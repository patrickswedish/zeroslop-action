# ZeroSlop™ Zero Code Retention & Data Privacy Policy
**Version 1.0 (2026) · Ribbsaeter Systems · Zurich · Amsterdam · Eindhoven**

At **Ribbsaeter Systems**, we believe intellectual property and software architecture are the most valuable assets of modern technology enterprises. We maintain an uncompromising, audited **Zero Code Retention Guarantee** across all ZeroSlop™ infrastructure.

---

### 1. The Zero Code Retention Guarantee
When you execute the ZeroSlop™ GitHub Action within your continuous integration pipelines:

1. **Ephemeral In-Memory Analysis Only**:
   * Pull request diffs transmitted from your CI runner to our API endpoints exist **exclusively in volatile RAM** for the duration of the invariant verification cycle (typically under 250 milliseconds).
   * Once the evaluation is complete and the signed JSON verdict is returned to your GitHub Action, the diff data is **immediately overwritten and purged from memory**.

2. **Zero Persistent Storage**:
   * Your source code, diffs, file trees, commit messages, and variable names are **NEVER saved to hard drives, SSDs, object storage (S3/GCS), or databases**.
   * Our cloud servers maintain zero cold cache of your codebase.

3. **Zero AI Model Training**:
   * **WE NEVER USE YOUR CODE TO TRAIN, FINE-TUNE, RE-TRAIN, OR VALIDATE ARTIFICIAL INTELLIGENCE MODELS.**
   * Your code is never sent to public LLM APIs (OpenAI, Anthropic, Google, etc.).
   * The ZeroSlop Invariant Engine evaluates code using deterministic formal compiler checks, abstract syntax tree (AST) traversal, and sovereign mathematical minimization matrices.

---

### 2. What Data We Process & Retain
To fulfill licensing obligations and provide billing services, we collect only minimal metadata:

| Data Category | Purpose | Retained? |
| :--- | :--- | :--- |
| **Customer Email & Billing Data** | Stripe payment processing & invoice delivery | Yes (Stripe PCI-compliant vault) |
| **API Key (`RST_LIVE_xxx`)** | Authentication & rate limit enforcement | Yes (Encrypted hash) |
| **Verification Counter** | Monthly PR verification volume tracking | Yes (Aggregate count only) |
| **Repository Name & Commit SHA** | Verification audit log (`vfy_xxx`) reference | Yes (Hash identifier only) |
| **Customer Source Code / Diffs** | Invariant & slop evaluation | **NO (Zero Retention — Purged immediately)** |

---

### 3. Encryption & In-Transit Security
* **TLS 1.3 Mandatory**: All communication between the `zeroslop-action` runner and the Ribbsaeter Systems verification cloud is strictly encrypted using TLS 1.3 with forward secrecy.
* **Mutual Authentication**: API requests must present a cryptographically verified `Authorization: Bearer <RST_LIVE_KEY>` token.
* **Diff Integrity Hashing**: Client runners compute an ephemeral SHA-256 digest of the diff before dispatch to guarantee payload integrity during transit.

---

### 4. Regulatory Compliance & European Standards
Ribbsaeter Systems is headquartered in Switzerland and operates across the Netherlands:
* **Swiss Federal Act on Data Protection (FADP)**: Fully compliant.
* **European General Data Protection Regulation (GDPR)**: Fully compliant. We process no personal data contained in repositories beyond necessary administrative licensing metadata.
* **European Union NIS2 & Cyber Resilience Act**: ZeroSlop architecture adheres to high-assurance supply chain security requirements.

---

### 5. On-Premise & Air-Gapped Deployments
For defense contractors, sovereign banks, and healthcare institutions with strict air-gap compliance requirements, Ribbsaeter Systems offers the **ZeroSlop Enterprise Core Self-Hosted Appliance**:
* Runs entirely within your VPC (AWS, GCP, Azure, or bare-metal Kubernetes).
* Zero external network calls.
* Full local verification with air-gapped cryptographic licensing.

---

### 6. Contact & Data Protection Officer
For data privacy inquiries, enterprise Data Processing Agreements (DPA), or CISO security questionnaires:
**Data Protection & Security Governance**  
Ribbsaeter Systems  
Email: [privacy@ribbsaetersystems.com](mailto:privacy@ribbsaetersystems.com)  
Website: [https://ribbsaetersystems.com/zeroslop](https://ribbsaetersystems.com/zeroslop)  
Zurich, Switzerland · Amsterdam · Eindhoven
