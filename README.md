# ShadowDuck Hardware

## DRAFT

<!-- Repo Cover Image -->
<p align="center">
<img align="center" src="https://github.com/KobolSystems/ShadowDuck_Firmware/blob/main/repoLogo.png?raw=true" width="450px"/>
</p>

## Overview
The ShadowDuck is a hardware platform designed for performing keystroke injection attacks. Our goal with this platform is to provide a budget-friendly, educational, and ethical pen-testing tool that resembles a legitimate USB stick, avoiding unnecessary scrutiny. We aim to give newcomers to cybersecurity the opportunity to experiment with these tools and eventually apply their skills in legitimate, professional roles within the industry.

## PCB Render

add renders here

## Technical Specifications
- **PCB Dimensions:** 50mm x 20mm
- **Layers:** 2
- **Material:** FR4
- **Thickness:** 1.6mm
- **Copper Weight:** 1oz (35µm)
- **Surface Finish:** HASL (Lead-Free)
- **Color:** Black Solder Mask with White Silkscreen
- **Connectors:**
  - USB-A Male Connector
  - SWD Programming Header
- **Microcontroller:** RP2040
- **Power Supply:**
  - 5V from USB
  - 3.3V LDO Regulator
- **LED Indicators:**
  - Power LED (Red)
  - Status LED (Green)

## Components
- **Microcontroller:** Raspberry Pi RP2040
- **Memory:** 2MB QSPI Flash
- **Crystal Oscillator:** 12MHz
- **Capacitors:**
  - 10µF (4x)
  - 0.1µF (2x)
- **Resistors:**
  - 10kΩ (2x)
- **LEDs:**
  - Red LED (Power)
  - Green LED (Status)

## Getting Started
### Prerequisites
- [KiCad](https://kicad.org/) (for viewing and editing the PCB design files)
- [PlatformIO](https://platformio.org/) (for firmware development)
- Basic knowledge of PCB design and electronics

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/KobolSystems/ShadowDuck_Hardware.git
   cd ShadowDuck_Hardware
   ```
**Something about opening in eagle**

## Contributing
We welcome contributions from the community. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.


<!-- Licencing Always at the Bottom -->
------------
### Licencing <img alt="" align="right" src="https://img.shields.io/badge/Licence-CC--BY--NC--SA--4.0-informational?style=flat&logo=Creative%20Commons&logoColor=white&color=EF9421" />

**Creative Commons: Attribution - NonCommercial - ShareAlike 4.0 International (CC BY-NC-SA 4.0)**


**You are free to:**

**Share** — copy and redistribute the material in any medium or format

**Adapt** — remix, transform, and build upon the material


**Under the following terms:**

**Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

**NonCommercial** — You may not use the material for commercial purposes.

**ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
