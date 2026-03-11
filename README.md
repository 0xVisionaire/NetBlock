# NetBlock

A per-app internet firewall for Android using KernelSU/Magisk. Block internet access for specific apps while keeping others connected.

## Features

- **Per-App Blocking** : Toggle internet access per app via WebUI
- **System & User Apps** : Block both user-installed and system apps
- **IPv4/IPv6 Support** : Blocks all traffic on both protocols
- **Backup/Restore** : Export/import blocklists config (path: `/sdcard/Downloads`)
- **Auto-Verification** : Service monitors and restores rules if cleared

## Installation

1. Flash module in KernelSU/Magisk/Apatch Manager
2. Reboot device
3. Launch NetBlock from WebUI
4. Toggle apps to block/unblock internet access

## Usage

| Action | Description |
|--------|-------------|
| Toggle Switch | Block/unblock app internet |
| Refresh | Reload app list |
| User/System | Switch between user and system apps |
| Verify | Check if iptables rules are active |
| Clear All | Remove all blocks instantly |
| Backup | Export/import blocklist as JSON |

## Note
- **Magisk Users**: Install [KSU WebUI](https://github.com/5ec1cff/KsuWebUIStandalone/releases) and grant root permission to use WebUI interface

## Preview
<table align="center">
  <tr>
    <td><img src="https://github.com/MeowDump/NetBlock/blob/main/assets/1.png" alt="1" style="max-width: 100%; height: auto;" /></td>
  </tr>
</table>
