# Lab 1: Installing Windows Server 2022 with Active Directory and DNS

This lab demonstrates the process of deploying Windows Server 2022 as a domain controller with DNS support using Oracle VirtualBox.

## 🧾 Overview

- Installed Windows Server 2022 Standard (Desktop Experience) on a VirtualBox VM
- Installed and configured Active Directory Domain Services (AD DS)
- Installed and configured DNS Server
- Promoted the server to a domain controller with the domain `test.local`

## 💻 Tools Used

- Oracle VirtualBox
- Windows Server 2022 Evaluation ISO
- GUI-based installation with Server Manager

## 📸 Screenshots

| Step | Description                                  | Screenshot |
|------|----------------------------------------------|------------|
| 01   | VM creation and ISO selection                | ![](screenshots/01-vm-creation-with-desktop-experience.png) |
| 02   | Unattended setup: username and hostname      | ![](screenshots/02-unattended-setup-username-and-hostname.png) |
| 03   | VM hardware configuration                    | ![](screenshots/03-vm-hardware-configuration.png) |
| 04   | Creating virtual hard disk                   | ![](screenshots/04-create-virtual-hard-disk.png) |
| 05   | VM setup summary                             | ![](screenshots/05-vm-creation-summary.png) |
| 06   | Windows Server installation progress         | ![](screenshots/06-windows-server-installation-progress.png) |
| 07   | Server Manager after installation            | ![](screenshots/07-server-manager-dashboard-loaded.png) |
| 08   | Selecting AD DS and DNS roles                | ![](screenshots/08-select-active-directory-and-dns-roles.png) |
| 09   | Promote server to domain controller          | ![](screenshots/09-promote-server-to-domain-controller.png) |
| 10   | Create new domain `test.local`               | ![](screenshots/10-create-new-domain-test-local.png) |
| 11   | Set DSRM password                            | ![](screenshots/11-set-dsrm-password.png) |
| 12   | DNS delegation warning                       | ![](screenshots/12-dns-delegation-warning-default-settings.png) |
| 13   | NetBIOS domain name confirmation             | ![](screenshots/13-netbios-domain-name-test.png) |
| 14   | Prerequisites check with warnings            | ![](screenshots/14-prerequisites-check-with-warnings.png) |
| 15   | Review options summary                       | ![](screenshots/14-review-options-summary.png) |
| 16   | AD DS and DNS installed successfully         | ![](screenshots/15-ad-ds-and-dns-installed-successfully.png) |

## 🏁 Result

The VM is now acting as a domain controller and DNS server for the `test.local` domain.
