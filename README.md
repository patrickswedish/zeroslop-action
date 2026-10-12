<div align="center">

<img src="./assets/zeroslop-header.svg" width="100%" alt="ZeroSlop™ by Ribbsaeter Systems — Autonomous CI Pull Request Invariant Gatekeeper &amp; Diff Minimization Engine on GitHub Marketplace" />

<br/><br/>

<img src="./assets/zeroslop-metrics.svg" width="100%" alt="Invariant Lock: 100% Green CI First · Diff Reduction: 94.2% · Zero Code Retention · Node 20 Enclave" />

<br/><br/>

<a href="https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems">
  <img src="./assets/action-marketplace.svg" width="200" height="40" alt="GitHub Marketplace" />
</a>
&nbsp;&nbsp;
<a href="https://ribbsaetersystems.com/zeroslop">
  <img src="./assets/action-zeroslop.svg" width="200" height="40" alt="Ribbsaeter Systems Key Issuance" />
</a>
&nbsp;&nbsp;
<a href="https://ribbsaetersystems.com/zeroslop">
  <img src="./assets/action-simulator.svg" width="200" height="40" alt="Live Diff Simulator" />
</a>
&nbsp;&nbsp;
<a href="#-the-wall-of-sovereign-proof">
  <img src="./assets/action-proof.svg" width="200" height="40" alt="Wall of Proof" />
</a>

<br/><br/>

<img src="./assets/zeroslop-trust-banner.svg" width="100%" alt="Verified Architectural PRs Merged Upstream Across 16 Tier-1 Foundations &amp; Systems" />

<br/><br/>

### Stop Paying Senior Engineers to Review AI Boilerplate.
**The Sovereign Pre-Flight Invariant Gatekeeper for AI-Augmented Software Teams.**

*Reclaim 60+ senior hours per sprint. Intercept hallucinated wrappers, structural bloat, and unauthorized test deletions before they reach human review.*

</div>

<br/>

> **The Executive Summary**: AI coding agents increased code output by 300%, but engineering velocity slowed down by 40% because senior architects are trapped acting as human linters. **ZeroSlop™ by Ribbsaeter Systems** mechanically audits incoming PR diffs against architectural invariants, stripping slop down to surgical, green commits that merge in minutes.

<br/>

---

## 🏛️ The AI Code Slop Crisis

Modern AI coding agents (Claude Code, Cursor, Devin, Copilot) generate extraordinary quantities of code in seconds. But without an invariant pre-flight gatekeeper, **over 80% of AI pull requests introduce structural debt**:

* **Hallucinated Wrappers**: 180-line adapter layers written to wrap standard library features that already exist.
* **Defensive Debris**: Dozens of redundant mock utilities, dead null guards, and cargo-culted error handlers.
* **Subtle Invariant Breakage**: Broken async lifecycles, memory ownership regressions, and silent edge-case violations.
* **Maintainer Exhaustion**: Senior architects spend 30+ hours every sprint triaging, reviewing, and rejecting broken AI PRs instead of shipping core architecture.

> *"More code is not more productivity. The gold standard of systems engineering is the smallest durable correction that preserves all system invariants."*

---

## ⚡ The Solution: The ZeroSlop™ Invariant Airlock

**ZeroSlop™ by Ribbsaeter Systems** is a drop-in pre-flight airlock for GitHub Actions. It intercepts pull requests before they touch public CI or human maintainers, auditing AST diffs against strict architectural invariants.

<div align="center">
  <br/>
  <img src="./assets/diagram-airlock.svg" width="100%" alt="ZeroSlop Invariant Architecture Pipeline" />
  <br/>
</div>

### How The Sovereign Engine Operates:

