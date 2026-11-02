# secbyte-devsecops-sast-dast-owasp-top-10-supply-chain-ctf-labs
A practical collection of cybersecurity CTF labs covering DevSecOps CI/CD pipeline automation (SAST code hunting, DAST scanning, dependency vulnerability triage, software integrity signing) and core OWASP Top 10 web application security vulnerabilities (SSRF, injection flaws, broken authentication, security misconfigurations, insecure design).
# DevSecOps Pipeline Security, SAST/DAST Analysis, Software Supply Chain & OWASP Top 10 Web CTF Labs

Welcome to the **DevSecOps Pipeline Security, SAST/DAST Analysis, Software Supply Chain & OWASP Top 10 Web CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on integrating security into continuous delivery pipelines, automated vulnerability scanning, third-party component risk management, and web application security testing—spanning **DevSecOps Architecture & Automated Security Testing (DevSecOps delivery fundamentals, SAST static code analysis, DAST dynamic web scanning, CI/CD pipeline trust under pressure)**, **Software Supply Chain & Component Security (Software integrity verification, dependency scanning, shadow supply chain components)**, and **OWASP Top 10 Web Application Vulnerabilities (SQL/Command injection, Server-Side Request Forgery, broken logins, security misconfigurations, insecure design flaws)**.

---

## Lab Collection Index

