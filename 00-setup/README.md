# Lab 00 — My IT Lab Setup (VMware + Ubuntu)

## What I built
I set up a safe practice lab on my Windows laptop using VMware (a “computer inside a computer”) and installed Ubuntu Linux as a virtual machine.

## My computer (Host)
- Device: Lenovo V14 Gen 5 IRL
- OS: Windows 11 Pro
- Specs: i5-13420H, 16GB RAM, 512GB SSD

## My virtual machine (Guest)
- VM name: UBU01
- OS: Ubuntu 24.04.3 LTS
- Settings: 2 CPU cores, 4GB RAM, 60GB disk, NAT networking
- Files stored in:
  - C:\ISOs (installer files)
  - C:\VMs (virtual machines)

## What went wrong and how I fixed it
**Problem:** The Ubuntu screen flickered during installation.  
**Fix:** In VMware settings I disabled “Accelerate 3D graphics”.  
**Result:** The VM display became stable.
**Verification:** VM boots successfully and Ubuntu desktop loads normally.

## Proof (screenshots)
- `screenshots/ubuntu_desktop.png` — Ubuntu desktop running inside VMware after install
- `screenshots/vm_summary.png` — VMware VM hardware summary (CPU/RAM/Disk/NAT)
