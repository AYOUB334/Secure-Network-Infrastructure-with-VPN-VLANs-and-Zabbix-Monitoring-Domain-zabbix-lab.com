# Windows Server 2012 VM (VMware)

This VM is configured for lab use (e.g., domain controller, DNS, DHCP, etc.).

## 🖥️ Specs

- OS: Windows Server 2012 (Standard or R2)
- CPU: 2 Cores
- RAM: 3 GB
- Disk: 40 GB (dynamically allocated)
- Platform: VMware Workstation or Player

## 🌐 Network Setup

- Adapter 1: NAT (Internet access)
- Adapter 2: Host-only (for private LAN with other lab VMs)

See `network-config.md` for detailed VMware network adapter setup.

## 📦 VM Files

- `windows-server-2012.vmx`: VMware config file (import into Workstation)
- `windows-server-2012.vmdk`: ⚠️ Not included here. Download from [external link].

## 🛠️ Usage

1. Open VMware Workstation/Player
2. Click **"Open a Virtual Machine"**
3. Select `windows-server-2012.vmx`
4. Start the VM

## 📥 Download

> 🔗 The `.vmdk` file is too large for GitHub. Download the full VM from:
[https://your-link-to-image.com/ws2012-vm.zip](#)

## 🔐 Admin Credentials

- Username: `Administrator`
- Password: `dfghjk`
