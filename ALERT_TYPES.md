# Alert Types Overview

This document provides details on the different alert types detected in the scan report. For every alert, references are provided to further information on the vulnerability type.

## Cross Site Scripting (Reflected)
- **Risk:** High
- **CWE ID:** 79  
- **WASC ID:** 8  
- **References:**  
  - [OWASP XSS](https://owasp.org/www-community/attacks/xss/)
  - [CWE-79](https://cwe.mitre.org/data/definitions/79.html)

## Path Traversal
- **Risk:** High
- **CWE ID:** 22  
- **WASC ID:** 33  
- **References:**  
  - [OWASP Path Traversal](https://owasp.org/www-community/attacks/Path_Traversal)
  - [CWE-22](https://cwe.mitre.org/data/definitions/22.html)

## SQL Injection - MySQL
- **Risk:** High
- **CWE ID:** 89  
- **WASC ID:** 19  
- **References:**  
  - [OWASP SQL Injection Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)

## Absence of Anti-CSRF Tokens
- **Risk:** Medium
- **CWE ID:** 352  
- **WASC ID:** 9  
- **References:**  
  - [OWASP CSRF Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.html)
  - [CWE-352](https://cwe.mitre.org/data/definitions/352.html)

## Content Security Policy (CSP) Header Not Set
- **Risk:** Medium
- **CWE ID:** 693  
- **WASC ID:** 15  
- **References:**  
  - [MDN Web Docs on CSP](https://developer.mozilla.org/en-US/docs/Web/Security/CSP/Introducing_Content_Security_Policy)  
  - [OWASP CSP Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html)

## Directory Browsing
- **Risk:** Medium
- **CWE ID:** 548  
- **WASC ID:** 16  
- **References:**  
  - [CWE-548](https://cwe.mitre.org/data/definitions/548.html)

## Missing Anti-clickjacking Header
- **Risk:** Medium
- **CWE ID:** 1021  
- **WASC ID:** 15  
- **References:**  
  - [MDN on X-Frame-Options](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

## Server Leaks Information via "X-Powered-By" HTTP Response Header Field(s)
- **Risk:** Low
- **CWE ID:** 497  
- **WASC ID:** 13  
- **References:**  
  - [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/01-Information_Gathering/08-Fingerprint_Web_Application_Framework)

## Server Leaks Version Information via "Server" HTTP Response Header Field
- **Risk:** Low
- **CWE ID:** 497  
- **WASC ID:** 13  
- **References:**  
  - [Apache ServerTokens](https://httpd.apache.org/docs/current/mod/core.html#servertokens)
  - [Microsoft Guidance](https://learn.microsoft.com/en-us/previous-versions/msp-n-p/ff648552(v=pandp.10))

## X-Content-Type-Options Header Missing
- **Risk:** Low
- **CWE ID:** 693  
- **WASC ID:** 15  
- **References:**  
  - [OWASP Security Headers](https://owasp.org/www-community/Security_Headers)

## Authentication Request Identified
- **Risk:** Informational
- **References:**  
  - [ZAP Authentication Helper](https://www.zaproxy.org/docs/desktop/addons/authentication-helper/auth-req-id/)

## Charset Mismatch (Header Versus Meta Content-Type Charset)
- **Risk:** Informational
- **CWE ID:** 436  
- **WASC ID:** 15  
- **References:**  
  - [BrowserSec Wiki on Charset Handling](https://code.google.com/p/browsersec/wiki/Part2#Character_set_handling_and_detection)

## Modern Web Application
- **Risk:** Informational

## User Controllable HTML Element Attribute (Potential XSS)
- **Risk:** Informational
- **CWE ID:** 20  
- **WASC ID:** 20  
- **References:**  
  - [OWASP Input Validation Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Input_Validation_Cheat_Sheet.html)