# Findings

- **vsftpd 2.3.4 on port 21** was exploitable and gave **root shell access**.
- **R-Login on port 513** was misconfigured and allowed **root login without proper authentication**.
- **UnrealIRCd on port 6667** was vulnerable and led to **root-level compromise**.
- **Samba on ports 139/445** had a remote code execution issue and also resulted in **root shell access**.
- **Telnet on port 23** used **default credentials**, giving access as `msfadmin` with **sudo privileges**.
- The system had **multiple critical services exposed**, showing a **complete system compromise risk**.
- The overall risk level was **Critical**, with **5 out of 5 vulnerabilities exploited successfully**.
- Post-exploitation showed the attacker had **full control of the machine** and could enumerate processes and services.
