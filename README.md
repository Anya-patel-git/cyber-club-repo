# cyber-club-repo

## About Me

My name is Anya.

## Why I Want to Join WhiteHats

I want to join WhiteHats to deepen my understanding of cybersecurity, learn practical skills from other members, and use that knowledge responsibly to help make systems and communities safer.

## Cybersecurity Incident I Recently Read About

### Sinobi Ransomware Group Targets Indian IT Services Company (January 2026)

In January 2026, the Sinobi ransomware group claimed an attack on an India-based IT services company, gaining access to Hyper-V servers, virtual machines, and customer backups. The group alleged that it stole 150 GB or more of data, including contracts, financial information, and customer data. Sinobi emerged in mid-2025 and had claimed approximately 50 victims by January 2026. The incident illustrates the supply-chain risks facing managed service providers and their customers.

| Detail | Information |
| --- | --- |
| Date | January 2026 |
| Sector | IT services, managed services, and IT solutions |
| Location | India |
| Attack type | Ransomware; Hyper-V server and virtual machine compromise; access to customer backups |
| Alleged exfiltration | 150 GB or more, including contracts, financial information, and customer data |
| Threat actor | Sinobi, which emerged in mid-2025; reported tactics include VPN compromise, DLL sideloading, and staged extortion |
| CIA impact | Confidentiality: alleged exfiltration of 150 GB or more. Availability: virtual machines and backups were reportedly accessed. Integrity: customer data may have been at risk of manipulation. |
| Source | Breached.company, January 2026 (as cited in the report I read) |

#### Prevention Controls

- Isolate Hyper-V and virtualization management networks and protect administrative access with multifactor authentication (MFA). A compromised hypervisor can expose multiple hosted virtual machines.
- Store customer backups using immutable storage and credentials separate from production systems.
- Require MFA for VPN access and restrict it to the minimum necessary network segments.
- Managed service providers should treat customer backup data as a high-priority asset and limit access to it.
