# Hi, I'm Omar Alghamdi 👋

**Cybersecurity Specialist | SOC Analyst | Incident Response & Threat Hunting**

A cybersecurity professional based in Riyadh with hands-on experience in government Security Operations Center (SOC) environments. I specialize in SIEM alert analysis, threat hunting, and turning attack simulations into practical detection logic. Every lab here follows the same approach: **simulate the attack, hunt it in the logs, then write the detection.**

### 🛠️ Skills & Expertise

- **Security Operations (SOC) & SIEM:** Log monitoring, alert triage, and writing custom AQL queries and correlation rules in IBM QRadar.
- **Threat Hunting & Incident Response:** Hunting through endpoint telemetry (Sysmon, Windows Event Logs) and following structured incident response playbooks.
- **Network Security & Defense:** Firewall log auditing, traffic analysis, and detecting brute-force attempts and lateral movement.
- **Detection Engineering:** Mapping attacks to MITRE ATT&CK and translating findings into SIEM detection rules.

### 🎓 Certifications

[![Security+][badge-secplus]][verify-secplus] [![Network+][badge-netplus]][verify-netplus] [![CEH][badge-ceh]][verify-ceh] [![eJPT][badge-ejpt]][verify-ejpt] [![OCI][badge-oci]][verify-oci]

---

### 🔬 SOC & Threat Hunting Portfolio

| Lab & Documentation | Attack / Focus | MITRE ATT&CK | Detection |
|---|---|---|---|
| [SMB Brute-Force Attack & Detection](https://github.com/omar-alghamdi-tech/smb-threat-hunting-lab) | SMB brute force with NetExec | T1110.001 | Windows Event Logs (4625 → 4624) + QRadar AQL |
| [LSASS Credential Dumping](https://github.com/omar-alghamdi-tech/lsass-credential-dumping-lab) | LSASS memory dump via Task Manager | T1003.001 | Sysmon Event ID 11 + KQL |
| [QRadar AQL Cheat Sheet](https://github.com/omar-alghamdi-tech/qradar-aql-firewall-cheatsheet) | Firewall log analysis | — | 9 ready-to-use AQL hunting queries |

### 🚧 Currently Working On

- Adding Sigma and QRadar AQL detection rules to the LSASS lab
- New labs covering more credential access and lateral movement techniques

---

### 📫 Connect With Me

- **LinkedIn:** [Omar Alghamdi](https://www.linkedin.com/in/omar-al-ghamdi-)
- **X (Twitter):** [@Omar_Cyber7](https://x.com/Omar_Cyber7)

<!-- ============================================================
     Certification links — replace each URL after "verify-" with
     your own verification link (Credly, CertMetrics, etc.)
     ============================================================ -->

[badge-secplus]: https://img.shields.io/badge/CompTIA-Security%2B-FF0000?style=for-the-badge&logo=comptia&logoColor=white
[badge-netplus]: https://img.shields.io/badge/CompTIA-Network%2B-0055A5?style=for-the-badge&logo=comptia&logoColor=white
[badge-ceh]: https://img.shields.io/badge/EC--Council-CEH-black?style=for-the-badge&logo=eccouncil&logoColor=white
[badge-ejpt]: https://img.shields.io/badge/INE-eJPT-000000?style=for-the-badge&logo=linux&logoColor=white
[badge-oci]: https://img.shields.io/badge/Oracle-OCI_Foundations-C74634?style=for-the-badge&logo=oracle&logoColor=white

[verify-secplus]: https://www.credly.com/
[verify-netplus]: https://www.credly.com/
[verify-ceh]: https://aspen.eccouncil.org/VerifyCert
[verify-ejpt]: https://certs.ine.com/
[verify-oci]: https://catalog-education.oracle.com/pls/certview/sharebadge
