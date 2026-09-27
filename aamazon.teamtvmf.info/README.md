# AAMAZON — Web Application Penetration Test

## Overview

| Category    | Details                                    |
|-------------|--------------------------------------------|
| Assessment  | Web Application Pentest                    |
| Environment | Authorized Training Platform               |
| Date        | September 2026                             |
| Methodology | Recon → Enumeration → Testing → Validation |
| Tools       | Burp Suite, Nmap, Browser DevTools, dig    |

## Findings

| Vulnerability                   | Severity | OWASP    |
|---------------------------------|----------|----------|
| Reflected & Stored XSS          | Critical | A03:2021 |
| Mass Assignment                 | Critical | A01:2021 |
| Unlimited Wallet Top-Up         | High     | A04:2021 |
| Broken Access Control           | Critical | A01:2021 |
| Unauthorized Price Modification | High     | A01:2021 |
| Stored XSS / Defacement         | Critical | A03:2021 |

## Key Technical Findings

- Identified reflected XSS in search functionality.
- Identified persistent XSS in product content.
- Demonstrated mass-assignment privilege escalation.
- Identified insufficient authorization checks on administrative APIs.
- Identified business-logic flaws in wallet functionality.
- Demonstrated unauthorized modification of product pricing.

## Attack Chain

→ Reconnaissance
→ API Discovery
→ Vulnerability Identification
→ Privilege Escalation
→ Administrative Access
→ Business Logic Abuse

## Full Report
Report pdf provided.

## Disclaimer
Testing was performed only against an authorized educational
training environment.
