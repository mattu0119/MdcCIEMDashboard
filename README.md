# MdcCIEMDashboard
> Microsoft Defender for Cloud - CIEM Dashboard

This repository provides CIEM Dashboard of Microsoft Defender for Cloud.<BR>
Microsoft Defender for Cloud provides two security recommendations about CIEM (Cloud Infrastructure Entitlement Management).

| Recommendations  | Severity | Detail |
| ---- | ---- | ---- |
| Azure overprovisioned identities should have only the necessary permissions | Medium | Overprovisioned identities in Azure are those that have been granted more permissions than they use, which can lead to potential misuse, either accidentally or maliciously.|
| Permissions of inactive identities in your Azure subscription should be revoked  | Medium | Microsoft Defender for Cloud discovered an identity that has not performed any action on any resource within your Azure subscription in the past 45 days. It is recommended to revoke permissions of inactive identities, in order to reduce the attack surface of your cloud environment. |

# Dashboard
> Workbook visual images

## PCI Summary
![image](https://github.com/user-attachments/assets/5ae32616-b1b7-4fd0-a051-b11080388704)

## Overprovisioned ID Information
![image](https://github.com/user-attachments/assets/b8e9722e-60f5-4cf6-a7fd-2eeb98b75723)<BR>
![image](https://github.com/user-attachments/assets/b58a16dd-6e19-4c98-85d4-d65d3d642903)

## Permissions of inactive identities
![image](https://github.com/user-attachments/assets/fcad65bc-b96c-41f3-884d-ab5334916518)

# Install
> How to install MDC CIEM dashboard on your environment

Two files are posted. You can install Wrokbooks of Microsoft Defender for Cloud via Gallary Template or ARM Template.

- Defender CSPM - [CIEM Dasboard.workbook](https://raw.githubusercontent.com/hisashin0728/MdcCIEMDashboard/refs/heads/main/Defender%20CSPM%20-%20CIEM%20Dasboard.workbook)
- Defender CSPM - [CIEM Dasboard.json](https://raw.githubusercontent.com/hisashin0728/MdcCIEMDashboard/refs/heads/main/Defender%20CSPM%20-%20CIEM%20Dasboard.json)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://raw.githubusercontent.com/mattu0119/MdcCIEMDashboard/refs/heads/main/Defender%20for%20Cloud%20CIEM%20%E3%83%80%E3%83%83%E3%82%B7%E3%83%A5%E3%83%9C%E3%83%BC%E3%83%89.json)
