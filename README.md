# Kernel config for my lenovo w530

- Based on a minimal config from kernel-seeds
- Targeting ~amd64 Gentoo Linux running on systemd or openrc
- Set default hostname to w530
- Kernel and initramfs must be gzip-compressed
- No bluetooth support yet

Added support for:
- Intel SATA chipset
- Intel GPU
- iwlwifi
- e1000e Ethernet
- Webcam
- MMC/SDcard
- USB 3
- Logitech Unified Receiver
- ACPI Battery and stuff
- Suspend to Ram
- Thinkpad ACPI extras
- Intel Coretemp
- Intel cpuidle driver
- Initramfs
- Early Cryptsetup
- KVM
- HD Audio with Realtec Codec
- ext2/3/4
- btrfs
- dosfs
- android USB tethering

Probably more stuff I already forgot....
