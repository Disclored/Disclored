<div align="center">

```
┌──(jose-abreu㉿recon)-[~]
└─$ whoami --verbose
```

</div>

```
[+] Target acquired: Jose Abreu
[+] Role:            Web Application Penetration Tester
[+] Experience:      2 years — Blackbox & Whitebox assessments
[+] Status:          Actively testing, actively learning
```

---

### `$ nmap -sV --top-ports skills jose-abreu`

```
PORT      STATE   SERVICE              VERSION
7/tcp     open    sql-injection        Union-based, Error-based, Blind, Auth Bypass
80/tcp    open    xss                  Stored, Reflected
801/tcp   open    access-control       IDOR, Privilege Escalation, JWT Abuse
1337/tcp  open    rce                  Webshell Deployment, File Upload Bypass
443/tcp   open    misconfiguration     TLS, CORS, Verbose Errors, Debug Mode
9999/tcp  open    recon                Path Traversal, Open Redirect, DoS
```

---

### `$ cat /var/log/methodology.log`

```
[OK] OWASP Web Security Testing Guide (WSTG) alignment
[OK] CVSS 3.1 scoring on every confirmed finding
[OK] Blackbox -> Whitebox escalation when access allows
[OK] Full reproducibility: request/response evidence, not just claims
[OK] Root-cause analysis over surface-level symptom reporting
```

---

### `$ ls -la ~/projects`

```
drwxr-xr-x   Security-Vulnerability-Catalog/     # documented real-world findings, CVSS-scored
drwxr-xr-x   Cybersecurity-Pentest-Web/           # methodology, wordlists, testing notes
```

**[Security-Vulnerability-Catalog](https://github.com/Disclored/Security-Vulnerability-Catalog)**
Anonymized, reproducible web app vulnerability findings — SQL Injection, XSS, Broken Access Control, RCE, and more — each documented with exploitation steps, HTTP evidence, CVSS 3.1 scoring, and remediation guidance.

---

<div align="center">

*All testing documented in this profile was performed in authorized environments with explicit permission.*

</div>
