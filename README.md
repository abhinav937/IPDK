# IPDK: Ice-Pi Development Kit

The Ice-Pi Development Kit (IPDK) is currently under development. More information will be available soon.

## Planned Features
- Plenty of PWM outputs for advanced power electronics applications
- High compute power for modern closed-loop control systems
- Raspberry Pi 5 runs programs for high-level monitoring and management
- Remote access via SSH for development and control
- Trigger outputs for connecting to oscilloscopes and measurement equipment
- Expansion options including I2C and SPI for current sensors or other peripherals

## Project Structure

```
IPDK/
├── hardware/                    # Hardware design files
│   ├── altium/                  # Altium PCB/schematic files
│   ├── planning/                # Design planning documents
│   │   ├── block-diagrams/      # System architecture diagrams
│   │   ├── schematics/          # Hand-drawn or concept schematics
│   │   └── requirements/        # Design requirements and specifications
│   └── references/              # Hardware reference materials
│       ├── components/          # Component datasheets
│       └── evaluation-boards/   # Reference board documentation
├── firmware/                    # Firmware code for embedded devices
│   ├── src/                     # Source code
│   └── build/                   # Build scripts and outputs
├── software/                    # Higher-level software (Raspberry Pi apps)
│   ├── src/                     # Source code
│   ├── docs/                    # Software-specific documentation
│   └── build/                   # Build outputs
├── docs/                        # General project documentation
│   ├── user-manual/            # End-user documentation
│   ├── assembly-guide/         # Assembly instructions
│   └── troubleshooting/        # Known issues and solutions
├── fab/                        # Fabrication outputs
│   ├── gerbers/                # Gerber files for PCB fabrication
│   ├── bom/                    # Bill of Materials
│   └── assembly/               # Assembly drawings and files
└── releases/                   # Versioned releases
    └── v0.1/                   # Example release folder
```

## Getting Started

### For Hardware Development
- **Design Files**: See `hardware/altium/` for PCB schematics and layouts
- **Planning**: Check `hardware/planning/block-diagrams/` for system architecture
- **References**: Find component datasheets in `hardware/references/components/`

### For Firmware Development
- **Source Code**: Add your embedded code to `firmware/src/`
- **Build Outputs**: Generated files go in `firmware/build/`

### For Software Development
- **Raspberry Pi Apps**: Add your Python/C++ code to `software/src/`
- **Documentation**: Software-specific docs in `software/docs/`

## Contributing

When adding new files:
1. Place them in the appropriate folder based on their purpose
2. Update this README if adding new folder types
3. Follow the existing naming conventions
4. Add meaningful commit messages
