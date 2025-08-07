# 🔐 Web Application Security Assessment – Task 1

Scan Date:August 7, 2025  
Tool Used:[OWASP ZAP](https://www.zaproxy.org/)  
Target: http://localhost

🧭 Objective
Perform a passive security scan on a modern web application to identify common vulnerabilities and generate a professional report.

📌 Process
- Deployed OWASP ZAP on a test environment
- Enabled spider and passive scanning
- Collected alerts and evidence
- Documented each issue with severity, risk, and recommendations
- Generated Markdown and PDF reports for documentation and sharing

🛡️ Summary of Findings

| Vulnerability | Risk |
|---------------|------|
| CSP: Unsafe inline script/style | Medium |
| CSP Header Missing / Wildcards | Medium |
| X-Frame-Options via META | Medium |
| Missing Anti-clickjacking Header | Medium |
| Server Info Disclosure via HTTP Header | Low |
| Unix Timestamp Disclosure | Low |
| X-Content-Type-Options Missing | Low |
| Suspicious Comments | Low |

📄 Deliverables

- [`Task_1_WebApp_Security_Report.md`](./Task_1_WebApp_Security_Report.md)
- [`Task_1_WebApp_Security_Report.pdf`](./Task_1_WebApp_Security_Report.pdf)
- 📸 Screenshot Evidence from OWASP ZAP

 🧠 What I Learned

- Importance of response headers in securing modern web apps
- How CSP misconfigurations lead to XSS vulnerabilities
- How to document findings clearly and professionally
- Using OWASP ZAP as a practical DAST tool for pentesting

