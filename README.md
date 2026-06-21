# Astrocopilot

Your personal astrophotography assistant and planning tool.

## Overview

Astrocopilot is an all-powerful assistant designed to help astrophotography enthusiasts with:

- **Planning Sessions**: Calculate crucial parameters for your imaging sessions
- **Target Recommendations**: Get recommendations for targets based on your camera
- **Educational Resources**: Access learning materials and guides
- **Camera Database**: Look up specifications for your camera equipment

## Features

### Calculators
- **Star Trail Calculator**: Prevent star trails using 500-rule (normal) or NPF-rule (advanced) calculations
- **FOV Calculator**: Calculate your field of view to know how much sky you'll capture
- **EV Calculator**: Calculate exposure value based on your camera settings
- **Integration Time Calculator**: Calculate total integration time for light frames
- **Image Scale Calculator**: Determine how many arcseconds each pixel covers

### Camera Information Database
Browse and search camera specifications to find detailed information about your equipment.

### Resource Hub
Access curated resources including:
- Star tracking and alignment guides
- Image processing tutorials

### Target Recommendation Engine
Get personalized recommendations for celestial targets based on your focal length and camera specifications. Currently supports all Messier objects.

## Installation

-just download the zip from the release page(for now being: astrocopilot_v1.0.0.7z)

## Usage

The program presents a main menu where you can choose:
- **calculators**: Access various astrophotography calculators
- **resources**: Browse learning materials
- **target recommendation**: Get target suggestions for your setup
- **camera info**: Look up camera specifications

Type 'q' at any time to return to the previous menu or exit.

## Project Structure

```
Astrocopilot/
├── astrocopilot.py                 # Main entry point
├── calculators/                    # Calculator modules
│   ├── Functions.py               # Core calculation functions
│   ├── calculators_hub.py         # Calculator menu interface
│   ├── startrail_cac.py          # Star trail prevention calculator
│   ├── FOV_cac.py                # Field of view calculator
│   ├── EV_cac.py                 # Exposure value calculator
│   ├── Integration_cac.py        # Integration time calculator
│   └── Image_scale_cac.py        # Image scale calculator
├── camera_info_lookup/             # Camera database module
│   ├── cam_info_lookup.py        # Camera lookup interface
│   └── FUNCTIONS.py              # Database navigation functions
├── resources/                      # Learning resources module
│   ├── resources_hub.py          # Resources menu interface
│   └── FUNCTIONS.py              # Resource navigation functions
├── target_recommendation/          # Target recommendation module
│   ├── target_recommedator.py    # Target recommendation interface
│   └── FUNCTIONS.py              # Recommendation engine
└── databases/                      # Data files
    ├── cameras.json              # Camera specifications database
    ├── Messier_targets.json      # Messier objects database
    └── resources.json            # Learning resources database
```

## Future Updates

This project is in its early stages. Planned enhancements include:
- Additional calculators for advanced astrophotography calculations
- Extended camera database with more models
- More celestial object catalogs (NGC, IC, etc.)
- Enhanced user interface
- AI assistant chatbox

## Requirements

- Python 3.x
- No external dependencies required (uses only standard library)

## Notes

- When entering menu choices, capitalization doesn't matter (case-insensitive)
- The camera and target databases can be expanded as the project grows
- All calculator results are approximate and should be verified for critical applications
- Presets are used only for the FOV calculator and the target recommendation. For additional information use the camera info option

## Contributing

To contribute improvements or report issues, please ensure any code additions follow the existing style and include appropriate comments and docstrings.

---

**Status**: Early Development

This Copilot is still in its very early stages. Feedback and contributions are welcome to help expand its capabilities!
