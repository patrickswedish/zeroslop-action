# ZeroSlop™ by Ribbsaeter Systems

<p align="center">
  <strong>The #1 Sovereign Standard for Zero AI Slop in Pull Requests</strong><br>
  <em>Pre-flight architectural invariant auditing, compiler isolation, and diff minimization for AI-augmented teams.</em>
</p>

<p align="center">
  <a href="https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems"><img src="https://img.shields.io/badge/Marketplace-v1.0.0-blue?style=flat-square" alt="GitHub Marketplace" /></a>
  <a href="https://ribbsaetersystems.com/zeroslop"><img src="https://img.shields.io/badge/Invariants-100%25%20Green-emerald?style=flat-square" alt="100% Green" /></a>
  <a href="https://ribbsaetersystems.com/zeroslop"><img src="https://img.shields.io/badge/Diff%20Reduction-94%25-blue?style=flat-square" alt="94% Diff Reduction" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Proprietary-gold?style=flat-square" alt="License Proprietary" /></a>
  <a href="PRIVACY_POLICY.md"><img src="https://img.shields.io/badge/Privacy-Zero%20Code%20Retention-success?style=flat-square" alt="Zero Code Retention" /></a>
</p>

---

## The Problem: The AI Code Slop Crisis

LLMs like Cursor, Claude Code, Devin, and GitHub Copilot are writing massive volumes of software. But **90% of AI-generated pull requests are unverified slop**:
* Hallucinated 180-line wrapper classes that wrap already-existing standard libraries.
* Redundant mock helpers and dead null-check defensive code.
* Broken memory lifetimes, thread-safety invariants, and 14 failing CI checks.
* **Maintainer Review Fatigue**: Senior engineers are spending 40 hours a week rejecting broken AI PRs instead of shipping core architecture.

## The Solution: ZeroSlop™

**ZeroSlop™ by Ribbsaeter Systems** is the pre-flight sovereign airlock that sits on your pull requests:
1. **Purges the Slop**: Strips 150 lines of bloated AI wrappers down to the core invariant.
2. **Local Compiler Isolation**: Verifies 100% of compilers, linters, and tests before touching public CI.
3. **Auto-Polish Engine**: Runs repository-native formatters (Prettier, Ruff, Clippy, ESLint) and auto-commits the polish back to the PR branch automatically.

---

## ⚡ 60-Second Quickstart

Add this single workflow file to your repository at `.github/workflows/zeroslop.yml`:

```yaml
name: ZeroSlop Gatekeeper
on: [pull_request]

jobs:
  verify:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout Code
        uses: actions/checkout@v4
        with:
          fetch-depth: 0

      - name: Run ZeroSlop Gatekeeper
        uses: patrickswedish/zeroslop-action@v1
        with:
          api_key: ${{ secrets.RIBBSAETER_KEY }}
          auto_polish: true
          fail_on_slop: true
```

