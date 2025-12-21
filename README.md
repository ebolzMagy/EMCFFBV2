# EMCFFBV2 – USB HID Force Feedback Firmware

**EMCFFBV2** is an advanced firmware project that transforms supported microcontroller platforms into a **USB HID (Human Interface Device)** with **Force Feedback (FFB)** capabilities.

It is designed for hobbyists, makers, and simulation enthusiasts who want to build custom **force feedback devices** such as steering wheels, joysticks, pedals, and other interactive controllers.

EMCFFBV2 currently supports both **ESP32** and **STM32** platforms, offering flexibility across different hardware ecosystems.

> **Project Status**  
> EMCFFBV2 is currently in **BETA** and under active development.  
> Some features may be incomplete or subject to change. Feedback and contributions are welcome.

---

## Supported Platforms

- **ESP32-S2**
- **ESP32-S3**
- **STM32F4 series** (ODRIVE MINI – STM32F405)

> ⚠️ Installation procedures differ between ESP32 and STM32 platforms.  
> Please follow the appropriate guide in the Wiki.

---

## Key Features

- **USB HID Compliant**
  - Works with DirectInput-based applications and games
- **Force Feedback Support**
  - Constant Force  
  - Periodic effects (Sine, Square, Triangle)  
  - Spring, Damper, Friction, Inertia
- **Multi-Platform Support**
  - ESP32-S2 / ESP32-S3 (native USB)
  - STM32F4 via ODRIVE MINI
- **Highly Configurable**
  - Axis mapping
  - Sensor selection
  - Motor and driver configuration

---

## Licensing Notice (Important)

> 🔒 **Force Feedback (FFB) functionality requires license activation.**

- **FFB features are not free** and must be activated via the **License Activation** process.
- All **non-FFB features** (USB HID axes, buttons, basic input devices) are **free to use**.
- Licensing is **device-based**.

For details, see:
👉 [License Activation Guide](https://github.com/ebolzMagy/EMCFFBV2/wiki/licenseActivation)

---

## Typical Use Cases

- 🎮 **Force Feedback Steering Wheels**
- 🕹️ **Joysticks and Controllers**
- 🏎️ **Driving and Flight Simulators**

---

## Getting Started

1. **Download the latest release**
   - Visit the [Releases page](https://github.com/ebolzMagy/EMCFFBV2/releases)
   - Download the package for your platform

2. **Follow the installation guide**
   - 📘 [Firmware Installation](https://github.com/ebolzMagy/EMCFFBV2/wiki/Firmware-Installation)

3. **Configure your hardware**
   - GPIO setup
   - Axis setup
   - Sensor selection
   - Motor & driver configuration

---

## Documentation & Community

- 📚 **Wiki**  
  https://github.com/ebolzMagy/EMCFFBV2/wiki

- 💬 **Discussions**  
  https://github.com/ebolzMagy/EMCFFBV2/discussions

- 🐞 **Bug Reports & Issues**  
  https://github.com/ebolzMagy/EMCFFBV2/issues

---

## Disclaimer

This project is provided **as-is** and is still under active development.  
Unexpected behavior or unfinished features may exist.

If you encounter bugs or have suggestions, please report them via GitHub Issues.

---

### 🚀 Happy building and enjoy Force Feedback!