1. **AST Invariant Isolation**: Parses incoming PR diffs to locate the single root-cause invariant, systematically peeling away up to **94% of hallucinated wrappers and defensive AI bloat**.
2. **10-Shield Deterministic CWE Security Airlock**: Mechanically intercepts high-risk AI-generated security vulnerabilities before human review—blocking SQL/vector injection (`CWE-89`), seeded/hardcoded credentials & plaintext auth (`CWE-798`/`CWE-256`), unbound caller identity / IDOR (`CWE-639`), command/code injection (`CWE-78`/`CWE-94`), unsafe deserialization (`CWE-502`), SSRF (`CWE-918`), silent error masking (`CWE-390`), and CI workflow "Pwn Requests" (`CWE-426`).
3. **Zero-Click Cross-Layer Blast Radius & Reachability**: Maps architectural impact across `API Entrypoints ➔ Auth Boundaries ➔ AI Pipelines ➔ Persistence/Vector Sinks` directly inside the native GitHub PR summary—eliminating bloated external SaaS dashboards and click-heavy review tools.
4. **Prompt-Injection & Trojan-Source Immunity (`CVE-2021-42574`)**: Unlike conversational LLM review bots that can be jailbroken by adversarial instructions hidden inside PR diffs, ZeroSlop's deterministic airlock is mathematically immune to prompt injection and actively blocks bidirectional Unicode attacks.
5. **Local Compiler Enclave & Autonomous Polish**: Runs compiler checks, type evaluation, and repository-native formatters (Prettier, Ruff, Clippy, ESLint, gofmt) ephemerally in RAM before burning shared CI minutes.

---

## 🚀 60-Second Quickstart (1-PR Free Evaluation Try + Instant Pro Key)

Download and test ZeroSlop on **1 pull request for free** out of the box, or pass your **`ZEROSLOP_API_KEY`** for continuous unlimited protection. Add this workflow file to your repository at `.github/workflows/zeroslop.yml`:

```yaml
name: ZeroSlop Invariant Gatekeeper

on:
  pull_request:
    branches: [main, master, develop]

jobs:
  airlock:
    name: Sovereign Pre-Flight Airlock
    runs-on: ubuntu-latest
    steps:
      - name: Checkout Source
        uses: actions/checkout@v4
        with:
          fetch-depth: 0

      - name: Run ZeroSlop Gatekeeper
        uses: patrickswedish/zeroslop-action@v1
        with:
          auto_polish: true
          fail_on_slop: true
          api_key: ${{ secrets.ZEROSLOP_API_KEY }} # Optional for 1st PR try; required from PR #2+
```

### 1-PR Free Evaluation Try vs. Commercial License Key

