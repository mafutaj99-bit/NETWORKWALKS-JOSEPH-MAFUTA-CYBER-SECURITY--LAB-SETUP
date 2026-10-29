# NETWORKWALKS-JOSEPH-MAFUTA-CYBER-SECURITY--LAB-SETUP
My personal Cyber Security lab setup featuring Kali Linux and VirtualBox configurations 
# Cyber Security Home Lab Setup

Welcome to my personal Cyber Security Lab! This repository documents the setup, configuration, and troubleshooting of my virtual environment.

## Objective
To build a safe, isolated environment for practicing penetration testing, vulnerability analysis, and network security using Kali Linux.

## Lab Components
*   **Host OS:** Windows 11
*   **Virtualization Software:** Oracle VirtualBox
*   **Attacker Machine:** Kali Linux (VirtualBox Image)
  
##Troubleshooting & Fixes
During the initial setup, I encountered a few hurdles and successfully resolved them:

### 1. VirtualBox UUID Conflict
*   **Issue:** VirtualBox threw an `E_FAIL (0x80004005)` error because the VM's UUID conflicted with an existing machine in the registry.
*   **Fix:** Used the Command Prompt to generate a new UUID for the virtual hard disk using `VBoxManage internalcommands sethduuid`. Then, created a new VM wrapper in VirtualBox and attached the existing `.vdi` disk.

### 2. Machine Folder Creation Error
*   **Issue:** VirtualBox could not create the machine folder due to path/permission restrictions on the selected drive.
*   **Fix:** Changed the default machine folder path to a standard, accessible directory and manually re-attached the storage.

## Next Steps
- [ ] Install VirtualBox Guest Additions (for better screen resolution and clipboard sharing).
- [ ] Take a baseline snapshot of the clean Kali installation.
- [ ] Configure a host-only network adapter for safe, isolated traffic.

## Resources
*   [Kali Linux Documentation](https://www.kali.org/docs/)
*   [VirtualBox Manual](https://www.virtualbox.org/manual/)
