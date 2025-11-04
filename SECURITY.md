# 🔒 Security Policy

## 📖 Overview

At **ScriptureFlow**, we are committed to maintaining a secure and trustworthy open-source project.  
While our platform focuses on making Scripture widely accessible, we take the integrity of our data, systems, and community contributions seriously.  

This document outlines how to responsibly report vulnerabilities and how we handle security issues.

---

## 🧭 Supported Versions

The following versions of ScriptureFlow are currently supported with security updates:

| Version | Supported |
|----------|------------|
| `main` (active branch) | ✅ Yes |
| Older snapshots (tagged commits) | ⚠️ Partial (best effort) |
| Archived forks or mirrors | ❌ No |

If you are using ScriptureFlow through a CDN (e.g., jsDelivr), make sure to pin to the latest stable commit for security and integrity.

---

## 🛡️ Reporting a Vulnerability

If you discover a security issue, data integrity problem, or potential abuse of the API:

1. **Do not open a public issue.**  
   Publicly posting vulnerabilities may put users and contributors at risk.

2. **Instead, please email:**  
   📧 **johnathan@listingsprogh.com**  
   with the subject line:  
   **“[Security Report] Vulnerability in ScriptureFlow”**

3. Include the following details (if applicable):
   - Description of the issue  
   - Steps to reproduce  
   - Affected endpoints or files  
   - Any proof-of-concept code or logs  
   - Suggested mitigation (if known)

You will receive a response within **96 hours**, and we aim to resolve confirmed issues within **14 days**, depending on complexity.

---

## 🔐 Data & Integrity Guidelines

Even though ScriptureFlow provides public-domain or licensed Scripture data, contributors should:
- Avoid adding files with embedded executables, scripts, or unverified external links.  
- Verify that all JSON and metadata files are free from malicious payloads.  
- Ensure all automation scripts (Node, Python, etc.) use HTTPS endpoints.  
- Do not commit sensitive credentials, tokens, or API keys.  

If any accidental exposure occurs, please alert the maintainers immediately.

---

## 📦 Dependency Security

We use **npm audit** and **GitHub Dependabot** to detect vulnerabilities in dependencies.  
If you find a package or dependency with a known CVE that hasn’t been addressed, open a GitHub Issue titled:  
**“[Security] Vulnerable Dependency Found”**

---

## 🧱 Verification & Integrity

All production data (Bible text, indexes, and JSON builds) are:
- Generated through verified build scripts.
- Checked for valid UTF-8 encoding and structural integrity.
- Distributed via trusted CDNs (e.g., jsDelivr or GitHub Pages).

Consumers of the API are encouraged to:
- Verify file integrity using commit hashes.
- Pin to specific release tags or commit IDs.

---

## 🤝 Responsible Disclosure Policy

We adhere to the principles of **responsible disclosure**:
- You may test vulnerabilities responsibly, provided it does not harm or disrupt the project or its users.  
- Do not publicly share exploits or vulnerability details until we have confirmed and resolved the issue.  
- Acknowledgment and thanks will be given to security researchers who report issues ethically.

---

## 🙏 Closing Note

ScriptureFlow is built on openness, transparency, and community trust.  
By following this policy, you help protect users, contributors, and the mission of keeping the Word accessible safely and securely.

> “The prudent see danger and take refuge.” — Proverbs 22:3  

---

**Maintained by:**  
The ScriptureFlow Project Team  
📧 [your-security-email@example.com]  
© 2025 ScriptureFlow – MIT Licensed