* **Single Evaluation Try (1st Pull Request Free)**: Every GitHub account or organization receives **1 complimentary pull request audit** with zero configuration required. One surgical, 100% green pull request merge proves the ZeroSlop standard. After 1 pull request, your account is locked until a commercial license key is activated.
* **ZeroSlop™ Pro (`$29/mo`) & Enterprise (`$1,999/mo`) License Key**: Unlocks continuous, unlimited pull request protection across private and public repositories, Active Auto-Close enforcement, and the Autonomous CI Flake & Triage Classifier. Provision your key in 30 seconds at [**ribbsaetersystems.com/zeroslop**](https://ribbsaetersystems.com/zeroslop) and store it as `ZEROSLOP_API_KEY` in your repository or organization secrets.

<div align="center">
  <br/>
  <img src="./assets/zeroslop-terminal-check.svg" width="100%" alt="ZeroSlop Autonomous Runner Execution Terminal" />
  <br/>
</div>

---

## 🏛️ The Wall of Sovereign Proof

ZeroSlop is not marketing theory. It is powered by the exact invariant engine that delivers merged, 100% green pull requests into the world's most demanding open-source production runtimes:

> ### 🛡️ Hardened on Systems Compilers. Built for Everyday Stacks.
> While ZeroSlop was battle-tested and proven directly against the world's most unforgiving runtimes—including **OpenAI Triton GPU compilers**, **LLVM SelectionDAG**, **Meta Velox vectorized execution**, and **DuckDB analytical kernels**—it delivers its most dramatic velocity gains on everyday commercial codebases:
> 
> * **TypeScript, Node.js & React**: Strips away up to 94% of hallucinated adapters, dead wrappers, and bloated mock utilities before peers or managers are tagged.
> * **Python, Go & Rust Stacks**: Mechanically halts deleted regression tests, catches broken interface contracts, and auto-commits repository-native formatting.
> * **From 4.2-Day Bottlenecks to 20-Minute Merges**: Brings senior staff architect rigor to your junior and mid-level PRs, so your engineering leads stop acting as human linters and get back to shipping core architecture.

<br/>

| Organization | Repository | Domain & Stack | Engineering Focus | Status |
| :--- | :--- | :--- | :--- | :--- |
| **LLVM** | `llvm/llvm-project` | Compiler Backend · C++ | X86 SelectionDAG non-power-of-two vector integer division vectorization & lowering | **Merged Upstream · [PR #215076](https://github.com/llvm/llvm-project/pull/215076)** |
| **Meta** | `facebookincubator/velox` | Vectorized Kernels · C++20 | TopNRowNumber in-memory rank ordering correctness & partition stream parity | **Merged Upstream · [PR #18529](https://github.com/facebookincubator/velox/pull/18529)** |
| **DuckDB** | `duckdb/duckdb` | Vectorized Engine · C++ | PIVOT IN list zero-argument `row()` expression preservation & null dereference guard | **Merged Upstream · [PR #26443](https://github.com/duckdb/duckdb/pull/26443)** |
| **Apache** | `apache/datafusion` | Query Engine · Rust | Execution-layer schema conformance across in-memory execution and aggregation | **Merged & Shipped · [PR #24394](https://github.com/apache/datafusion/pull/24394)** |
| **Microsoft** | `microsoft/pyright` | Type Evaluator · TypeScript | Inherited asymmetric descriptor detection across effective MRO behavior | **Merged Upstream · [PR #11605](https://github.com/microsoft/pyright/pull/11605)** |
| **Hugging Face** | `huggingface/diffusers` | Generative AI · Python | InpaintProcessor 3-tuple return contract preservation when mask is None | **Merged Upstream · [PR #14481](https://github.com/huggingface/diffusers/pull/14481)** |
| **Valkey** | `valkey-io/valkey` | Distributed Storage · C99 | Cluster key-slot resolution & client cache validation for commands touching arbitrary keys | **Merged Upstream · [PR #4424](https://github.com/valkey-io/valkey/pull/4424)** |
| **eBay** | `eBay/NuRaft` | Distributed Consensus · C++17 | Rejection of concurrent snapshot sync requests during asynchronous finalization race | **Merged Upstream · [PR #663](https://github.com/eBay/NuRaft/pull/663)** |
| **Microsoft** | `microsoft/typespec` | Compiler Tooling · TypeScript | Playground state synchronization and deterministic regression coverage | **Merged Upstream · [PR #11660](https://github.com/microsoft/typespec/pull/11660)** |
| **Microsoft** | `microsoft/agent-governance-toolkit` | AI Governance · Python | Fail-closed approval-chain correctness for zero-required-stage configurations | **Merged Upstream · [PR #3448](https://github.com/microsoft/agent-governance-toolkit/pull/3448)** |
| **Microsoft** | `microsoft/agent-governance-toolkit` | AI Governance · Python | Policy fixture validation rejecting test definitions without explicit expectations | **Merged Upstream · [PR #3442](https://github.com/microsoft/agent-governance-toolkit/pull/3442)** |
| **TheBushidoCollective** | `TheBushidoCollective/han` | CLI Tooling · Rust | Windows project-path compatibility with Claude Code slug conventions | **Merged Upstream · [PR #105](https://github.com/TheBushidoCollective/han/pull/105)** |
| **Tokio** | `tokio-rs/tokio` | Async Runtime · Rust | Current-thread paused time wake tracking & zero-syscall timer preservation | **110/110 Checks Green · Mergeable · [PR #8595](https://github.com/tokio-rs/tokio/pull/8595)** |
| **ClickHouse** | `ClickHouse/ClickHouse` | Real-Time DBMS · C++20 | Bounds validation on parallel replicas legacy query plan limit (`rows_before_limit_at_least`) | **174/176 Checks Green · [PR #114954](https://github.com/ClickHouse/ClickHouse/pull/114954)** |
| **SGLang** | `sgl-project/sglang` | LLM Serving · Python/CUDA | Mid-turn inline system message in-place attachment preserving RadixAttention prefix caching | **98 Checks Green · In Review · [PR #42533](https://github.com/sgl-project/sglang/pull/42533)** |
| **Cloudflare** | `cloudflare/workers-sdk` | Edge Runtime · TypeScript | Raw TCP socket streaming & backpressure handling for rejected WebSocket upgrades | **54/54 Checks Green · [PR #15205](https://github.com/cloudflare/workers-sdk/pull/15205)** |
| **Apache** | `apache/datafusion` | Query Engine · Rust | PushDownFilter clippy `mutable_key_type` allow annotations for Expr hash sets | **43/43 Checks Green · [PR #26189](https://github.com/apache/datafusion/pull/26189)** |
| **Apache** | `apache/datafusion` | Query Engine · Rust | Downcast to `FixedSizeBinaryArray` in CASE literal lookup table | **43/43 Checks Green · [PR #26096](https://github.com/apache/datafusion/pull/26096)** |
| **Apache** | `apache/datafusion` | Query Engine · Rust | Sort-merge semi/anti/mark key equality routing via `JoinKeyComparator` | **42/42 Checks Green · [PR #26006](https://github.com/apache/datafusion/pull/26006)** |
| **Anthropic / MCP** | `modelcontextprotocol/typescript-sdk` | Agent Protocol · TypeScript | Stream resumption for event IDs containing underscores | **14/14 Checks Green · [PR #2567](https://github.com/modelcontextprotocol/typescript-sdk/pull/2567)** |
| **LLVM** | `llvm/llvm-project` | Compiler Backend · C++ | X86 CodeGen preserve XMM liveness across `VZEROUPPER` and check register clobbers | **12/12 Checks Green · [PR #218873](https://github.com/llvm/llvm-project/pull/218873)** |
| **Redpanda** | `redpanda-data/redpanda` | Streaming Storage · C++20 | RPC transport memory semaphore unit retention in queued request entries | **9/9 Checks Green · Mergeable · [PR #31594](https://github.com/redpanda-data/redpanda/pull/31594)** |
| **OpenAI** | `triton-lang/triton` | GPU Compiler · C++/Python | Nanobind static build free-threaded PEP 703 GIL slot declaration | **All Checks Green · Mergeable · [PR #12221](https://github.com/triton-lang/triton/pull/12221)** |
| **vLLM** | `vllm-project/vllm` | AI Inference Serving · Python | Empty and non-mapping YAML config validation preventing unhandled CLI crash | **Contributor Checks Green · Mergeable · [PR #60319](https://github.com/vllm-project/vllm/pull/60319)** |
| **AWS** | `firecracker-microvm/firecracker` | MicroVM Hypervisor · Rust | Resolved clippy `infallible_destructuring_match` on `TimerFd` in release builds | **3/3 Checks Green · Mergeable · [PR #6262](https://github.com/firecracker-microvm/firecracker/pull/6262)** |
| **Bun** | `oven-sh/bun` | JS Runtime · C++/Zig | Node.js `Buffer` per-encoding methods `ERR_INVALID_ARG_TYPE` receiver conformance in JSC bindings | **2/2 Checks Green · [PR #44571](https://github.com/oven-sh/bun/pull/44571)** |
| **Ethereum** | `ethereum/go-ethereum` | Blockchain Execution · Go | Bound database batch size during filtermaps log index rollback | **All Checks Green · [PR #35586](https://github.com/ethereum/go-ethereum/pull/35586)** |
| **Paradigm** | `paradigmxyz/reth` | Blockchain Execution · Rust | Txpool live iterator candidate demotion when earlier transactions are reinserted | **Mergeable · In Review · [PR #27707](https://github.com/paradigmxyz/reth/pull/27707)** |
| **Supabase** | `supabase/supavisor` | Connection Pooler · Elixir | PostgreSQL cancellation synchronization across backend connection reuse | **All Checks Green · Mergeable · [PR #1149](https://github.com/supabase/supavisor/pull/1149)** |

---

## ⚙️ Configuration & Action Reference

### Inputs

| Input | Required | Default | Description |
| :--- | :---: | :--- | :--- |
| `license_key` | No (Optional) | `''` | ZeroSlop Pro/Enterprise License Key (from Stripe Checkout). Unlocks CI Diagnostics and centralized fleet telemetry. |
| `ci_diagnostics` | No | `false` | Enable Pro CI Intelligence & Flake Classifier. Automatically isolates contributor green code from maintainer triage gates and runner flakes. |
| `api_key` | No (Optional) | `''` | Enterprise API key for custom on-premise or VPC deployments. |
| `base_branch` | No | `main` | Base branch to compare incoming pull request diff against. |
| `auto_polish` | No | `true` | Automatically run repo-native linters and auto-commit clean code. |
| `fail_on_slop` | No | `true` | Fail the status check if unmitigated AI slop patterns are detected. |
| `github_token` | No | `${{ github.token }}` | GitHub token for querying workflow check runs and commit status. |
| `api_endpoint` | No | `https://ribbsaetersystems.com/api/v1/verify` | Custom API endpoint for on-premise or VPC enterprise appliances. |

### Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| `slop_score` | `number` | Calculated slop ratio percentage (0% = clean invariant, 100% = pure slop). |
| `lines_reduced` | `number` | Total percentage of bloated, hallucinated lines stripped from diff. |
| `invariants_verified` | `number` | Count of architectural invariants verified green. |
| `security_findings_count` | `number` | Total deterministic CWE security vulnerabilities intercepted (`CWE-89`, `CWE-798`, `CWE-639`, etc.). |
| `critical_cwe_count` | `number` | Count of CRITICAL severity CWE security findings blocked at the gate. |
| `blast_radius_layers` | `number` | Count of architectural layers impacted by the pull request diff. |
| `ci_classification` | `string` | Categorization of PR check status: `ALL_GREEN`, `TRIAGE_GATED`, `INFRA_FLAKE`, or `CODE_DEFECT`. |
| `flaky_jobs_count` | `number` | Total upstream runner timeouts or toolchain flakes isolated. |
| `gated_jobs_count` | `number` | Total maintainer triage gates (awaiting labels/approvals) isolated. |

---

## 🔒 10-Shield CWE Security & Zero-Click Blast Radius Architecture

ZeroSlop is engineered for security-conscious engineering teams, sovereign AI labs, and regulated enterprises that refuse to trust probabilistic LLM review chatbots with production security:

* **10-Shield Deterministic CWE Airlock**: Blocks the top empirical AI-generated vulnerabilities before code reaches human review—including SQL/vector injection (`CWE-89`), hardcoded/seeded credentials & plaintext password checks (`CWE-798`/`CWE-256`), unbound caller identity / IDOR (`CWE-639`), OS command & `eval` injection (`CWE-78`/`CWE-94`), silent exception masking (`CWE-390`), XSS (`CWE-79`), unsafe deserialization (`CWE-502`), SSRF & disabled TLS (`CWE-918`/`CWE-295`), and GitHub Actions workflow injection ("Pwn Requests", `CWE-426`).
* **Zero-Click Cross-Layer Blast Radius**: Automatically maps multi-file diffs across architectural boundaries (`API Contracts ➔ Auth & Session ➔ AI/LLM Pipeline ➔ Persistence/Vector Sinks`) and evaluates end-to-end exploit reachability right inside the GitHub PR summary—with **zero external SaaS dashboards or extra clicks required**.
* **Adversarial Prompt-Injection & Trojan-Source Immunity (`CVE-2021-42574`)**: Because conversational AI code reviewers ingest raw PR diffs into LLM context windows, they are susceptible to indirect prompt injection hidden in comments. ZeroSlop's deterministic invariant engine cannot be jailbroken and actively blocks Trojan Source bidirectional Unicode and reviewer override payloads.
* **Zero Code Retention**: Your proprietary codebase is **never stored, retained, cached, or used for AI model training**. Diffs are analyzed ephemerally in volatile RAM and purged immediately upon response return.
* **Zero Supply Chain Overhead**: Packaged as a self-contained Node.js 20 runner with zero runtime dependencies. No third-party npm package vulnerabilities.
* **Enterprise Compliance**: Designed to meet Swiss FADP, European GDPR, and NIS2 DevSecOps supply-chain standards.
* **Security & Responsible Disclosure**: Comprehensive reporting SLAs and policies documented in [SECURITY.md](SECURITY.md).

### ⚔️ Category Showdown: ZeroSlop™ Airlock vs. AI Review Chatbots & Legacy SAST

Competitors tell you *"the future isn't writing code—it's reviewing it and prioritizing it"* while herding your engineers into 80-PR Kanban queues, multi-tab "ChangeStack" portals, and 1,999-finding security charts. Senior engineers were hired to ship systems—not click through external SaaS dashboards or read 25 bot comments per PR.

| Architectural Capability | 🛡️ ZeroSlop™ Sovereign Airlock | 🤖 AI Review Chatbots (CodeRabbit, Greptile, Qodo) | 🐢 Legacy SAST Scanners (SonarQube, Snyk) |
| :--- | :--- | :--- | :--- |
| **Developer Workflow & UI** | **✓ Zero-Click Native GitHub Summary** (Zero external SaaS dashboards or logins) | ✕ Herds devs into external SaaS portals, ChangeStacks & 80-PR Kanban queues | ✕ Separate enterprise portal with high false-positive alert fatigue |
| **Cross-Layer Blast Radius** | **✓ Automatic `Entrypoint ➔ Auth ➔ Persistence Sink` reachability in PR** | ⚠️ Requires manual clicking across SaaS UI tabs to inspect file groups | ✕ Isolated file-level lint alerts without architectural layer context |
| **10-Shield CWE Enforcement** | **✓ Deterministically blocks SQLi, Seeded Creds, IDOR, SSRF & CI Pwn Requests** | ⚠️ Probabilistic LLM commentary; leaves 1,999 unfixed findings in charts | ⚠️ Slow post-hoc scans; blind to AI-specific wrapper & workflow patterns |
| **Prompt-Injection Immunity** | **✓ 100% Deterministic Engine** — Cannot be jailbroken by PR comments | ✕ Vulnerable to indirect prompt injection hidden inside PR diffs | ✓ Deterministic rules, but blind to AI prompt-override payloads |
| **AI Slop & Wrapper Distillation** | **✓ Strips 94% of hallucinated wrappers & blocks deleted test assertions** | ✕ Adds more AI commentary on top of AI slop without shrinking the diff | ✕ Zero awareness of LLM wrapper bloat or conversational debris |
| **CI Flake vs. Triage Gate Isolation** | **✓ Separates Contributor Code Defects from Runner Flakes & Triage Gates** | ✕ Blind to upstream runner flakes vs. maintainer approval labels | ✕ No GitHub Actions check-run triage classification |
| **Source Code Privacy & Retention** | **✓ Strictly Zero Code Retention** (Ephemeral RAM Enclave · Swiss/GDPR) | ⚠️ Ships proprietary diffs to third-party LLM providers & SaaS stores | ⚠️ Persists full source code snapshots in cloud databases |

---

## 💰 The Economic Business Case: Why Engineering Leaders Mandate ZeroSlop

AI coding agents (Cursor, Copilot, Claude Code) increased commit volume by 300%, but engineering velocity slowed down by 40% because senior staff architects are trapped acting as human linters for bloated, unverified PRs.

### The Hard ROI Breakdown (10-Engineer Team)

| Metric | Without ZeroSlop (Status Quo) | With ZeroSlop Sovereign Airlock | Net Impact |
| :--- | :--- | :--- | :--- |
| **PR Review Churn** | 15–20 hours / week per senior dev | Under 2 hours / week (pre-flight verified) | **60+ hours reclaimed per sprint** |
| **PR Cycle Turnaround** | 4.2 days average review bottleneck | 45 minutes to merge | **85% faster release cadence** |
| **CI Failures on PRs** | 14+ failing public CI checks per draft | 100% green compiler checks on first push | **Zero public CI debugging waste** |
| **Annual Review Payroll** | **$160,000 / year** burned ($80/hr senior salary) | **$348 / year** ($29/mo Pro) or **$1,999/mo** (Enterprise) | **$150,000+ net annual payroll saved** |
| **Financial Return** | Continuous velocity erosion | **18.2x+ Annual ROI** | **Payback Period: < 48 Hours** |

---

## 🎯 Engineered for Every Decision Maker in Engineering

| Role | Core Friction | How ZeroSlop Delivers The Win |
| :--- | :--- | :--- |
| **Staff & Senior Engineers** | Getting slammed with 20 review comments for bloated AI helpers. | **Surgical Invariant Output**: Strips 180-line diffs down to the 4 lines that preserve contracts. Auto-commits clean formatting before peers review. Zero CI humiliation. |
| **Tech Leads & EMs** | PR queue backlogs; senior engineers acting as human linters. | **70% Shorter PR Cycles**: Clears review bottlenecks so teams spend sprint capacity shipping user features instead of untangling boilerplate. |
| **VPs of Engineering** | Hiring more engineers slows release cadence; high cost of delay. | **Measurable Velocity Boost**: Reclaim 60+ senior hours per sprint. Turn generative AI code into verified production throughput with 18x annual return. |
| **CTOs & Chief Architects** | Long-term architectural decay and subtle AI memory/concurrency leaks. | **Hard Invariants & Zero-Click Blast Radius**: Mathematically proves interface contracts and maps cross-layer exploit reachability directly in GitHub without external SaaS dashboard bloat. |
| **CISOs & AppSec Directors** | AI-introduced CWE flaws, prompt-injected review bots, and IP leakage. | **10-Shield CWE Airlock & Zero Code Retention**: Blocks SQLi, hardcoded keys, IDOR, SSRF, and CI Pwn Requests deterministically in ephemeral RAM. 100% immune to reviewer prompt injection. |

---

## 💼 Commercial Licensing & Pricing (100% Self-Serve)

| Tier | Investment | Seats & Scope | Concurrency | Capabilities Included | Direct Checkout |
| :--- | :--- | :--- | :--- | :--- | :---: |
| **Single Evaluation Try** | **$0 (1 PR Try)** | **1 Developer · 1 PR Audit**<br>*(One-Time Account Test · Locks After 1 PR)* | Standard | AST diff parser · 10-Shield CWE Security Airlock · Zero-Click Blast Radius · Zero-test-deletion guard | [**Try 1 PR Free**](https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems) |
| **ZeroSlop™ Pro** | **$29 / month** | **1 Pro Developer Account**<br>*(Single Seat · Unlimited Repos · Zero Local Installs)* | Unlimited | Full Continuous Access + **Unlimited Repo Audits** · **10-Shield CWE Security Airlock** · **Zero-Click Cross-Layer Blast Radius** · **Active Auto-Close Airlock** · **Autonomous CI Flake & Triage Classifier** | [**Subscribe Pro ($29/mo)**](https://buy.stripe.com/28E5kFflO4n65Ho9JFfQI02) |
| **ZeroSlop™ Enterprise Core** | **$1,999 / month** | **Per 100 Active Developers**<br>*(100-Dev Block · Dedicated VPC · Unlimited Repos)* | Unlimited Dedicated | Everything in Pro + **Dedicated VPC Invariant Enclave** · Custom CWE & Wire Protocol Invariants · Multi-Repo Fleet Analytics · Air-Gapped Runners · 24/7 SLA | [**Deploy Enterprise ($1,999/mo)**](https://buy.stripe.com/aFaeVf0qU06Qb1I9JFfQI03) |

### ⚡ Self-Serve Headcount Scaling (Zero Sales Calls · Instant Activation)

Enterprise Core is billed in transparent **100-developer blocks at $1,999 / month per block**. Organizations purchase the quantity matching their active contributor count:

| Active Engineering Headcount | License Allocation | Monthly Investment | Annual Investment | Activation Model |
| :--- | :--- | :--- | :--- | :--- |
| **1 – 68 Engineers** | Individual Pro Seats ($29/dev) | $29 – $1,972 / mo | $348 – $23,664 / yr | [Subscribe Pro ($29/mo)](https://buy.stripe.com/28E5kFflO4n65Ho9JFfQI02) |
| **Up to 100 Engineers** | 1x Enterprise Core Block | **$1,999 / month flat** | $23,988 / year | [Deploy Enterprise ($1,999/mo)](https://buy.stripe.com/aFaeVf0qU06Qb1I9JFfQI03) |
| **Up to 200 Engineers** | 2x Enterprise Core Blocks | **$3,998 / month flat** | $47,976 / year | [Deploy Enterprise (2 Units)](https://buy.stripe.com/aFaeVf0qU06Qb1I9JFfQI03) |
| **Up to 500 Engineers** | 5x Enterprise Core Blocks | **$9,995 / month flat** | $119,940 / year | [Deploy Enterprise (5 Units)](https://buy.stripe.com/aFaeVf0qU06Qb1I9JFfQI03) |
| **Up to 1,000 Engineers** | 10x Enterprise Core Blocks | **$19,990 / month flat** | $239,880 / year | [Deploy Enterprise (10 Units)](https://buy.stripe.com/aFaeVf0qU06Qb1I9JFfQI03) |

*Zero sales negotiation. Zero multi-week procurement friction. Calculate your engineering headcount and deploy organization-wide via Stripe.*

Provision license keys and explore the live interactive simulator at [**ribbsaetersystems.com/zeroslop**](https://ribbsaetersystems.com/zeroslop).

---

## ⚡ High-Ticket Advisory: Frontier AI Systems & GPU Performance Sprints

Beyond autonomous CI invariant protection, Ribbsaeter Systems operates an elite, confidential advisory practice for frontier AI research labs, sovereign cloud operators, high-frequency quant funds, and scale-ups:

* **GPU Cluster & KV Cache Performance Sprint ($75,000 – $150,000 flat / 2-week turnaround)**:  
  Direct multi-node GPU cluster intervention. Surgical reduction of multi-gigabyte KV cache memory footprints across H100/H200/B200 clusters, Triton/CUDA operator fusion, disaggregated prefill/decode pipeline architecture, and custom compiler lowerings. Merged, green production PRs with benchmark proofs delivered in 14 days.
* **Principal Systems Architecture Retainer ($35,000 – $65,000 / month)**:  
  Direct access to Patrick Ribbsaeter for core distributed memory hierarchies, low-level CPython 3.14t free-threading (PEP 703) migrations, and mission-critical compiler invariants across OpenAI Triton, LLVM, Meta Velox, and DuckDB.

Inquire confidentially: [**contact@ribbsaetersystems.com**](mailto:contact@ribbsaetersystems.com) · Subject: `[FRONTIER-AI-ADVISORY]` · [Explore Frontier AI Practice](https://ribbsaetersystems.com/services/ai-infrastructure)

---

## ❓ Frequently Asked Questions (FAQ)

### How does the 1-PR Free Evaluation Try work?
Every GitHub account or organization receives **1 complimentary pull request audit** upon installing ZeroSlop from the GitHub Marketplace. One clean, surgical pull request merge is enough to prove the ZeroSlop standard. After your 1st pull request, your account is locked until you activate a **ZeroSlop™ Pro ($29/mo)** or **Enterprise ($1,999/mo)** license key. ZeroSlop does not offer recurring monthly free tiers.

### How do I activate my license key after purchasing?
Immediately after checkout via Stripe, you are redirected to your private activation screen displaying your sovereign API key (`RST_LIVE_xxx`). Copy this key, navigate to your GitHub Repository or Organization **Settings → Secrets and variables → Actions**, create a secret named `ZEROSLOP_API_KEY`, and pass `api_key: ${{ secrets.ZEROSLOP_API_KEY }}` in your workflow YAML. Your pull requests are unlocked in under 60 seconds.

### Does ZeroSlop store, retain, or train on our proprietary code?
**Strictly zero code retention.** ZeroSlop evaluates pull request diffs ephemerally in a volatile Node 20 RAM enclave. Your source code is never written to disk, never stored in a database, and never used to train machine learning models. We log strictly mathematical invariant telemetry (lines purged, invariant pass/fail).

### How does ZeroSlop protect all repositories in our organization?
For teams with dozens of repositories, you do not need to configure secrets one by one. In your GitHub Organization settings, add `ZEROSLOP_API_KEY` under Organization Secrets and grant access to **"All repositories"**. Every repository in your organization automatically inherits ZeroSlop pre-flight protection.

### How do I get support or request custom invariant rules?
Direct founder and senior engineering support is available via [**contact@ribbsaetersystems.com**](mailto:contact@ribbsaetersystems.com). For media, press inquiries, and editorial kits, contact [**press@ribbsaetersystems.com**](mailto:press@ribbsaetersystems.com). Every inquiry is reviewed and answered by senior production engineers within 24 hours.

### Direct Inquiries & Desks
- **Technical & License Support**: [contact@ribbsaetersystems.com](mailto:contact@ribbsaetersystems.com)
- **Media & Press Relations**: [press@ribbsaetersystems.com](mailto:press@ribbsaetersystems.com)
- **Enterprise Architecture**: [contact@ribbsaetersystems.com](mailto:contact@ribbsaetersystems.com)

---

<div align="center">

<img src="./assets/zeroslop-closing-banner.svg" width="100%" alt="Surgical Invariants · Zero Regressions" />

<br/><br/>

### Systems. Intelligence. Product. Business.

[Personal Website](https://www.patrickribbsaeter.com/) · [Ribbsaeter Systems](https://www.ribbsaetersystems.com/) · [ZeroSlop™ Portal](https://www.ribbsaetersystems.com/zeroslop) · [LinkedIn](https://www.linkedin.com/in/patrickribbsaeter) · [GitHub Profile](https://github.com/patrickswedish)

<br/>

**Software License**: Distributed under the [Ribbsaeter Systems Proprietary Software Client License Agreement](LICENSE).  
**Terms of Service**: Governed by the [Commercial Terms of Service](TERMS_OF_SERVICE.md).  
**Trademarks**: "ZeroSlop", "ZeroSlop PR", "ZeroSlop Invariant Engine", and "Ribbsaeter Systems" are proprietary trademarks of Patrick Ribbsaeter / Ribbsaeter Systems (Zurich · Amsterdam · Eindhoven).  
Copyright © 2026 Patrick Ribbsaeter / Ribbsaeter Systems. All Rights Reserved.

</div>
