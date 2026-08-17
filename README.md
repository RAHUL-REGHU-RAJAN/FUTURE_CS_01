# OWASP Juice Shop — Security Assessment

![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-blue)
![Future Interns](https://img.shields.io/badge/Future%20Interns-Task%201-green)
![OWASP](https://img.shields.io/badge/Target-Juice%20Shop-orange)

## 📌 About

A passive security assessment of **OWASP Juice Shop** conducted as part of the Future Interns Cyber Security Internship.

The assessment focuses on identifying security weaknesses, reviewing application configurations, collecting supporting evidence, and suggesting appropriate remediation measures.

> Testing was performed in a controlled environment using non-intrusive techniques.

## 🎯 Objectives

* Discover accessible services and ports.
* Review HTTP security configurations.
* Examine security headers and browser-side data.
* Identify potential security misconfigurations.
* Assess the impact of observed issues.
* Assign appropriate risk levels.
* Document findings with evidence and recommendations.

## 🛠️ Tools

| Tool                | Purpose                                          |
| ------------------- | ------------------------------------------------ |
| **Nmap**            | Port and service discovery                       |
| **OWASP ZAP**       | Passive web security analysis                    |
| **Chrome DevTools** | Headers, cookies, storage and network inspection |

## 🔍 Method

```text
Reconnaissance
     ↓
Nmap Scan
     ↓
ZAP Passive Analysis
     ↓
Browser Inspection
     ↓
Evidence Review
     ↓
Risk Assessment
     ↓
Remediation
```

## 🌐 Target

**Application:** OWASP Juice Shop
**URL:** `http://localhost:3000`
**Host:** `localhost`
**IP:** `127.0.0.1`
**Port:** `3000`

OWASP Juice Shop is an intentionally vulnerable application used for security education and testing.

## ⚠️ Findings

The assessment reviews areas including:

* Network exposure
* HTTP security headers
* Information disclosure
* Cookie configuration
* Browser storage
* Application security configuration

Findings are categorized as **Low, Medium, or High** based on their potential security impact.

## 🛠️ Recommendations

The assessment provides remediation guidance for the identified issues, including security-header hardening, reducing unnecessary information exposure, reviewing cookie settings, and improving application configuration where applicable.

## 📸 Evidence & Report

Screenshots and supporting evidence are provided alongside the assessment documentation to demonstrate the observations and their associated recommendations.

## ⚠️ Scope

This was a **passive/read-only assessment**. No exploitation, brute-force attacks, denial-of-service testing, or destructive activity was performed.

## 📚 Key Learning Areas

* Web application security assessment
* Network reconnaissance
* HTTP security analysis
* Browser security inspection
* Risk classification
* Vulnerability reporting
* Security remediation

---

**RAHUL REGHU RAJAN, Future Interns - Cyber Security Internship**
**Task 01: Vulnerability Assessment Report**
