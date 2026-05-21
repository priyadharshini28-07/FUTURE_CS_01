# FUTURE_CS_01

## Passive Vulnerability Assessment Report

**Target Website:** demo.testfire.net (Altoro Mutual Sandbox)  
**Assessment Type:** Passive (Read-Only)  
**Tools Used:** Nmap, OWASP ZAP (Passive), Browser DevTools, Canva  

---

### Scope
- Passive scanning only  
- Header validation  
- Port analysis  
- Cookie inspection  

---

### Findings
- **High:** Insecure Session Cookies (Missing SameSite)  
- **Medium:** Missing Core Security Headers, Insecure HTTP Connection  
- **Low:** Information Disclosure via Public Directory Listings  

---

### Deliverables
- 📄 [Vulnerability Assessment Report PDF](./Vunerability%20report.pdf)  
- 📂 Evidence screenshots in the [`Evidence/`](./Evidence) folder:  
  - [Nmap Scan Results](./Evidence/nmap_scan.png)  
  - [Cookies Inspection](./Evidence/cookies_devtools.png)  
  - [Headers Inspection](./Evidence/headers_devtools.png)  
  - [Insecure Connection Banner](./Evidence/insecure_banner.png)  
  - [OWASP ZAP Alerts](./Evidence/zap_alerts.png)  

---

### Prepared By
**Priyadharshini S** – Future Interns Cyber Security Task 1 (2026)
