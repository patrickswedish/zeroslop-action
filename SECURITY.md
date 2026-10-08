# Security & Vulnerability Disclosure Policy
**Ribbsaeter Systems · Zurich · Amsterdam · Eindhoven**

Ribbsaeter Systems takes the security of developer ecosystems and continuous integration infrastructure with utmost seriousness. We welcome reports from security researchers and the global developer community.

---

### Supported Versions

We release patches and security updates for the following versions of ZeroSlop Action:

| Version | Supported |
| :--- | :--- |
| `v1.x` | :white_check_mark: |
| `< v1.0` | :x: |

---

### Reporting a Vulnerability

**Please DO NOT file public GitHub issues for security vulnerabilities.**

To report a vulnerability, please contact our security team directly:
* **Email**: [security@ribbsaetersystems.com](mailto:security@ribbsaetersystems.com)
* **Response SLA**: We acknowledge receipt of vulnerability reports within **24 to 48 hours**.
* **Remediation Target**: Critical issues are triaged and patched within **7 business days**.

Please provide:
1. Description of the vulnerability.
2. Steps to reproduce or proof-of-concept repository.
3. Potential impact on CI runners or secret isolation.

---

### Safe Harbor

Ribbsaeter Systems will not pursue legal action against security researchers who:
* Act in good faith and conduct non-destructive research.
* Do not attempt to access, exfiltrate, or compromise customer code or data.
* Provide us a reasonable opportunity to remediate before public disclosure.
* Comply with applicable local and international computer crime laws.

---

### Security Architecture Highlights
* **Zero Dependency Client**: The `zeroslop-action` runner relies exclusively on Node.js core modules (`https`, `crypto`, `child_process`, `fs`). No supply-chain bloat or vulnerable third-party npm packages.
* **Ephemeral Runner Integrity**: Diffs are evaluated in-memory and discarded immediately upon completion.
* **Encrypted Communication**: Strict TLS 1.3 encryption across all network pipes.
