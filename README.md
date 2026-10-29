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













<img width="626" height="510" alt="installation error" src="https://github.com/user-attachments/assets/6fb32ed5-a8cc-45ad-afb1-53bd18f9a17e" />
<img width="647" height="502" alt="Screenshot 2026-10-28 125831" src="https://github.com/user-attachments/assets/0b2c3529-30a2-4241-9332-6254e49ff3b0" />
<img width="726" height="572" alt="Screenshot 2026-10-28 131645" src="https://github.com/user-attachments/assets/4247d32f-4ebe-4be7-b3b0-cb2451049f9e" />
<img width="1912" height="1077" alt="Screenshot 2026-10-28 133738" src="https://github.com/user-attachments/assets/347711cf-47ba-42d0-9f28-5b3b6ff7e84c" />
<img width="1897" height="1077" alt="Screenshot 2026-10-28 134128" src="https://github.com/user-attachments/assets/88040b38-d70b-4ccb-9fb1-b54e26b37ff4" />
<img width="1902" height="1077" alt="Screenshot 2026-10-29 105125" src="https://github.com/user-attachments/assets/22fc0c38-5025-4eb4-a363-6119e735118a" />
<img width="1915" height="1077" alt="Screenshot 2026-10-28 134951" src="https://github.com/user-attachments/assets/11960929-4630-462d-9ef3-f9c2721c17bd" />
<img width="1917" height="1077" alt="Screenshot 2026-10-28 141530" src="https://github.com/user-attachments/assets/9021a43d-6930-4ac5-8e57-06bc42dc472e" />
<img width="1916" height="1025" alt="Screenshot 2026-10-28 140829" src="https://github.com/user-attachments/assets/0cecd67a-5a67-436d-87c8-c06d43d4ba80" />

