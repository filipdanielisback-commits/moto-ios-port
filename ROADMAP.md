Moto G60 Native iOS Port — Roadmap

Our goal is to investigate and develop a genuine native iOS port for the Motorola Moto G60, inspired by HakiOS.

This is an experimental operating-system research project, not an Android launcher or theme.

Phase 1 — Hardware research

- [ ] Verify the exact Moto G60 model and codename.
- [ ] Document the Snapdragon 732G platform and Adreno 618 GPU.
- [ ] Identify the boot chain and available UEFI support.
- [ ] Locate relevant Android kernel sources.
- [ ] Compare the Moto G60 hardware with the existing HakiOS target.
- [ ] Document hardware compatibility gaps.

Phase 2 — Upstream analysis

- [ ] Read the HakiOS architecture documentation.
- [ ] Inspect its device-specific implementation.
- [ ] Identify reusable components and their licenses.
- [ ] Document the changes required for a new device.
- [ ] Record build requirements.

Phase 3 — Development environment

- [ ] Establish a reproducible Linux build environment.
- [ ] Verify required compiler and build-tool versions.
- [ ] Build a generic open-source research target.
- [ ] Add automated checks where possible.
- [ ] Document build logs and test results.

Phase 4 — Device-specific research

- [ ] Investigate UEFI and bootloader compatibility.
- [ ] Investigate memory layout and device-tree requirements.
- [ ] Identify display and touchscreen requirements.
- [ ] Investigate GPU initialization.
- [ ] Investigate storage and firmware dependencies.
- [ ] Document a safe recovery strategy.

Phase 5 — Experimental boot

- [ ] Demonstrate the earliest feasible boot milestone.
- [ ] Capture and analyze boot logs.
- [ ] Validate kernel initialization.
- [ ] Investigate display and touchscreen support.
- [ ] Test further components only when the preceding milestones succeed.

Phase 6 — Native iOS environment

- [ ] Establish whether the chosen XNU and iOS versions are compatible.
- [ ] Investigate legitimate system-image preparation.
- [ ] Test userspace startup.
- [ ] Verify the lock screen and home screen.
- [ ] Evaluate Wi-Fi, audio, graphics, and other hardware individually.

Safety rules

- Never flash an unverified image.
- Never assume another phone's boot image is compatible.
- Preserve a recoverable Android installation.
- Keep proprietary firmware and Apple system binaries out of the repository.
- Mark every untested feature as unverified.
- Do not claim successful iOS boot without reproducible evidence.

Current status

Stage: Initial research

Target device: Motorola Moto G60

Native iOS boot: Not demonstrated

Next milestone: Complete hardware and upstream compatibility research.
