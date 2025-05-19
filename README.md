# CVE-2025-31200 – iOS AudioConverterService Zero-Click RCE

Public disclosure of CVE-2025-31200 – a zero-click remote code execution (RCE) vulnerability in Apple's iOS 18.X, specifically within the `AudioConverterService` component. The vulnerability is triggered by a malicious audio file delivered via iMessage or SMS, requiring no user interaction.

---

##  Disclosure & Patch Timeline

- **Initial Report Date:** January 21, 2025  
- **Reported To:** US-CERT (Tracking ID: VRF#25-01-MPVDT)  
- **Patched By Apple:** Silently resolved in **iOS 18.4.1**, released **April 16, 2025**  
- **CVE Assignment:** Identifier **CVE-2025-31200** is used publicly due to lack of MITRE response  
- **Acknowledgment:** No public credit or acknowledgment provided by Apple or MITRE as of May 18, 2025  

Due to the severity of the vulnerability, prolonged silence from relevant stakeholders, and lack of credit or transparency post-patch, this repository is being published to inform the security community and support defensive mitigation.

---

##  Affected Systems

- **Product:** iPhone 15 Pro Max (others likely affected)  
- **iOS Versions:** iOS 18.2.1, iOS 18.3 Beta  
- **Patched Version:** iOS 18.4.1 (April 16, 2025)  
- **Vulnerable Component:** `AudioConverterService` via iMessage / SMS processing

---

##  Contents

- `Remote-Audio-Exploit-iOS-15ProMax-iOS18x.md` – Full technical write-up including:  
  - Attack chain  
  - Simulated proof-of-concept (PoC)  
  - Log timeline and decrypted token leakage  
  - Privilege escalation and AWDL DoS impact

No weaponized exploit code or malicious payloads are provided. This repository is for documentation and defense only.

---

## 🛡️ Disclaimer

This report is released in the interest of public safety, transparency, and to support defenders and researchers. All information is based on independent research. No offensive code is included. The author remains open to coordination with trusted parties for validation and response.


