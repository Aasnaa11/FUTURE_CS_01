 # FUTURE_CS_01 — Vulnerability Assessment Report

**Intern:** Asna Fatima  
**CIN ID:** FIT/MAR26/CS6725  
**Program:** Future Interns — Cybersecurity Internship  
**Track:** Cyber Security (CS)  
**Task:** Task 1 — Vulnerability Assessment Report  

## Target
http://testphp.vulnweb.com — Intentionally vulnerable test site by Acunetix. Authorised for security testing.

## Tools Used
- Nmap 7.98 (Zenmap GUI) — Network port scanner
- OWASP ZAP 2.17.0 — Web application vulnerability scanner
- Browser DevTools (Edge) — HTTP header analysis

## Key Findings
- 14 vulnerability types identified
- 3 HIGH: SQL Injection (MySQL), SQL Injection (Time-Based Blind), XSS Reflected
- 3 MEDIUM: Missing CSP, Missing Anti-Clickjacking Header, Absence of Anti-CSRF Tokens
- 4 LOW: Server/PHP version disclosure, X-Content-Type-Options missing, In-Page Banner leak
- 4 INFORMATIONAL: Auth request identified, Charset mismatch, Modern web app, User-controllable HTML

## Files in This Repository
- Vulnerability_Assessment_Report.pdf — Full 13-page professional report
- CE_A_ZAP_Alerts.png — OWASP ZAP alerts panel
- CE_B_Nmap_Output.png — Nmap full scan output
- CE_C_Nmap_Ports.png — Zenmap Ports/Hosts tab
- CE_D_DevTools_Headers.png — Browser DevTools response headers
- CE_E_DevTools_Network.png — Browser DevTools network requests
- CE_F_Cookies_Panel.png — Application cookies panel

## Assessment Date
March 11, 2026
