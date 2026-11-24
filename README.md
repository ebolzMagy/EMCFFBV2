# EMCFFBV2 – USB HID Force Feedback Firmware

**EMCFFBV2** is an advanced USB HID firmware project that transforms supported microcontrollers (ESP32-S3 & STM32F4) into powerful **Force Feedback (FFB)** devices — perfect for DIY steering wheels, joysticks, and pedals.

It is designed for hobbyists, makers, and sim-racing enthusiasts who want to build custom, high-quality interactive controllers without proprietary hardware.

> **Project Status**  
> EMCFFBV2 is currently in **BETA** and under active development. Some features may be incomplete or subject to change. Feedback and contributions are welcome!

---

## ⚠️ IMPORTANT LICENSE NOTICE

**THIS IS A BINARY-ONLY DISTRIBUTION**  
This repository contains **COMPILED FIRMWARE (.hex files)** and **UTILITY SOFTWARE** only.  
**SOURCE CODE IS NOT INCLUDED OR PROVIDED.**

### 📜 Usage Terms:
- **Personal/DIY Use:** ✅ Allowed (non-commercial, personal projects only)
- **Commercial Use:** ❌ **STRICTLY PROHIBITED** without commercial license
- **Redistribution:** ❌ **NOT ALLOWED** in any form
- **Reverse Engineering:** ❌ **EXPRESSLY PROHIBITED**

### 🔒 LITE vs PRO Licensing:
- **LITE (Free):** Basic FFB, max 3 axes, max 2 buttons, fixed pinout, current limit 5A.
- **PRO (Paid License):** Full FFB effects, unlimited axes/buttons, XY Shifter, custom pin mapping, no current limit.

Attempting to bypass/crack PRO protection is **ILLEGAL**.

### 🏢 Commercial Licensing:
For commercial use (OEM, product integration, resale):
- **Volume pricing available**
- **Custom firmware options**
- **Technical support included**
- **Contact:** ebolz.magy@gmail.com

**By downloading or using these files, you agree to these terms.**

---

## Supported Platforms

| Board | MCU | Status |
|---|---|---|
| **ESP32-S3 DevKit C1** | ESP32-S3 | ✅ Supported |
| **WeAct BlackPill F401** | STM32F401 | ✅ Supported |
| **WeAct BlackPill F411** | STM32F411 | ✅ Supported |
| **Black F407VE** | STM32F407 | 🟡 Supported (Not fully tested) |
| **ODrive Mini (F405)** | STM32F405 | ✅ Supported |
| ~~LOLIN S2 Mini (ESP32-S2)~~ | ESP32-S2 | ⚠️ **Discontinued** (Poor ADC performance) |

> ⚠️ Installation procedures differ between ESP32 and STM32 platforms. Please follow the guides in the Wiki.

---

## Key Features

- **USB HID Compliant**
  - Works out of the box with DirectInput-based games and Windows `joy.cpl`
- **Advanced Force Feedback** *(PRO License required)*
  - Constant, Periodic (Sine, Square, Triangle), Spring, Damper, Friction, Inertia
- **Multi-Platform Support**
  - ESP32-S3 (Native USB)
  - STM32F4 (High-performance FOC, 1PWM/3PWM/6PWM support)
- **Broad Hardware Support**
  - Sensors: Quadrature encoders, SPI/Magnetic encoders, Potentiometers, Hall sensors
  - Current sensing: Inline shunt, low-side op-amp, Hall-effect sensors
- **Highly Configurable**
  - Axis mapping, sensor calibration, motor tuning via **EMCFFBV2 Utility**

---

## 📋 LITE vs PRO – What's the difference?

EMCFFBV2 uses a **modular licensing model**. You can build a fully functional device with the free LITE version, or unlock the full potential with a PRO license.

| Feature | LITE (Free) | PRO (License Required) |
| :--- | :--- | :--- |
| **Force Feedback** | Basic (Filters disabled) | ✅ Full FFB suite + Filters |
| **Axes** | Max 3 (1 FFB + 2 Regular) | ✅ Unlimited |
| **Buttons** | Max 2 | ✅ Unlimited |
| **XY Shifter** | ❌ No | ✅ Yes |
| **Custom Pin Mapping** | ❌ No | ✅ Yes |
| **Motor Current Limit** | Max 5A | ✅ No limit |

**For activation details, see:**  
👉 [License Activation Guide](https://github.com/ebolzMagy/EMCFFBV2/wiki/licenseActivation)

---

## Getting Started

1. **Download the latest release**
   - Visit the [Releases page](https://github.com/ebolzMagy/EMCFFBV2/releases)
   - Extract the `EMCFFBV2Utility` package.

2. **Flash the firmware**
   - 📘 [Firmware Installation Guide](https://github.com/ebolzMagy/EMCFFBV2/wiki/Installation)
   - Supports ESP32 (via Utility) and STM32 (DFU/ST-LINK).

3. **Wire your hardware**
   - 📘 [Hardware & Wiring Guide](https://github.com/ebolzMagy/EMCFFBV2/wiki/Hardware-Wiring)
   - Universal pinouts and component wiring.

4. **Configure via Utility**
   - 📘 [Utility Guide](https://github.com/ebolzMagy/EMCFFBV2/wiki/Utility-Guide)
   - Set up axes, buttons, motor drivers, and FFB profiles.

5. **Activate PRO License** *(Optional)*
   - Unlock unlimited hardware and full FFB features.

---

## 🚫 Prohibited Activities

The following are **STRICTLY PROHIBITED**:
- Selling or distributing modified versions
- Integrating into commercial products without a license
- Reverse engineering the firmware/software
- Sharing license keys or activation tools
- Using in commercial services/offerings

Violators will be subject to:
- DMCA takedown notices
- Legal action for copyright infringement
- Blacklisting from future updates

---

## Documentation & Community

- 📚 **Wiki**  
  https://github.com/ebolzMagy/EMCFFBV2/wiki

- 💬 **Discussions**  
  https://github.com/ebolzMagy/EMCFFBV2/discussions  
  *(Commercial inquiries via email only)*

- 🐞 **Bug Reports & Issues**  
  https://github.com/ebolzMagy/EMCFFBV2/issues

---

## 📞 Contact & Support

**For Personal Use Support:**
- GitHub Discussions
- Issue tracker

**For Commercial Licensing:**
- **Email:** ebolz.magy@gmail.com
- **Response Time:** 24-48 hours

**For Activation Issues:**
- Include purchase receipt
- Provide device ID (ChipID)

---

## Disclaimer

This firmware is provided **"AS IS"** without warranty of any kind.  
The developer is not responsible for:
- Damage to hardware
- Data loss
- Personal injury
- Commercial losses

Use at your own risk. Professional/commercial users should obtain appropriate licenses.

---

### 🚀 Happy building and enjoy Force Feedback!
*(with proper licensing)*
