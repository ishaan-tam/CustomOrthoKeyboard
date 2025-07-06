# 60-Key Custom Keyboard (4x12 Layout)

A custom 60% keyboard running on Zephyr RTOS with support for custom firmware, shields, and keymaps.

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
