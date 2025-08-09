---

**1. What is vulnerability scanning?**
Vulnerability scanning is the process of using automated tools to identify known security weaknesses in systems, networks, or applications. It helps detect outdated software, misconfigurations, and exploitable services without actively exploiting them.

---

**2. Difference between vulnerability scanning and penetration testing?**

* **Vulnerability Scanning**: Automated, broad check for known security issues. Focuses on finding vulnerabilities, not exploiting them.
* **Penetration Testing**: Manual or semi-automated process where security professionals actively exploit vulnerabilities to assess the real risk and impact.

---

**3. What are some common vulnerabilities in personal computers?**

* Outdated operating system or software
* Weak or reused passwords
* Unpatched security flaws in applications
* Enabled insecure protocols (e.g., SMBv1, Telnet)
* Weak encryption or open ports
* Malware infections

---

**4. How do scanners detect vulnerabilities?**
Scanners compare system details (OS, services, software versions) against a database of known vulnerabilities (CVE database). They use methods like banner grabbing, configuration checks, and network probing to identify security weaknesses.

---

**5. What is CVSS?**
**Common Vulnerability Scoring System (CVSS)** is a standardized method to rate the severity of vulnerabilities on a scale from 0 to 10.

* 0–3.9: Low
* 4.0–6.9: Medium
* 7.0–8.9: High
* 9.0–10.0: Critical

---

**6. How often should vulnerability scans be performed?**
At least **monthly** or **after major system changes**. Critical systems may require **weekly or even daily scans**. Regular scanning ensures timely detection of newly discovered vulnerabilities.

---

**7. What is a false positive in vulnerability scanning?**
A **false positive** occurs when the scanner reports a vulnerability that does not actually exist. This can happen due to outdated vulnerability databases, misconfigurations, or incorrect detection logic.

---

**8. How do you prioritize vulnerabilities?**

* **Severity score** (CVSS rating)
* **Asset importance** (criticality of affected system)
* **Exploit availability** (whether a working exploit exists)
* **Business impact** (data sensitivity, service downtime risk)
  Critical vulnerabilities on high-value systems should be fixed first.

---
