🔐 Footprinting & Reconnaissance | Networkwalks Week 2






📌 Project Overview

This repository documents my Week 2 Cybersecurity Internship practical work with Networkwalks, focusing on Footprinting and Reconnaissance.

The objective of this activity was to understand how security professionals collect publicly available information about an authorized target before further security testing.

All activities were performed in an authorized educational environment.

🎯 Objectives

Understand the reconnaissance and footprinting phase of penetration testing.

Collect publicly available information from an authorized target.

Identify domain, DNS, web technology, HTTP and security-control information.

Practice commonly used reconnaissance tools.

Document findings with screenshots and observations.

Follow responsible and authorized security-testing practices.

🛠️ Tools Used

Tool

Purpose

WHOIS

Collect domain registration information

WhatWeb

Identify web technologies

Nslookup

Resolve domain and DNS/IP information

Curl

Inspect HTTP response headers

Wafw00f

Identify Web Application Firewall information

DNSRecon

Enumerate DNS-related records

Wappalyzer Extension

Detect website technologies through the browser

🔎 Activities Performed

1. WHOIS

WHOIS was used to collect publicly available domain registration information.

whois <authorized-domain>

2. WhatWeb

WhatWeb was used to identify technologies associated with the authorized website.

whatweb <authorized-domain>

3. Nslookup

Nslookup was used to resolve the authorized domain and identify DNS/IP information.

nslookup <authorized-domain>

4. Curl

Curl was used to inspect HTTP response headers.

curl -I https://<authorized-domain>

5. Wafw00f

Wafw00f was used to identify whether a Web Application Firewall could be detected.

wafw00f https://<authorized-domain>

6. DNSRecon

DNSRecon was used to collect DNS-related information.

dnsrecon -d <authorized-domain>

7. Wappalyzer Extension

The Wappalyzer browser extension was used to identify technologies detected by the website through browser-based technology analysis.

Method: Open the authorized website in the browser and review the Wappalyzer result.

📊 Findings

ID

Finding

Evidence

Security Relevance

Risk

F-01

Domain Information

WHOIS

Supports public domain profiling

Low

F-02

Web Technology Information

WhatWeb / Wappalyzer

May assist further authorized review

Medium

F-03

DNS/IP Information

Nslookup

Helps identify network information

Low

F-04

HTTP Technical Information

Curl

May assist fingerprinting

Low

F-05

WAF Information

Wafw00f

Reveals defensive technology

Low

F-06

DNS Infrastructure Information

DNSRecon

Helps build an infrastructure profile

Medium

Note: These are observations from reconnaissance activities, not confirmed vulnerabilities. Further authorized validation is required before treating any observation as a security vulnerability.

🛡️ Security Recommendations

Review publicly exposed technology information.

Keep CMS, plugins and web technologies updated.

Review HTTP response headers.

Review DNS records regularly.

Properly configure and monitor security controls.

Perform reconnaissance only against authorized systems.

Maintain clear documentation of findings and evidence.

⚠️ Disclaimer

This project is intended strictly for educational and authorized cybersecurity testing.

All reconnaissance activities should be performed only against systems for which appropriate permission has been obtained or systems owned by the tester.

Unauthorized scanning, enumeration or access may violate applicable laws and organizational policies.

📚 Learning Outcomes

Through this activity, I learned:

How reconnaissance fits into penetration testing.

How to use multiple reconnaissance tools in Kali Linux.

How domain, DNS, web technology and HTTP information can be collected.

How browser-based technology detection can complement command-line tools.

How to document technical findings and evidence.

The importance of authorization and responsible security testing.

👨‍💻 Author

Kanishka M.

Cybersecurity Student | Ethical Hacking & VAPT

Program: Cybersecurity Internship – Networkwalks

🔗 Project

Week 2 – Footprinting & Reconnaissance

Built as part of my hands-on cybersecurity learning journey with Networkwalks.  
