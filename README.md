### PICO Emulator Manifest

Welcome to the PICO Emulator Manifest repository! This repository is designed to facilitate the setup and management of the PICO Emulator development environment.

#### Table of Contents
<hr style="height:1px; background-color:#e5e5e5;margin: 5px;>

- [PICO Emulator Manifest](#pico-emulator-manifest)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Repository Structure](#repository-structure)
  - [Getting Started](#getting-started)
  - [Building the Emulator](#building-the-emulator)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)
  - [Contact](#contact)

#### Project Overview

The PICO Emulator is based on Google's open-source Android Open Source Project (AOSP) and aims to provide a robust environment for testing and development. This repository contains the manifest file needed to initialize the repository and access the modified code.

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
For Windows:
https://android.googlesource.com/platform/external/qemu/+/refs/heads/emu-master-dev/android/docs/WINDOWS-DEV.md

For Linux:
https://android.googlesource.com/platform/external/qemu/+/refs/heads/emu-master-dev/android/docs/LINUX-DEV.md

For Macos:
https://android.googlesource.com/platform/external/qemu/+/refs/heads/emu-master-dev/android/docs/DARWIN-DEV.md

#### License
This project is licensed under the GPLv2 License. See the LICENSE file for details.

#### Acknowledgments
We would like to express our gratitude to Google for their contributions to the Android Open Source Project (AOSP). Their work has laid the foundation for the development of the PICO Emulator and many other projects within the open-source community.

#### Contact
For questions or suggestions, please contact us through GitHub Issues.