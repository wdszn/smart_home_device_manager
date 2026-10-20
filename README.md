# Smart Home Device Manager

A Python desktop application developed as part of my first-year Computer Science coursework at the University of Portsmouth.

The application uses Tkinter to provide a graphical interface for managing simulated smart home devices, demonstrating object-oriented programming principles and GUI development.

## Features

- Add and remove simulated smart home devices.
- Toggle individual devices on and off.
- Switch all devices on or off simultaneously.
- Edit device-specific settings.
- Display device statuses through a dynamically updated interface.
- Manage up to 10 devices.
- Validate device settings and user inputs.

## Supported Devices

| Device | Functionality |
|---|---|
| Smart Plug | Toggle power and configure consumption rate (0–150). |
| Smart Heater | Toggle power and adjust heating level (0–5). |
| Smart Doorbell | Toggle power and enable or disable sleep mode. |

## Technologies

- **Python** — Application logic and object-oriented programming.
- **Tkinter** — Desktop graphical user interface.

## Project Structure

```text
smart-home-device-manager/
├── backEnd.py
├── frontEnd.py
└── README.md
```

- `backEnd.py` — Device classes, state management, validation and manual tests.
- `frontEnd.py` — Tkinter interface and user interactions.

## Getting Started

1. Install Python 3 with Tkinter support.
2. Clone or download the repository.
3. Open a terminal in the project directory.
4. Run:

```bash
python frontEnd.py
```

## Known Limitations

- Adding Smart Heater and Smart Doorbell devices through the GUI requires a constructor fix.
- Device states are stored in memory and reset when the application closes.
- The application simulates devices rather than connecting to physical smart home hardware.
- Some invalid operations are not fully handled by the GUI.

## Academic Context

**University:** University of Portsmouth  
**Course:** BSc (Hons) Computer Science  
**Level:** First Year Coursework
