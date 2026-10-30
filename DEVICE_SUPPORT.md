Moto G60 Device Support Plan

Target device

- Phone: Motorola Moto G60
- Device codename: hanoip
- SoC family: Qualcomm Snapdragon 732G
- Project goal: Investigate a native Darwin/XNU-based operating system port for the Moto G60, based on the HakiOS project.

Current status

- HakiOS upstream source: Being inspected
- Moto G60 device compatibility: Not yet established
- Kernel build: Not yet verified
- QEMU boot: Not yet verified
- Moto G60 boot: Not yet verified

Development stages

1. Inspect HakiOS build requirements.
2. Identify the supported device and SoC configurations.
3. Compare the supported device with hanoip.
4. Identify required bootloader, kernel, display, touch, storage, and power-management work.
5. Attempt a safe development build.
6. Test in an emulator where possible.
7. Investigate physical-device boot only after compatibility and recovery procedures are understood.

Safety rules

- Do not flash unverified images.
- Do not overwrite the Android boot or recovery partitions.
- Keep the original firmware and a recovery plan.
- Do not claim Moto G60 support until a real device boot has been verified.

Important limitation

A native iOS or Darwin-based port is experimental and is not guaranteed to work on the Moto G60. HakiOS support for another phone does not establish compatibility with this device.
