#### Overview

The Pico emulator is a tool developed based on Google's open-source project AOSP, designed to replicate the PICO system's operating environment for use on PCs, including Windows, macOS, and Linux platforms. Its primary advantage is the elimination of reliance on physical PICO devices, making it ideal for a range of applications, including development, testing, and everyday usage.

Developer Instructions: [PICO Swan Emulator User Guide](https://developer-cn.picoxr.com/document/unity/pico-emulator/)

#### Repository Structure

~~~yaml
├── LICENSE
├── pico
│ ├── emu-35-6-release.xml
│ └── emu-35-rom.xml
└── README.md
~~~

- **LICENSE**: Contains the licensing information for the project.
- **pico/**: Directory containing the manifest files.
  - **emu-35-6-release.xml**: The manifest for the AOSP `emu-35-6-release` branch.
  - **emu-35-rom.xml**: The modified manifest specifically for the PICO Emulator.
- **README.md**: This file providing information about the project.

#### Getting Started

To initialize the repository and download the necessary code, execute the following command in your terminal:

~~~bash
repo init -g all -u https://github.com/Pico-Developer/PICO-Emulator-manifest.git -m pico/emu-35-rom.xml
~~~

#### Building the Emulator
- For Windows, see the [Android Emulator Windows Development](https://android.googlesource.com/platform/external/qemu/+/refs/heads/emu-master-dev/android/docs/WINDOWS-DEV.md)

- For Linux, see the [Android Emulator Linux Development](https://android.googlesource.com/platform/external/qemu/+/refs/heads/emu-master-dev/android/docs/LINUX-DEV.md)

- For MacOS, see the [Android Emulator MacOS Development](https://android.googlesource.com/platform/external/qemu/+/refs/heads/emu-master-dev/android/docs/DARWIN-DEV.md)

#### License
This project is licensed under the GPLv2 License. See the [LICENSE](./LICENSE) file for details.

#### Acknowledgments

This project acknowledges Google's substantial contributions to the AOSP, which have established a strong foundation for the PICO Emulator. We also express our gratitude to all contributors and stakeholders who support open-source initiatives, as their efforts are vital for advancing technology and fostering collaboration.

#### Contact
For questions or suggestions, please contact us through GitHub Issues.