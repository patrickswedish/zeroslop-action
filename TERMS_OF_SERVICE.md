# ZeroSlop™ Commercial Terms of Service
**Version 1.0 (2026) · Ribbsaeter Systems · Zurich · Amsterdam · Eindhoven**

PLEASE CAREFULLY READ THESE COMMERCIAL TERMS OF SERVICE ("TERMS") BEFORE SUBSCRIBING TO, DOWNLOADING, ACCESSING, OR UTILIZING THE ZEROSLOP™ GITHUB ACTION, RUNNER, API, OR ASSOCIATED SERVICES (COLLECTIVELY, THE "SERVICE").

BY SUBSCRIBING TO THE SERVICE, INSTALLING THE GITHUB ACTION, OR PROVISIONING AN API KEY, YOU ("CUSTOMER" OR "YOU") AGREE TO BE BOUND BY THESE TERMS. IF YOU ARE ENTERING INTO THESE TERMS ON BEHALF OF AN ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE LEGAL AUTHORITY TO BIND SUCH ENTITY.

---

### 1. The Service & Proprietary Architecture
ZeroSlop™ is a proprietary automated software verification service developed and operated by **Patrick Ribbsaeter / Ribbsaeter Systems** ("Licensor", "Company", "We", or "Us"). The Service conducts pre-flight invariant evaluations, static code quality analysis, diff minimizations, and automated linting on GitHub pull requests.

The Service comprises:
1. **ZeroSlop Client Runner**: The GitHub Action wrapper deployed within Customer's CI workflows.
2. **ZeroSlop Invariant Cloud Engine**: The closed-source server-side verification infrastructure.
3. **Sovereign CLI & Developer Tools**: Local inspection binaries.

All algorithms, AST patterns, reduction matrices, heuristics, designs, documentation, and trade secrets remain the sole and exclusive intellectual property of Ribbsaeter Systems.

---

### 2. Commercial Subscriptions & Authorized Use
Subject to timely payment of applicable subscription fees and continuous adherence to these Terms, Ribbsaeter Systems grants Customer a limited, non-exclusive, non-transferable, revocable license to execute the Service within Customer's designated GitHub repositories.

* **Solo Engineer Tier**: Authorized for one (1) developer account across personal and open-source repositories.
* **Engineering Team Tier**: Authorized for up to the contracted number of seats across organization repositories.
* **Enterprise Core Tier**: Authorized for organization-wide deployment, including self-hosted runner integration and custom architectural invariant rules.

Customer shall ensure that API keys (`RST_LIVE_xxx`) are treated as confidential credentials and not disclosed, committed to public repositories, or shared with unauthorized third parties.

---

### 3. Strict Prohibitions & Acceptable Use Policy
Customer expressly agrees NOT to:
1. **Reverse Engineer**: Decompile, disassemble, reverse engineer, or attempt to derive the source code or trade secrets of the Service or its verification cloud;
2. **AI Model Training & Benchmarking**: Use the Service, its outputs, telemetry, or invariant diagnostic logs to train, fine-tune, evaluate, validate, or benchmark any competing artificial intelligence model, machine learning architecture, code review bot, or static analysis engine;
3. **Resell or Sublicense**: Rent, lease, distribute, timeshare, or commercially resell access to the Service without an executed OEM Partnership Agreement;
4. **Circumvent Controls**: Bypass, disable, or tamper with any authentication, cryptographic license checks, or rate limits;
5. **Malicious Exploitation**: Transmit malicious code, viruses, or use the Service for denial-of-service attempts.

---

### 4. Zero Code Retention Guarantee & Privacy
Ribbsaeter Systems operates under an uncompromising **Zero Code Retention Guarantee**:
* **Ephemeral Processing Only**: Pull request diffs transmitted to the ZeroSlop API are analyzed strictly in volatile memory.
* **No Storage**: Source code diffs are **never saved to disk, persistent databases, or log files**.
* **Zero Model Training**: Customer code is **never used to train, retrain, or fine-tune foundation models or third-party AI systems**.
* Full details are set forth in the [Zero Code Retention & Privacy Policy](PRIVACY_POLICY.md).

---

### 5. Fees, Invoicing & Cancellation
1. **Billing**: Subscriptions are billed on a recurring monthly or annual basis via Stripe.
2. **Automatic Renewal**: Subscriptions automatically renew until canceled via the Ribbsaeter Systems billing portal.
3. **Taxes**: All fees are exclusive of value-added tax (VAT) or applicable withholding taxes unless stated otherwise.
4. **Suspension for Non-Payment**: We reserve the right to deactivate API keys for overdue accounts after five (5) business days' notice.

---

### 6. Disclaimer of Warranties & Limitation of Liability
1. **"As Is" Provision**: THE SERVICE IS PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTIES OF ANY KIND, WHETHER EXPRESS, IMPLIED, OR STATUTORY, INCLUDING MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NON-INFRINGEMENT.
2. **Merge Responsibility**: ZeroSlop provides architectural invariant verification; Customer remains solely responsible for the final human review, compilation, deployment, and security of code merged into Customer's repositories.
3. **Limitation of Liability**: TO THE MAXIMUM EXTENT PERMITTED BY LAW, IN NO EVENT SHALL RIBBSAETER SYSTEMS OR PATRICK RIBBSAETER BE LIABLE FOR ANY CONSEQUENTIAL, INDIRECT, INCIDENTAL, SPECIAL, OR PUNITIVE DAMAGES (INCLUDING LOSS OF PROFITS, DATA, OR REPOSITORY DOWNTIME). IN ALL CASES, LICENSOR'S AGGREGATE LIABILITY SHALL BE STRICTLY CAPPED AT THE TOTAL FEES ACTUALLY PAID BY CUSTOMER TO LICENSOR IN THE TWELVE (12) MONTHS PRECEDING THE CLAIM.

---

### 7. Trademarks & Brand Protection
"ZeroSlop", "ZeroSlop PR", "ZeroSlop Invariant Engine", and "Ribbsaeter Systems" are proprietary trademarks of Patrick Ribbsaeter / Ribbsaeter Systems. No license to use any trademark, logo, or brand emblem is granted without prior written consent.

---

### 8. Governing Law & Dispute Resolution
These Terms and any dispute arising out of or related to the Service shall be governed by and construed in accordance with the substantive laws of **Switzerland**, without regard to conflict of laws principles or the UN Convention on Contracts for the International Sale of Goods (CISG).

The competent commercial courts of the **Canton of Zurich, Switzerland** shall have exclusive jurisdiction over any dispute or claim arising under these Terms.

---

### 9. Contact Information
For commercial licensing, enterprise master service agreements (MSA), or legal inquiries:
**Ribbsaeter Systems Legal & Enterprise Governance**  
Email: [legal@ribbsaetersystems.com](mailto:legal@ribbsaetersystems.com)  
Website: [https://ribbsaetersystems.com/zeroslop](https://ribbsaetersystems.com/zeroslop)  
Headquarters: Zurich, Switzerland · Amsterdam · Eindhoven