### 1. DevSecOps Architecture, SAST & DAST Automated Testing
* **DevSecOps Fundamentals: Secure Delivery Pipeline**  
  *Lab Link:* [https://learn.secbyte.org/ctf/devsecops-fundamentals-secure-delivery-pipeline](https://learn.secbyte.org/ctf/devsecops-fundamentals-secure-delivery-pipeline)  
  *Focus:* Architecture principles of secure continuous integration and delivery (CI/CD), embedding security verification gates into build stages, and establishing feedback loops for development teams.

* **SAST: Secure Code Hunt**  
  *Lab Link:* [https://learn.secbyte.org/ctf/sast-secure-code-hunt](https://learn.secbyte.org/ctf/sast-secure-code-hunt)  
  *Focus:* Performing Static Application Security Testing (SAST), writing custom Semgrep/SonarQube rules, auditing source code for latent security bugs, and reducing static analysis false positives.

* **DAST Detective: Finding Web App Weaknesses from the Outside**  
  *Lab Link:* [https://learn.secbyte.org/ctf/dast-detective-finding-web-app-weaknesses-from-the-outside](https://learn.secbyte.org/ctf/dast-detective-finding-web-app-weaknesses-from-the-outside)  
  *Focus:* Executing Dynamic Application Security Testing (DAST) using OWASP ZAP and Burp Suite, crawling active web endpoints, and automated black-box scanning.

* **Secure CI/CD Pipeline: Trust Under Pressure**  
  *Lab Link:* [https://learn.secbyte.org/ctf/secure-cicd-pipeline-trust-under-pressure](https://learn.secbyte.org/ctf/secure-cicd-pipeline-trust-under-pressure)  
  *Focus:* Hardening CI/CD runner execution contexts, protecting build environment variables and secrets, preventing unauthorized workflow tampering, and auditing build step permissions.

<Image src="image_agent_tag_18265792866237282603" alt="Software Supply Chain Security diagram showing Developer, Source, Build, and Package and Deploy stages" caption="Software Supply Chain & Build Pipeline Verification Architecture" />

---

### 2. Software Supply Chain & Component Security
* **Dependency Scanning: From Theory to Real-World Supply Chain**  
  *Lab Link:* [https://learn.secbyte.org/ctf/dependency-scanning-from-theory-to-real-world-supply-chain-t](https://learn.secbyte.org/ctf/dependency-scanning-from-theory-to-real-world-supply-chain-t)  
  *Focus:* Analyzing Software Bill of Materials (SBOM) manifests (`cyclonedx`/`spdx`), auditing third-party open-source libraries (`npm`, `pip`, `maven`), and remediating Known Exploited Vulnerabilities (KEVs).

* **Software Integrity Failures: Signed by Trust**  
  *Lab Link:* [https://learn.secbyte.org/ctf/software-integrity-failures-signed-by-trust](https://learn.secbyte.org/ctf/software-integrity-failures-signed-by-trust)  
  *Focus:* Investigating compromised code signing certificates, bypassing weak artifact verification routines (Cosign/Sigstore), and triaging malicious build artifact replacement.

* **Vulnerable Components: Shadow Supply Chain**  
  *Lab Link:* [https://learn.secbyte.org/ctf/vulnerable-components-shadow-supply-chain](https://learn.secbyte.org/ctf/vulnerable-components-shadow-supply-chain)  
  *Focus:* Identifying transitive and hidden dependency chains, triaging typosquatted package imports, and securing internal package registry proxies.

### 3. OWASP Top 10 Web Application Vulnerabilities
* **Injection Attacks Lab: From Input Flaws to Full Compromise**  
  *Lab Link:* [https://learn.secbyte.org/ctf/injection-attacks-lab-from-input-flaws-to-full-compromise](https://learn.secbyte.org/ctf/injection-attacks-lab-from-input-flaws-to-full-compromise)  
  *Focus:* Exploiting and remediating SQL Injection (SQLi), Command Injection, and LDAP Injection vulnerabilities; enforcing parameterized queries; and sanitizing input channels.

<Image src="image_agent_tag_18265792866237282360" alt="Diagram listing OWASP Top 10 Web Application Security Vulnerabilities" caption="OWASP Top 10 Web Application Vulnerability Categories" />

---

* **Server-Side Request Forgery: Internal Eyes**  
  *Lab Link:* [https://learn.secbyte.org/ctf/server-side-request-forgery-internal-eyes](https://learn.secbyte.org/ctf/server-side-request-forgery-internal-eyes)  
  *Focus:* Exploit Server-Side Request Forgery (SSRF) to query cloud instance metadata services (IMDSv1/IMDSv2), bypass internal URL validation filters, and pivot to internal microservices.

* **Broken Logins: Authentication Failures Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/broken-logins-authentication-failures-lab](https://learn.secbyte.org/ctf/broken-logins-authentication-failures-lab)  
  *Focus:* Triaging broken authentication flaws—including credential stuffing, password spraying, weak session token generation, insecure password reset flows, and missing rate limits.

* **Security Misconfiguration: Broken Defaults & Exposed Admin Paths**  
  *Lab Link:* [https://learn.secbyte.org/ctf/security-misconfiguration-broken-defaults-exposed-admin-path](https://learn.secbyte.org/ctf/security-misconfiguration-broken-defaults-exposed-admin-path)  
  *Focus:* Discovering unhardened default application installations, exposed administrative control panels, verbose stack traces, and unsecure HTTP security response headers.

* **Insecure-by-Design: Clinic Portal**  
  *Lab Link:* [https://learn.secbyte.org/ctf/insecure-by-design-clinic-portal](https://learn.secbyte.org/ctf/insecure-by-design-clinic-portal)  
  *Focus:* Threat modeling web application architecture flaws, identifying Insecure Direct Object References (IDOR), fixing missing function-level access control, and redesigning secure workflows.

---

## Learning Path

### Path A: DevSecOps Engineer & Automated Testing Specialist
1. **Pipeline & Static Analysis:** Start with [DevSecOps Fundamentals](https://learn.secbyte.org/ctf/devsecops-fundamentals-secure-delivery-pipeline), [SAST: Secure Code Hunt](https://learn.secbyte.org/ctf/sast-secure-code-hunt), and [Secure CI/CD Pipeline](https://learn.secbyte.org/ctf/secure-cicd-pipeline-trust-under-pressure).
2. **Dynamic Scanning:** Master black-box web testing via [DAST Detective](https://learn.secbyte.org/ctf/dast-detective-finding-web-app-weaknesses-from-the-outside).

### Path B: Software Supply Chain & Component Auditor
1. **Dependencies & SBOMs:** Triage package vulnerabilities in [Dependency Scanning](https://learn.secbyte.org/ctf/dependency-scanning-from-theory-to-real-world-supply-chain-t) and [Vulnerable Components](https://learn.secbyte.org/ctf/vulnerable-components-shadow-supply-chain).
2. **Integrity & Code Signing:** Validate code signatures in [Software Integrity Failures](https://learn.secbyte.org/ctf/software-integrity-failures-signed-by-trust).

### Path C: Web Application Security Penetration Tester
1. **Input & Server Exploitation:** Master high-severity flaws in [Injection Attacks Lab](https://learn.secbyte.org/ctf/injection-attacks-lab-from-input-flaws-to-full-compromise) and [Server-Side Request Forgery](https://learn.secbyte.org/ctf/server-side-request-forgery-internal-eyes).
2. **Authentication, Configuration & Design:** Audit web applications in [Broken Logins](https://learn.secbyte.org/ctf/broken-logins-authentication-failures-lab), [Security Misconfiguration](https://learn.secbyte.org/ctf/security-misconfiguration-broken-defaults-exposed-admin-path), and [Insecure-by-Design](https://learn.secbyte.org/ctf/insecure-by-design-clinic-portal).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding direct link to launch the exercise environment hosted on Learn SecByte.
3. Review scenario directives, source code repositories, CI/CD workflow YAMLs, SBOM files, or target web application endpoints.
4. Craft SQLi/SSRF payloads, audit source code with SAST tools, configure DAST scans in OWASP ZAP, generate SBOM component audits, or fix broken authentication logic to capture flags.

---

## Target Audience

* **DevSecOps Engineers & Build Pipeline Architects:** Embed SAST/DAST tools into GitHub Actions/GitLab CI, enforce SBOM dependency auditing, and secure pipeline runner environments.
* **Web Application Penetration Testers & Red Teamers:** Exploit OWASP Top 10 vulnerabilities (SQLi, SSRF, IDOR), bypass web application firewalls (WAF), and triage authentication flaws.
* **AppSec Engineers & Software Developers:** Conduct source code reviews, remediate vulnerable open-source dependencies, fix security misconfigurations, and adopt secure design practices.
* **Cybersecurity Students:** Acquire practical hands-on experience in modern application security, software supply chain defense, and web vulnerability analysis.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized scanning, web exploitation, or supply chain poisoning against external production systems is strictly prohibited.
