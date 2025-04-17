# DCC-EX EX-CommandStation Home Assistant Integration
This custom integration allows Home Assistant to monitor and control an [EX‑CommandStation](https://dcc-ex.com/ex-commandstation/index.html) — a simple but powerful DCC/DC command station used to run model train layouts.

# EX‑CommandStation Integration for Home Assistant
This custom integration allows Home Assistant to monitor and control an [EX‑CommandStation](https://dcc-ex.com/ex-commandstation/index.html) — a simple but powerful DCC/DC command station used to run model train layouts.

## Features
- (Planned) Monitor status of the EX‑CommandStation
- (Planned) Control locomotives, turnouts, and routes

## Installation
Clone this repository into your Home Assistant's `custom_components` directory:

```bash
cd config/custom_components
git clone https://github.com/SenMorgan/ha-excommandstation
```

## Configuration
Basic configuration (coming soon):

```yaml
excommandstation:
    host: "x.x.x.x"  # IP address or hostname of the EX‑CommandStation
    port: 2560       # Port number (default is 2560)
```

## License
Copyright (c) 2024 Sen Morgan. Licensed under the MIT license, see LICENSE.md
