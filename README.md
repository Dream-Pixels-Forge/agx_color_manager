# AgX Color Manager for Blender

## Overview
AgX Color Manager is a color management system addon for Blender that provides advanced control over color grading and image processing. This addon implements the AgX color science for accurate and cinematic results.

## Features
- Automatic AgX color management setup
- Advanced exposure and contrast controls
- Highlight and shadow recovery
- Color tinting capabilities
- False color display mode for exposure checking
- Intelligent texture color space management
- Debug logging system for troubleshooting

## Requirements
- Blender 4.2.0 or newer
- Compatible with Windows, macOS, and Linux

## Installation
1. Download the latest release from the repository
2. In Blender, go to Edit > Preferences > Add-ons
3. Click "Install" and select the downloaded .zip file
4. Enable the addon by checking the checkbox next to "Render: AgX Color Manager"

## Usage

### Quick Setup
1. Navigate to Properties > Render > AgX Color Manager
2. Click "Setup AgX" to automatically configure color management
3. Use "Defaults" to reset all settings to their default values

### Main Settings
- **Exposure**: Adjust global exposure compensation (-5.0 to 5.0)
- **Contrast**: Control global contrast levels (0.0 to 2.0)
- **Saturation**: Adjust color saturation (0.0 to 2.0)

### Recovery Tools
- **Highlight Recovery**: Recover detail in bright areas (0.0 to 2.0)
- **Shadow Recovery**: Enhance shadow detail (-1.0 to 1.0)

### Color Controls
- **Color Tint**: Apply global color tinting
- **False Color**: Toggle false color mode for exposure checking

## Preferences
Access addon preferences through Edit > Preferences > Add-ons > AgX Color Manager

### Available Options
- **Auto Setup**: Automatically configure AgX on file load
- **Debug Mode**: Enable detailed logging for troubleshooting
- **Default Look**: Choose default AgX look preset
  - None
  - Medium Contrast
  - High Contrast
  - Custom

## Texture Management
The addon automatically manages texture color spaces based on filename patterns:
- Color textures (basecolor, diffuse, albedo, etc.)
- Non-color data (normal, roughness, metallic, etc.)
- HDR formats (.exr, .hdr)

## Technical Details
- Implements professional-grade color management workflow
- Supports various AgX look presets
- Includes comprehensive logging system
- Maintains proper color space assignments for different texture types

## Troubleshooting
1. Check the addon preferences and ensure settings are correctly configured
2. Enable Debug Mode in preferences for detailed logging
3. Logs are stored in the system temp directory as "agx_color_manager.log"

## Known Limitations
- Requires Blender's native color management system
- Some features may be GPU-dependent
- HDR texture processing may require additional system resources

## Development
The addon is structured with:
- Core color management system
- Enhanced logging capabilities
- Texture profile management
- UI panels and operators
- Persistent settings management

## License
[GNU -3.0 License]

## Author
Dimona Patrick

## Support
[dream.pixels.forge@gmail.com]

## Version History
### 1.0.1
- Current stable release
- Compatible with Blender 4.2.0
- Improved texture handling
- Enhanced logging system


