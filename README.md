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
![image](https://github.com/user-attachments/assets/daeaaec9-835e-4c48-a6dc-cbb8d60378b9)<BR>


## Permissions of inactive identities
![image](https://github.com/user-attachments/assets/a78d005f-8700-4131-9be7-287bd3173958)
