# CustomOrthoKeyboard

A customizable 4x12 ortholinear keyboard powered by Zephyr RTOS, with support for custom shields, layouts, and future expansions.


## Features
- 4x12 ortholinear layout
- Zephyr-based firmware
- Custom keymaps and debounce tuning
- QMK-inspired structure
- USB input with hot-plug detection

## Folder Overview
- `boards/shields/`: Custom shield definitions and pin configs
- `config/`: Keymap and build configs for the keyboard
- `zephyr/`: Zephyr OS base setup
- `build.yaml`: Build process definition

## Getting Started
To build the firmware:
```bash
west init -l .
west update
west build -b <your_board> -p
