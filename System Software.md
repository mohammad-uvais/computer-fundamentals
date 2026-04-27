This software is responsible for controlling, integrating, and managing the individual hardware components of a computer system.
System software is the set of programs and services that manage hardware resources and provide a platform for running application software. It operates between hardware and applications.

## Firmware

Low-level code embedded in hardware.
Small programs stored on chips (BIOS/UEFI) that initialize hardware and begin the boot process.

Boot flow (simple): Power on -> Firmware performs checks -> Bootloader loads OS kernel -> Kernel initializes services -> Login / desktop.

Example:
- BIOS/UEFI
- Microcontroller firmware

## [[Operating System]] (OS)

The master program. It manages memory, files and processes.
Kernel + core services (schedulers, memory manager, file system, drivers).

Examples:
- Windows
- MacOS
- Linux/Unix
- Android
- iOS

## Device Drivers

Programs that act as a bridge between the OS and specific hardware.
Hardware-specific modules that let the OS control devices.
Translate OS calls into device-specific instructions.

Example:
- Graphics Driver
- USB Driver

## System Utility Software

Software designed to maintain the system's performance and security.

Examples:
- Antivirus
- Disk Cleanup
- Disk Partition
- Backup Tools
- Task Manager