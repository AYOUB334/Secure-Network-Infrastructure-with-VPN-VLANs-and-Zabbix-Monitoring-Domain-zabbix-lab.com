# ONOS VMware VM

This folder contains configuration and setup instructions for the ONOS virtual machine used in this lab.

## Files

- `onos-vm.vmx`: VMware configuration file
- `onos-network-setup.md`: Details on bridged/host-only interface setup

## System Specs

- OS: Ubuntu 20.04 (64-bit)
- RAM: 2 GB
- CPU: 2 cores
- Disk: 10 GB

## Network Configuration

- NIC 1: Bridged (access to LAN)
- NIC 2: Host-only (internal communication)

## Download VM Image

📦 Due to file size, the `.vmdk` (virtual disk) is not stored in this repo.

👉 You can download it from:  
[https://your-link-to-image.com/onos-vm.7z](#)

Or build manually using instructions in `onos-network-setup.md`.

---

🛠️ To import:
1. Open VMware Workstation / Player
2. Open `onos-vm.vmx`
3. Start the VM
