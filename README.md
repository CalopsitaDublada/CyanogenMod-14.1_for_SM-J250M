# CyanogenMod-14.1_for_SM-J250M
-> CyanogenMod Port for SM-J250M - Status: Not Booting

# CyanogenMod 14.1 for Samsung Galaxy J2 Pro 2018

An unofficial CyanogenMod 14.1 port for the Samsung Galaxy J2 Pro 2018 (SM-J250M).

The project aims to bring Android 7.1.2 Nougat, powered by CyanogenMod 14.1, to the Samsung Galaxy J2 Pro 2018.

> **Status: Work in Progress**
>
> This port is under development. Device compatibility, hardware functionality,
> and boot stability have not yet been fully verified.

---

## 📱 Device Information

| Component | Details |
|---|---|
| Device | Samsung Galaxy J2 Pro 2018 |
| Model | SM-J250M |
| Device codename | `j2y18lte` |
| SoC | Qualcomm Snapdragon 425 |
| SoC platform | MSM8917 |
| CPU architecture | ARM 32-bit |
| GPU | Qualcomm Adreno 308 |
| Target ROM | CyanogenMod 14.1 |
| Android version | Android 7.1.2 Nougat |
| Kernel | Linux 3.18.31 |
| Development status | Work in Progress |

---

## 🎯 Project Goals

The main goals of this project are:

- Port CyanogenMod 14.1 to the Samsung Galaxy J2 Pro 2018 SM-J250M.
- Establish a working device configuration for `j2y18lte`.
- Adapt the kernel and device configuration to the target model.
- Integrate the required proprietary vendor components.
- Fix hardware compatibility issues.
- Improve system stability and performance.
- Publish development progress, fixes, and future releases.

---

## 🛠️ Development

This project is being developed using the CyanogenMod 14.1 source tree.

The development process may involve:

- Device configuration (`device/samsung/j2y18lte`).
- Kernel sources and configuration.
- Proprietary vendor files extracted from compatible firmware.
- Android BoardConfig and product configuration.
- Hardware abstraction layers and device-specific components.
- Boot image configuration and device tree compatibility.

### Important Compatibility Note

The SM-J250M and SM-J250F belong to the same device family, but their
compatibility must not be assumed.

Device trees, kernels, modem components, partition layouts, boot images,
and proprietary binaries must be checked against the target SM-J250M.

A successful build does not necessarily mean that the ROM will boot or that
all hardware components will work.

---

## 📋 Current Status

The following checklist tracks development progress.

- [ ] Verify device tree compatibility with SM-J250M.
- [ ] Review kernel sources and configuration.
- [ ] Prepare required proprietary vendor files.
- [ ] Configure the CyanogenMod 14.1 build environment.
- [ ] Complete the first ROM build.
- [ ] Verify boot image compatibility.
- [ ] Test initial boot.
- [ ] Verify display and touchscreen.
- [ ] Test Wi-Fi and Bluetooth.
- [ ] Test audio and microphone.
- [ ] Test camera.
- [ ] Verify mobile network, calls, and SMS.
- [ ] Test sensors and other hardware.
- [ ] Publish a stable release.

Items should only be marked complete after they have been tested.

---

## 📦 Downloads

Official project builds will be published through GitHub Releases.

**No official builds are available yet.**

When a release becomes available, its release notes should include:

- Build date.
- Android version.
- Supported device model.
- Installation instructions.
- Known issues.
- Tested hardware features.
- Checksums for published files.

---

## ⚠️ Disclaimer

This is an unofficial community development project.

CyanogenMod is discontinued software, and this project is not affiliated
with or endorsed by Samsung or the original CyanogenMod team.

Installing custom firmware can cause data loss or render a device unusable
if the firmware is incompatible or incorrectly installed.

Always verify the exact device model and read the installation instructions
before attempting to install a build.

The developers are not responsible for damage caused by improper installation.

---

## 🤝 Contributing

Contributions, bug reports, testing results, and technical discussions are welcome.

When reporting a problem, please include:

- Exact device model.
- ROM build identifier.
- Steps to reproduce the problem.
- Relevant logs, when available.
- Whether the problem occurs consistently.

Do not report an untested feature as working.

---

## 📜 License

CyanogenMod and Android components are distributed under their respective
licenses.

Kernel sources, device configuration files, and other components may have
different licensing requirements. Refer to the relevant upstream projects
and source files for their applicable licenses.

Proprietary firmware components remain subject to their respective owners'
licenses.

---

**Project:** CyanogenMod 14.1 for Samsung Galaxy J2 Pro 2018

**Target:** Samsung Galaxy J2 Pro 2018 SM-J250M (`j2y18lte`)

**Android:** 7.1.2 Nougat