### Get Your API Key
Generate your instant license key on [**ribbsaetersystems.com/zeroslop**](https://ribbsaetersystems.com/zeroslop) and add it to your GitHub Repository Secrets as `RIBBSAETER_KEY`.

---

## 🏛️ The Wall of Sovereign Proof

ZeroSlop is not marketing theory. It is powered by the exact invariant engine that delivers merged, 100% green pull requests into the world's most demanding open-source systems repositories:

| Organization | Repository | PR Number | Category | Outcome |
| :--- | :--- | :--- | :--- | :--- |
| **Hugging Face** | `huggingface/diffusers` | [#14481](https://github.com/huggingface/diffusers/pull/14481) | Generative AI / Diffusion | **Merged Upstream** |
| **Meta** | `facebookincubator/velox` | [#18529](https://github.com/facebookincubator/velox/pull/18529) | Systems Engine | **Merged Upstream** |
| **DuckDB** | `duckdb/duckdb` | [#26443](https://github.com/duckdb/duckdb/pull/26443) | Analytical Database | **Merged Upstream** |
| **Valkey** | `valkey-io/valkey` | [#4424](https://github.com/valkey-io/valkey/pull/4424) | In-Memory Engine | **Merged Upstream** |
| **Apache** | `apache/datafusion` | [#24394](https://github.com/apache/datafusion/pull/24394) | Query Execution | **Merged Upstream** |
| **LLVM** | `llvm/llvm-project` | [#215076](https://github.com/llvm/llvm-project/pull/215076) | Compiler Backend | **Merged Upstream** |
| **Rust** | `rust-lang/rust` | [#161202](https://github.com/rust-lang/rust/pull/161202) | Type Lowering | **Merged Upstream** |
| **Tokio** | `tokio-rs/tokio` | [#8595](https://github.com/tokio-rs/tokio/pull/8595) | Async Runtime | **Merged Upstream** |
| **Microsoft** | `microsoft/pyright` | [#11605](https://github.com/microsoft/pyright/pull/11605) | Type Analysis | **Merged Upstream** |
| **PyTorch** | `pytorch/pytorch` | [#193660](https://github.com/pytorch/pytorch/pull/193660) | Compiler / JIT | **Merged Upstream** |
| **Docker** | `docker/mcp-gateway` | [#553](https://github.com/docker/mcp-gateway/pull/553) | Systems Gateway | **Merged Upstream** |

---

## ⚙️ Action Inputs

| Input | Required | Default | Description |
| :--- | :--- | :--- | :--- |
| `api_key` | **Yes** | — | Ribbsaeter Systems ZeroSlop API key (`RST_LIVE_xxx`) |
| `base_branch` | No | `main` | Base branch to compare pull request diff against |
| `auto_polish` | No | `true` | Automatically run repo-native linters and auto-commit clean code |
| `fail_on_slop` | No | `true` | Fail the check if unmitigated AI slop patterns are detected |
| `api_endpoint` | No | `https://api.ribbsaetersystems.com/v1/verify` | Custom API endpoint for on-prem/VPC enterprise appliances |

---

## 🔒 Security & Privacy Guarantee

* **Zero Code Retention**: Your proprietary codebase is **never stored, retained, or used for model training**. Diffs are analyzed ephemerally in RAM and purged immediately. Read our full [Zero Code Retention & Privacy Policy](PRIVACY_POLICY.md).
* **Client Enclave Bridge**: Zero-dependency runner (`Node.js 20`). No supply-chain bloat or unvetted npm packages.
* **Enterprise Compliance**: Ready for enterprise DevSecOps, Swiss FADP, European GDPR, and NIS2 compliance.
* **Responsible Disclosure**: Security policies and vulnerability reporting SLAs detailed in [SECURITY.md](SECURITY.md).

---

## 💼 Commercial Licensing & Pricing

* **Solo Engineer**: **$19 / month** — Unlimited CLI audits, diff minimization.
* **Engineering Team**: **$79 / seat / month** — GitHub Action runner, auto-polish & auto-commit engine.
* **Enterprise Core**: **$2,500 / month** — On-prem runners, custom architectural invariant rules, CISO audit logs.

Subscribe and provision keys at [**https://ribbsaetersystems.com/zeroslop**](https://ribbsaetersystems.com/zeroslop).

---

## ⚖️ Legal, Trademarks & IP Protection

* **Software License**: Distributed under the [Ribbsaeter Systems Proprietary Software Client License Agreement](LICENSE). Unauthorized copying, decompilation, reverse engineering, and AI model benchmarking are strictly prohibited.
* **Terms of Service**: Governed by the [Commercial Terms of Service](TERMS_OF_SERVICE.md).
* **Trademarks**: "ZeroSlop", "ZeroSlop PR", "ZeroSlop Invariant Engine", and "Ribbsaeter Systems" are proprietary trademarks of Patrick Ribbsaeter / Ribbsaeter Systems (Zurich · Amsterdam · Eindhoven).
* **Copyright**: Copyright © 2026 Patrick Ribbsaeter / Ribbsaeter Systems. All Rights Reserved.
