# MdcCIEMDashboard
> Microsoft Defender for Cloud - CIEM Dashboard

This repository provides CIEM Dashboard of Microsoft Defender for Cloud.<BR>
Microsoft Defender for Cloud provides two security recommendations about CIEM (Cloud Infrastructure Entitlement Management).

| Recommendations  | Severity | Detail |
| ---- | ---- | ---- |
| Azure overprovisioned identities should have only the necessary permissions | Medium | Overprovisioned identities in Azure are those that have been granted more permissions than they use, which can lead to potential misuse, either accidentally or maliciously.|
| Permissions of inactive identities in your Azure subscription should be revoked  | Medium | Microsoft Defender for Cloud discovered an identity that has not performed any action on any resource within your Azure subscription in the past 45 days. It is recommended to revoke permissions of inactive identities, in order to reduce the attack surface of your cloud environment. |

# Dashboard
## Overprovisioned ID Information
![image](https://github.com/user-attachments/assets/a04ee69d-3c01-4eaa-bcbd-920ceb948f74)<BR>
![image](https://github.com/user-attachments/assets/15f784df-aebf-447e-8d84-6446a40047ee)


## Permissions of inactive identities
![image](https://github.com/user-attachments/assets/a78d005f-8700-4131-9be7-287bd3173958)

# Install
two files are posted. You can install Wrokbooks of Microsoft Defender for Cloud via Gallary Template or ARM Template.

- Defender CSPM - [CIEM Dasboard.workbook](https://raw.githubusercontent.com/hisashin0728/MdcCIEMDashboard/refs/heads/main/Defender%20CSPM%20-%20CIEM%20Dasboard.workbook)
- Defender CSPM - [CIEM Dasboard.json](https://raw.githubusercontent.com/hisashin0728/MdcCIEMDashboard/refs/heads/main/Defender%20CSPM%20-%20CIEM%20Dasboard.json)
