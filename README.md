# Hi, I'm Eduardo Masceno 👋
> *"Something like the Midas touch."*

IT Infrastructure Technician & Information Systems Student. Focused on **Detection Engineering**, **Incident Response (DFIR)**, **SIEM Telemetry**, and **Security Automation**. Bringing hands-on corporate IT support and infrastructure experience into building automated, high-fidelity defensive capabilities based on offensive research (Cloud-Native kill chains, AD attack vectors, malware behavior, and reverse engineering).

---

### 🛡️ Formations & Badges
![Cisco CCNA 1](https://img.shields.io/badge/Cisco_CCNA_1-005A9C?style=for-the-badge&logo=cisco&logoColor=white)
![Cisco CyberOps Course](https://img.shields.io/badge/Cisco_CyberOps_Course-005A9C?style=for-the-badge&logo=cisco&logoColor=white)
![IBSEC SOC Analyst](https://img.shields.io/badge/IBSEC_SOC_Analyst-000000?style=for-the-badge&logo=target&logoColor=white)
![Google Cybersecurity](https://img.shields.io/badge/Google_Cybersecurity-4285F4?style=for-the-badge&logo=google&logoColor=white)

---

### 🛠️ Tech Stack & Security Tooling
* **SIEM, Detection & Response:** Wazuh SIEM/XDR, IBM QRadar CE, Custom YARA Rule Engineering, Stream Log Correlation, Telemetry Normalization
* **DFIR & Malware Analysis:** Static Triage, Java/Binary Reverse Engineering (JADX, pefile), Mandiant CAPA & FLOSS, IoC Extraction, Any.Run, Wireshark
* **Systems, Cloud & Networks:** Linux (Ubuntu, Kali), Windows Server, Active Directory (AD), Kubernetes/Microservice Telemetry, TCP/IP Protocols
* **Scripting, Automation & AI:** Python (OOP, $O(1)$ Generators, Dataclasses), Bash, SQL, **Google Gemini API**, Agentic Workflows for CTI Triage

---

### 🐉 Project Chimera: Custom DFIR & Detection Arsenal
> *"Exorcising and consuming (mal)ware."*

An integrated suite of three modular Python frameworks engineered to cover the full threat detection lifecycle—from perimeter file triage to deep binary dissection and cloud-native log correlation:

* 🦎 **[salamander-framework](https://github.com/edmasceno/salamander-framework)** *(Perimeter Pre-Filter)*
  * Automated batch triage scanner featuring Magic Byte masquerading detection, $O(1)$ chunked hashing, ephemeral archive unpacking, and boolean-logic YARA scanning to filter out droppers and disguised executables at scale.

* 🐜 **[black-ant-framework](https://github.com/edmasceno/black-ant-framework)** *(Deep Static Dissection & CTI)*
  * Advanced malware analysis engine featuring deep IoC extraction, recursive installer unpacking (7-Zip), V8 Bytenode string recovery, automated Java XOR array brute-forcing (JADX), MITRE ATT&CK capability mapping (CAPA/FLOSS), and an **AI-driven CTI Engine (Google Gemini)** that generates SIEM-ready JSON SOC playbooks.

* 🐦‍⬛ **[crow-framework](https://github.com/edmasceno/crow-framework)** *(Cloud-Native Stream Correlation)*
  * Zero-dependency, $O(1)$ memory stream processing engine built for Kubernetes and microservice telemetry. Normalizes heterogeneous JSONL logs into chronological attack timelines to detect multi-stage TTPs including SSRF Redirect Bypasses, Segregation of Duties (SoD) fraud, Anti-Forensics evasion, and Unauthorized Token Bootstrapping.

---

### 🧪 SOC, SIEM & Active Directory Labs

* **[AD-Attack-Defense-QRadar-Lab](https://github.com/edmasceno/AD-Attack-Defense-QRadar-Lab)**
  * Active Directory threat detection inside IBM QRadar focusing on Credential Dumping (MITRE T1003) and Lateral Movement (T1550).

* **[Wazuh-SOC-Lab-Active-Response](https://github.com/edmasceno/Wazuh-SOC-Lab-Active-Response)**
  * Full SOC environment using Wazuh SIEM/XDR for real-time threat detection and automated Active Response against Brute Force attacks (MITRE T1110).

* **[qradar-siem-homelab](https://github.com/edmasceno/qradar-siem-homelab)**
  * Advanced deployment and troubleshooting of IBM QRadar CE, including legacy license resolution, system optimization, and service recovery via CLI and `psql`.

* **[wannacry-analysis-wazuh](https://github.com/edmasceno/wannacry-analysis-wazuh)**
  * Behavioral analysis of WannaCry ransomware in sandbox environments and custom detection rule engineering in Wazuh.

---

### 📩 Contact & Links
* **LinkedIn:** [Eduardo Masceno](https://www.linkedin.com/in/eduardo-masceno-047265321)
* **Email:** [mascenoeduardo@gmail.com](mailto:mascenoeduardo@gmail.com)
