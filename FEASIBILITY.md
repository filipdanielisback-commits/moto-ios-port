Moto G60 Native iOS Port — Feasibility Study

Project goal

Investigate whether genuine Apple iOS can boot on the Motorola Moto G60 using an architecture inspired by HakiOS.

This project is not an Android launcher, theme, or iOS simulation.

Target device

- Device: Motorola Moto G60
- Android device codename: "hanoip" (verify against the exact model)
- SoC: To be verified
- GPU: To be verified
- Bootloader status: Unknown
- Kernel source: Under investigation
- Native iOS compatibility: UNVERIFIED

Research references

- HakiOS kernel: https://github.com/oosexgang/hackios-xnu-kernel
- Moto G60 Android device tree: https://github.com/motorola-sm6150-devs/android_device_motorola_hanoip
- HakiOS project overview: https://hackiosx.dev/projects

Technical requirements

Investigate:

1. ARM64 boot and exception-level requirements.
2. Bootloader and UEFI support.
3. XNU kernel compatibility.
4. Memory layout and device-tree requirements.
5. Display and touchscreen drivers.
6. GPU acceleration.
7. Storage and filesystem access.
8. Wi-Fi and networking drivers.
9. Audio and power management.
10. iOS userspace compatibility.

Development rules

- Do not claim compatibility without evidence.
- Do not invent hardware addresses, drivers, or firmware.
- Do not flash experimental images during initial research.
- Preserve the original Android installation.
- Document every tested feature and its results.
- Keep proprietary Apple files out of the Git repository.

Initial status

Feasibility: NOT YET ESTABLISHED

Native iOS boot: NOT IMPLEMENTED

Device-specific drivers: NOT IMPLEMENTED

Next milestone: Verify the Moto G60 hardware and identify the differences between it and the existing HakiOS target.
