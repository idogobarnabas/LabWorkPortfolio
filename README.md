# ZAP Scan Report for testphp.vulnweb.com

This repository documents the results of a security scan performed using ZAP by idogobarnabas. The scan focused on the site [http://testphp.vulnweb.com](http://testphp.vulnweb.com) and covers vulnerabilities across different risk levels—from High and Medium risks to Informational alerts.

## Overview

- **ZAP Version**: 2.16.1
- **Scan Date**: Tue 20 May 2025, at 00:49:46 UTC
- **Site Tested**: [http://testphp.vulnweb.com](http://testphp.vulnweb.com)

The scan report details several kinds of vulnerabilities such as Cross Site Scripting (XSS), SQL Injection, missing security headers (e.g., Content Security Policy, X-Content-Type-Options), and others. This repository provides:
- A full **scan report** (see [ZAP_Scan_Report.md](ZAP_Scan_Report.md))
- Details on each **alert type** (see [ALERT_TYPES.md](ALERT_TYPES.md))
- **Security references** and remediation guidelines ([SECURITY_REFERENCES.md](SECURITY_REFERENCES.md))

This documentation may serve as a reference for security testing, risk assessment, and for developing remediation strategies in similar web applications.