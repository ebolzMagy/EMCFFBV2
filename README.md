# EMCFFBV2 - ESP32-Based USB HID Force Feedback Device

**EMCFFBV2** is an advanced project that implements a **USB HID (Human Interface Device)** with **Force Feedback (FFB)** capabilities, powered by the **ESP32-S2** or **ESP32-S3** microcontroller. This project is designed for hobbyists and enthusiasts who want to create custom force feedback devices such as gaming controllers, steering wheels, joysticks, or other interactive input devices.

> **Note**: This project is currently in **BETA version**. It is still under active development, and there may be bugs or unfinished features. Your feedback and contributions are highly appreciated as we work to improve and stabilize the project.

## Key Features
- **USB HID Compliance**: Fully compliant with USB HID standards.
- **Force Feedback Support**: Implements force feedback effects like constant force, sine, square, spring, damper, inertia, and friction.
- **ESP32-S2/S3 Powered**: Utilizes the ESP32-S2 or ESP32-S3 microcontroller.
- **Customizable**: Easily adaptable to various hardware configurations.

## Use Cases
- **Gaming Controllers**: Create force feedback-enabled gaming peripherals.
- **Simulators**: Enhance flight or driving simulators.
- **DIY Projects**: Perfect for makers and hobbyists.

## Getting Started
To get started with EMCFFBV2, follow these steps:
1. **Download the latest release**:
   - Go to the [Releases page](https://github.com/ebolzMagy/EMCFFBV2/releases) and download the `.zip` file for your platform.
2. **Set up the ESP-IDF framework**:
   - Follow the instructions in the [Wiki](https://github.com/ebolzMagy/EMCFFBV2/wiki) to set up the ESP-IDF development environment.
3. **Build and flash the firmware**:
   - Use the ESP-IDF tools to build and flash the firmware to your ESP32-S2/S3 device.
4. **Connect your hardware**:
   - Connect your motors, sensors, and other peripherals as described in the [Hardware Setup Guide](https://github.com/ebolzMagy/EMCFFBV2/wiki/Hardware-Setup).
5. **Test the force feedback functionality**:
   - Run the application and test the force feedback effects.

For more detailed instructions, troubleshooting, and FAQs, visit the [Wiki](https://github.com/ebolzMagy/EMCFFBV2/wiki) or join the [Discussions](https://github.com/ebolzMagy/EMCFFBV2/discussions) to ask questions and share ideas.

> **Disclaimer**: This project is still in development. Some features may not work as expected, and there may be occasional bugs. If you encounter any issues, please report them in the [Issues](https://github.com/ebolzMagy/EMCFFBV2/issues) section.

## Support the Project
If you find this project useful, consider supporting its development:

- **Donate via PayPal**: [PayPal.me Link]
- **Report Issues**: Help us improve by reporting bugs or suggesting new features.

### Free vs Full Version
The **free version** of this project includes basic Force Feedback (FFB) effects:
- **Desktop Spring**: Simulates a spring force centered on the desktop.
- **Endstop**: Provides a hard stop effect at the boundaries.

To unlock the **full version** with access to all FFB effects (such as constant force, sine, square, damper, inertia, and friction), you can support this project by donating a minimum of **10 USD** via [PayPal.me/ebolzmagy](https://paypal.me/ebolzmagy). Your contribution will help us continue developing and improving this project!

---

Thank you for your support! Your generosity enables us to keep creating and maintaining high-quality projects for the community.

---

### **Feedback and Bug Reports**
Your feedback is invaluable to us! If you encounter any issues or have suggestions for improvement, please:
- Open an issue on the [Issues page](https://github.com/ebolzMagy/EMCFFBV2/issues).
- Provide as much detail as possible, including steps to reproduce the issue.

---

### **Join the Discussion**
Have questions, ideas, or want to share your experience? Join the [Discussions](https://github.com/ebolzMagy/EMCFFBV2/discussions) to connect with the community!

---

## License
This project is licensed under the **Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)** license. You are free to share and use this project, but **modification and redistribution of modified versions are prohibited**. For more details, see the [LICENSE](LICENSE) file.
