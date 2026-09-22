# 🔐 Footprinting & Reconnaissance | Networkwalks Week 2

## 📌 Project Overview

This repository documents my Week 2 Cybersecurity Internship practical work with **Networkwalks**, focusing on **Footprinting and Reconnaissance**.

The objective of this activity was to understand how security professionals collect publicly available information about an authorized target before further security testing

---

## 🎯 Objectives

- Understand the reconnaissance and footprinting phase of penetration testing
- Collect publicly available information from an authorized target
- Identify domain, DNS, web technology, HTTP, and security-control information
- Practice commonly used reconnaissance tools
- Document findings with screenshots and observations
- Follow responsible and authorized security-testing practices

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| WHOIS | Collect domain registration information |
| WhatWeb | Identify web technologies |
| Nslookup | Resolve domain and DNS/IP information |
| Curl | Inspect HTTP response headers |
| Wafw00f | Identify Web Application Firewall information |
| DNSRecon | Enumerate DNS-related records |
| Wappalyzer Extension | Detect website technologies through the browser |

---

## 🔎 Activities Performed

### 1. WHOIS
Collected publicly available domain registration information.

![CYBER](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING--FOOTPRINTING/blob/7c0fdf2219647355ea3a764914b566731d3329f5/whois%201.png)
![CYBER](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING--FOOTPRINTING/blob/7c0fdf2219647355ea3a764914b566731d3329f5/whois%202.png)
![CYBER](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING--FOOTPRINTING/blob/7c0fdf2219647355ea3a764914b566731d3329f5/whois%203.png)

2. WhatWeb
Identified technologies associated with the authorized website.

![WHATWEB](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING--FOOTPRINTING/blob/7c0fdf2219647355ea3a764914b566731d3329f5/whatweb.png)


### 3. Nslookup
Resolved the authorized domain and identified DNS/IP information.
![CYBER](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING--FOOTPRINTING/blob/7c0fdf2219647355ea3a764914b566731d3329f5/nslookup.png)


### 4. Curl
Inspected HTTP response headers.
![CYBER](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING--FOOTPRINTING/blob/7c0fdf2219647355ea3a764914b566731d3329f5/curl.png)

### 5. Wafw00f
Identified whether a Web Application Firewall could be detected.
![CYBER](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING--FOOTPRINTING/blob/7c0fdf2219647355ea3a764914b566731d3329f5/waff.png)


### 6. DNSRecon
![CYBER](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING--FOOTPRINTING/blob/7c0fdf2219647355ea3a764914b566731d3329f5/DNS.png)


### 7. Wappalyzer Extension
Used the browser extension to identify technologies detected on the website through browser-based technology analysis.

**Method:** Open the authorized website in the browser and review the Wappalyzer result.
![CYBER](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING--FOOTPRINTING/blob/7c0fdf2219647355ea3a764914b566731d3329f5/wap.png)
---

## 📊 Findings

| ID | Finding | Evidence | Security Relevance | Risk |
|---|---|---|---|---|
| F-01 | Domain Information | WHOIS | Supports public domain profiling | 🟢 Low |
| F-02 | Web Technology Information | WhatWeb / Wappalyzer | May assist further authorized review | 🟠 Medium |
| F-03 | DNS/IP Information | Nslookup | Helps identify network information | 🟢 Low |
| F-04 | HTTP Technical Information | Curl | May assist fingerprinting | 🟢 Low |
| F-05 | WAF Information | Wafw00f | Reveals defensive technology | 🟢 Low |
| F-06 | DNS Infrastructure Information | DNSRecon | Helps build an infrastructure profile | 🟠 Medium |

> **Note:** These are observations from reconnaissance activities, not confirmed vulnerabilities. Further authorized validation is required before treating any observation as a security vulnerability.

---

## 🛡️ Security Recommendations

- Review publicly exposed technology information
- Keep CMS, plugins, and web technologies updated
- Review HTTP response headers
- Review DNS records regularly
- Properly configure and monitor security controls
- Perform reconnaissance only against authorized systems
- Maintain clear documentation of findings and evidence

---

## ⚠️ Disclaimer

This project is intended strictly for **educational and authorized cybersecurity testing**.

All reconnaissance activities should be performed only against systems for which appropriate permission has been obtained, or systems owned by the tester. Unauthorized scanning, enumeration, or access may violate applicable laws and organizational policies.

---

## 📚 Learning Outcomes

Through this activity, I learned:

- How reconnaissance fits into penetration testing
- How to use multiple reconnaissance tools in Kali Linux
- How domain, DNS, web technology, and HTTP information can be collected
- How browser-based technology detection can complement command-line tools
- How to document technical findings and evidence
- The importance of authorization and responsible security testing

---

## 👨‍💻 Author

**Kanishka M.**
Cybersecurity Student 
Program: Cybersecurity Internship – Networkwalks

---

## 🔗 Project

**Week 2 – Footprinting & Reconnaissance**
Built as part of my hands-on cybersecurity learning journey with Networkwalks.


