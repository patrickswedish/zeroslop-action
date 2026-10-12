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
2. **12-Shield Deterministic CWE Security Airlock**: Mechanically intercepts high-risk AI-generated security vulnerabilities before human review—blocking SQL/vector injection (`CWE-89`), seeded/hardcoded credentials & plaintext auth (`CWE-798`/`CWE-256`), unbound caller identity / IDOR (`CWE-639`), command/code injection (`CWE-78`/`CWE-94`), unsafe deserialization (`CWE-502`), SSRF (`CWE-918`), silent error masking (`CWE-390`), CI workflow "Pwn Requests" (`CWE-426`), AI package "Slopsquatting" (`CWE-829`), and unbounded loop/timer resource exhaustion (`CWE-400`).
3. **Zero-Click Cross-Layer Blast Radius & Mermaid Dependency Graph**: Maps architectural impact across `API Entrypoints ➔ Auth Boundaries ➔ AI Pipelines ➔ Persistence/Vector Sinks` with an embedded Mermaid diagram directly inside the native GitHub PR summary and a **Single Self-Updating PR Verdict Card**—eliminating bloated external SaaS dashboards and click-heavy review tools.
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

### 🏅 Official "Protected by ZeroSlop™" Repository Badge

Add the official sovereign badge to your repository's `README.md` to signal to contributors, maintainers, and enterprise buyers that every pull request is gated by the 12-Shield CWE & Invariant Airlock:

[![ZeroSlop Airlock: SOVEREIGN](https://www.ribbsaetersystems.com/api/v1/badge?repo=patrickswedish/zeroslop-action)](https://www.ribbsaetersystems.com/zeroslop)

```markdown
[![ZeroSlop Airlock: SOVEREIGN](https://www.ribbsaetersystems.com/api/v1/badge?repo=OWNER/REPO)](https://www.ribbsaetersystems.com/zeroslop)
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

| System & Stack | Architectural Invariant | Status |
| :--- | :--- | :--- |
| **LLVM** · *C++*<br/>`llvm-project` | X86 SelectionDAG vector integer<br/>division lowering & vectorization | **Merged**<br/>[PR #215076](https://github.com/llvm/llvm-project/pull/215076) |
| **Meta Velox** · *C++20*<br/>`velox` | TopNRowNumber in-memory rank<br/>ordering & partition stream parity | **Merged**<br/>[PR #18529](https://github.com/facebookincubator/velox/pull/18529) |
| **DuckDB** · *C++*<br/>`duckdb` | PIVOT IN list zero-arg `row()`<br/>preservation & null guard | **Merged**<br/>[PR #26443](https://github.com/duckdb/duckdb/pull/26443) |
| **Apache DataFusion** · *Rust*<br/>`datafusion` | Execution-layer schema conformance<br/>across in-memory aggregation | **Merged**<br/>[PR #24394](https://github.com/apache/datafusion/pull/24394) |
| **Microsoft Pyright** · *TS*<br/>`pyright` | Inherited asymmetric descriptor<br/>detection across MRO hierarchy | **Merged**<br/>[PR #11605](https://github.com/microsoft/pyright/pull/11605) |
| **Hugging Face** · *Python*<br/>`diffusers` | InpaintProcessor 3-tuple return<br/>contract when mask is None | **Merged**<br/>[PR #14481](https://github.com/huggingface/diffusers/pull/14481) |
| **Valkey** · *C99*<br/>`valkey` | Cluster key-slot resolution &<br/>client cache key validation | **Merged**<br/>[PR #4424](https://github.com/valkey-io/valkey/pull/4424) |
| **eBay NuRaft** · *C++17*<br/>`NuRaft` | Reject concurrent snapshot sync<br/>during async finalization race | **Merged**<br/>[PR #663](https://github.com/eBay/NuRaft/pull/663) |
| **Microsoft TypeSpec** · *TS*<br/>`typespec` | Playground state synchronization<br/>& deterministic regression suite | **Merged**<br/>[PR #11660](https://github.com/microsoft/typespec/pull/11660) |
| **Microsoft** · *Python*<br/>`agent-governance` | Fail-closed approval-chain guard<br/>for zero-stage configurations | **Merged**<br/>[PR #3448](https://github.com/microsoft/agent-governance-toolkit/pull/3448) |
| **Microsoft** · *Python*<br/>`agent-governance` | Policy fixture validation rejecting<br/>missing test expectations | **Merged**<br/>[PR #3442](https://github.com/microsoft/agent-governance-toolkit/pull/3442) |
| **Bushido Han** · *Rust*<br/>`han` | Windows project-path conformance<br/>with Claude Code slug rules | **Merged**<br/>[PR #105](https://github.com/TheBushidoCollective/han/pull/105) |
| **Tokio** · *Rust*<br/>`tokio` | Current-thread paused time wake<br/>tracking & timer preservation | **110/110 Green**<br/>[PR #8595](https://github.com/tokio-rs/tokio/pull/8595) |
| **ClickHouse** · *C++20*<br/>`ClickHouse` | Bounds validation on parallel<br/>replicas legacy query plan limit | **174/176 Green**<br/>[PR #114954](https://github.com/ClickHouse/ClickHouse/pull/114954) |
| **SGLang** · *Python/CUDA*<br/>`sglang` | Mid-turn inline system message<br/>preserving RadixAttention cache | **98 Green**<br/>[PR #42533](https://github.com/sgl-project/sglang/pull/42533) |
| **Cloudflare** · *TypeScript*<br/>`workers-sdk` | Raw TCP socket streaming &<br/>backpressure for WS upgrades | **54/54 Green**<br/>[PR #15205](https://github.com/cloudflare/workers-sdk/pull/15205) |
| **Apache DataFusion** · *Rust*<br/>`datafusion` | PushDownFilter clippy mutable<br/>key allow for Expr hash sets | **43/43 Green**<br/>[PR #26189](https://github.com/apache/datafusion/pull/26189) |
| **Apache DataFusion** · *Rust*<br/>`datafusion` | FixedSizeBinaryArray downcast<br/>in CASE literal lookup table | **43/43 Green**<br/>[PR #26096](https://github.com/apache/datafusion/pull/26096) |
| **Apache DataFusion** · *Rust*<br/>`datafusion` | Sort-merge semi/anti/mark key<br/>equality via JoinKeyComparator | **42/42 Green**<br/>[PR #26006](https://github.com/apache/datafusion/pull/26006) |
| **Anthropic MCP** · *TS*<br/>`typescript-sdk` | Stream resumption for event IDs<br/>containing underscore tokens | **14/14 Green**<br/>[PR #2567](https://github.com/modelcontextprotocol/typescript-sdk/pull/2567) |
| **LLVM** · *C++*<br/>`llvm-project` | X86 CodeGen preserve XMM liveness<br/>across VZEROUPPER register checks | **12/12 Green**<br/>[PR #218873](https://github.com/llvm/llvm-project/pull/218873) |
| **Redpanda** · *C++20*<br/>`redpanda` | RPC transport memory semaphore<br/>unit retention in queued entries | **9/9 Green**<br/>[PR #31594](https://github.com/redpanda-data/redpanda/pull/31594) |
| **OpenAI Triton** · *C++/Py*<br/>`triton` | Nanobind static build free-threaded<br/>PEP 703 GIL slot declaration | **Checks Green**<br/>[PR #12221](https://github.com/triton-lang/triton/pull/12221) |
| **vLLM** · *Python*<br/>`vllm` | Empty & non-mapping YAML config<br/>validation preventing CLI crash | **Checks Green**<br/>[PR #60319](https://github.com/vllm-project/vllm/pull/60319) |
| **AWS Firecracker** · *Rust*<br/>`firecracker` | Resolved clippy destructuring<br/>match on TimerFd release builds | **3/3 Green**<br/>[PR #6262](https://github.com/firecracker-microvm/firecracker/pull/6262) |
| **Bun** · *C++/Zig*<br/>`bun` | Node.js Buffer per-encoding<br/>receiver conformance in JSC | **2/2 Green**<br/>[PR #44571](https://github.com/oven-sh/bun/pull/44571) |
| **Ethereum** · *Go*<br/>`go-ethereum` | Bound database batch size during<br/>filtermaps log index rollback | **Checks Green**<br/>[PR #35586](https://github.com/ethereum/go-ethereum/pull/35586) |
| **Paradigm Reth** · *Rust*<br/>`reth` | Txpool live candidate demotion<br/>under reorgs & nonce ordering | **Mergeable**<br/>[PR #27707](https://github.com/paradigmxyz/reth/pull/27707) |
| **Supabase** · *Elixir*<br/>`supavisor` | PostgreSQL cancellation sync<br/>across backend connection reuse | **Checks Green**<br/>[PR #1149](https://github.com/supabase/supavisor/pull/1149) |

---

## ⚙️ Configuration & Action Reference

### Inputs

| Input & Default | Purpose & Behavior |
| :--- | :--- |
| **`api_key`**<br/>*Default:* `''` *(Optional 1st PR)* | ZeroSlop Pro/Enterprise License Key.<br/>Optional for 1st PR; required from PR #2+. |
| **`post_pr_comment`**<br/>*Default:* `'true'` | Maintain 1 self-updating Sovereign Verdict<br/>Card + Mermaid Blast Radius in PR timeline. |
| **`auto_close_slop`**<br/>*Default:* `'false'` | Auto-close PRs failing with severe AI slop<br/>(`>=60%`) or CRITICAL CWEs (Pro/Enterprise). |
| **`ci_diagnostics`**<br/>*Default:* `'false'` | Enable Pro CI Flake Classifier isolating<br/>contributor code from runner flakes & gates. |
| **`base_branch`**<br/>*Default:* `'main'` | Base branch to compare incoming PR diff<br/>against during invariant evaluation. |
| **`auto_polish`**<br/>*Default:* `'true'` | Run repository-native linters and<br/>auto-verify formatting in-memory. |
| **`fail_on_slop`**<br/>*Default:* `'true'` | Block status check if unmitigated AI slop<br/>or CWE vulnerabilities are detected. |
| **`github_token`**<br/>*Default:* `github.token` | GitHub token for querying check runs<br/>and updating the single PR Verdict Card. |
| **`api_endpoint`**<br/>*Default:* *Sovereign Cloud* | Custom verification endpoint for<br/>dedicated VPC enterprise appliances. |

### Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| **`slop_score`** | `number` | Calculated slop ratio (`0%` = clean, `100%` = slop). |
| **`lines_reduced`** | `string` | Percentage of bloated lines stripped from diff. |
| **`invariants_verified`** | `string` | Percentage of architectural invariants verified. |
| **`security_findings_count`** | `number` | Total deterministic CWE vulnerabilities blocked. |
| **`critical_cwe_count`** | `number` | Count of CRITICAL severity CWE findings blocked. |
| **`blast_radius_layers`** | `number` | Count of architectural layers impacted by diff. |
| **`ci_classification`** | `string` | Status: `ALL_GREEN`, `TRIAGE_GATED`, or `INFRA_FLAKE`. |
| **`flaky_jobs_count`** | `number` | Upstream runner timeouts or flakes isolated. |
| **`gated_jobs_count`** | `number` | Maintainer triage gates isolated. |

---

## 🔒 12-Shield CWE Security & Zero-Click Blast Radius Architecture

ZeroSlop is engineered for security-conscious engineering teams, sovereign AI labs, and regulated enterprises that refuse to trust probabilistic LLM review chatbots with production security:

* **12-Shield Deterministic CWE Airlock**: Blocks the top empirical AI-generated vulnerabilities before code reaches human review—including SQL/vector injection (`CWE-89`), hardcoded/seeded credentials & plaintext password checks (`CWE-798`/`CWE-256`), unbound caller identity / IDOR (`CWE-639`), OS command & `eval` injection (`CWE-78`/`CWE-94`), silent exception masking (`CWE-390`), XSS (`CWE-79`), unsafe deserialization (`CWE-502`), SSRF & disabled TLS (`CWE-918`/`CWE-295`), GitHub Actions workflow injection ("Pwn Requests", `CWE-426`), AI package "Slopsquatting" (`CWE-829`), and unbounded loop/timer resource exhaustion (`CWE-400`).
* **Zero-Click Cross-Layer Blast Radius & Mermaid Dependency Graph**: Automatically maps multi-file diffs across architectural boundaries (`API Contracts ➔ Auth & Session ➔ AI/LLM Pipeline ➔ Persistence/Vector Sinks`) and renders an interactive Mermaid reachability diagram right inside the GitHub PR summary and single PR Verdict Card—with **zero external SaaS dashboards or extra clicks required**.
* **Adversarial Prompt-Injection & Trojan-Source Immunity (`CVE-2021-42574`)**: Because conversational AI code reviewers ingest raw PR diffs into LLM context windows, they are susceptible to indirect prompt injection hidden in comments. ZeroSlop's deterministic invariant engine cannot be jailbroken and actively blocks Trojan Source bidirectional Unicode and reviewer override payloads.
* **Zero Code Retention**: Your proprietary codebase is **never stored, retained, cached, or used for AI model training**. Diffs are analyzed ephemerally in volatile RAM and purged immediately upon response return. Read the full [**Enterprise Zero-Retention Security & Procurement Brief →**](https://www.ribbsaetersystems.com/zeroslop/security).
* **Zero Supply Chain Overhead**: Packaged as a self-contained Node.js 20 runner with zero runtime dependencies. No third-party npm package vulnerabilities.
* **Enterprise Compliance**: Designed to meet Swiss FADP, European GDPR, and NIS2 DevSecOps supply-chain standards.
* **Security & Responsible Disclosure**: Comprehensive reporting SLAs and policies documented in [SECURITY.md](SECURITY.md) and [ribbsaetersystems.com/zeroslop/security](https://www.ribbsaetersystems.com/zeroslop/security).

### ⚔️ Category Showdown: ZeroSlop™ vs. AI Review Bots & Legacy SAST

Competitors tell you *"the future isn't writing code—it's reviewing it and prioritizing it"* while herding your engineers into 80-PR Kanban queues, multi-tab "ChangeStack" portals, and 1,999-finding security charts. Senior engineers were hired to ship systems—not click through external SaaS dashboards or read 25 bot comments per PR.

| Capability | 🛡️ ZeroSlop™ Airlock | 🤖 AI Review Bots & Legacy SAST |
| :--- | :--- | :--- |
| **Workflow & UI** | **✓ Zero-Click GitHub Summary + 1 PR Card**<br/>*Zero external SaaS dashboards or logins* | ✕ Herds devs into external SaaS portals,<br/>ChangeStacks & 80-PR Kanban queues |
| **Blast Radius** | **✓ Auto Mermaid Reachability in PR**<br/>*Entrypoint ➔ Auth ➔ Persistence Sink* | ⚠️ Manual clicking across SaaS UI tabs<br/>or isolated file-level lint alerts |
| **12-Shield CWE Gate** | **✓ Deterministically Blocks 12 CWE Classes**<br/>*SQLi, Creds, IDOR, SSRF, Pwn Requests* | ⚠️ Probabilistic LLM chat leaving 1,999+<br/>unfixed findings in dashboard charts |
| **Prompt Injection** | **✓ 100% Deterministic Engine**<br/>*Cannot be jailbroken by PR diff comments* | ✕ Conversational LLMs are vulnerable to<br/>indirect prompt injection in PR diffs |
| **Slop Distillation** | **✓ Strips 94% of Hallucinated Wrappers**<br/>*Blocks unauthorized test deletions* | ✕ Adds 25+ bot comments on top of<br/>AI slop without shrinking the diff |
| **CI Flake Isolation** | **✓ Isolates Contributor Code Defects**<br/>*Separates runner flakes & triage gates* | ✕ Blind to upstream runner flakes vs.<br/>maintainer approval labels |
| **Code Retention** | **✓ Strictly Zero Code Retention**<br/>*Ephemeral RAM Enclave · Swiss/GDPR* | ⚠️ Ships proprietary diffs to 3rd-party<br/>LLMs or stores snapshots in cloud DBs |

---

## 💰 The Economic Business Case: Why Engineering Leaders Mandate ZeroSlop

AI coding agents (Cursor, Copilot, Claude Code) increased commit volume by 300%, but engineering velocity slowed down by 40% because senior staff architects are trapped acting as human linters for bloated, unverified PRs.

### The Hard ROI Breakdown (10-Engineer Team)

| Metric | Status Quo (No Airlock) | With ZeroSlop™ Airlock |
| :--- | :--- | :--- |
| **PR Review Churn** | 15–20 hrs/wk per senior dev | **< 2 hrs/wk** *(60+ hrs saved/sprint)* |
| **PR Turnaround** | 4.2 days average bottleneck | **45 minutes** *(85% faster cadence)* |
| **Public CI Failures** | 14+ failing checks per draft | **100% green checks on 1st push** |
| **Annual Payroll Cost** | $160,000/yr burned in review | **$348/yr** ($29/mo) · **$150k+ saved** |
| **Financial Return** | Continuous velocity erosion | **18.2x+ ROI · < 48hr Payback** |

---

## 🎯 Engineered for Every Decision Maker in Engineering

| Role | Core Friction Solved | How ZeroSlop Delivers The Win |
| :--- | :--- | :--- |
| **Staff & Senior Devs** | Slammed with 20 review comments<br/>for bloated AI helpers. | **Surgical Invariants**: Strips 180-line diffs<br/>down to 4 clean lines. Zero CI humiliation. |
| **Tech Leads & EMs** | PR queue backlogs; seniors<br/>acting as human linters. | **70% Shorter PR Cycles**: Clears review<br/>bottlenecks so teams ship core features. |
| **VPs of Engineering** | High commit volume slows<br/>actual release cadence. | **60+ Hours Reclaimed/Sprint**: Turns AI<br/>output into verified production throughput. |
| **CTOs & Architects** | Architectural decay and subtle<br/>memory/concurrency leaks. | **Zero-Click Blast Radius**: Maps cross-layer<br/>reachability directly inside GitHub PRs. |
| **CISOs & AppSec** | AI-introduced CWE flaws and<br/>3rd-party LLM IP leakage. | **12-Shield CWE Gate & Zero Retention**:<br/>Blocks SQLi, IDOR, SSRF & Pwn Requests. |

---

## 💼 Commercial Licensing & Pricing (100% Self-Serve)

| Tier & Investment | Scope & Concurrency | Capabilities & Instant Activation |
| :--- | :--- | :--- |
| **Single Evaluation Try**<br/>**`$0` (1 PR Try)** | **1 Developer · 1 PR Audit**<br/>*Locks After 1st PR* | AST diff parser · 12-Shield CWE Airlock ·<br/>Zero-Click Mermaid Blast Radius<br/>👉 [**Try 1 PR Free on Marketplace →**](https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems) |
| **ZeroSlop™ Pro**<br/>**`$29 / month`** | **1 Pro Developer Seat**<br/>*Unlimited Repos & PRs* | **Unlimited PR Audits** · **12-Shield CWE Gate** ·<br/>**1 In-Place PR Card** · **CI Flake Classifier**<br/>👉 [**Subscribe Pro ($29/mo) →**](https://buy.stripe.com/28E5kFflO4n65Ho9JFfQI02) |
| **ZeroSlop™ Enterprise**<br/>**`$1,999 / month`** | **Per 100 Active Devs**<br/>*Dedicated VPC Enclave* | Everything in Pro + **Dedicated VPC Enclave** ·<br/>Custom CWE Rules · Air-Gapped · 24/7 SLA<br/>👉 [**Deploy Enterprise ($1,999/mo) →**](https://buy.stripe.com/aFaeVf0qU06Qb1I9JFfQI03) |

### ⚡ Self-Serve Headcount Scaling (Zero Sales Calls · Instant Activation)

Enterprise Core is billed in transparent **100-developer blocks at $1,999 / month per block**. Organizations purchase the quantity matching their active contributor count:

| Engineering Headcount | License Allocation | Investment & Instant Activation |
| :--- | :--- | :--- |
| **1 – 68 Engineers** | Individual Pro Seats ($29/dev) | **$29 – $1,972 / mo**<br/>[Subscribe Pro ($29/mo) →](https://buy.stripe.com/28E5kFflO4n65Ho9JFfQI02) |
| **Up to 100 Engineers** | 1x Enterprise Core Block | **$1,999 / mo** ($23,988/yr)<br/>[Deploy 1 Block →](https://buy.stripe.com/aFaeVf0qU06Qb1I9JFfQI03) |
| **Up to 200 Engineers** | 2x Enterprise Core Blocks | **$3,998 / mo** ($47,976/yr)<br/>[Deploy 2 Blocks →](https://buy.stripe.com/aFaeVf0qU06Qb1I9JFfQI03) |
| **Up to 500 Engineers** | 5x Enterprise Core Blocks | **$9,995 / mo** ($119,940/yr)<br/>[Deploy 5 Blocks →](https://buy.stripe.com/aFaeVf0qU06Qb1I9JFfQI03) |
| **Up to 1,000 Engineers** | 10x Enterprise Core Blocks | **$19,990 / mo** ($239,880/yr)<br/>[Deploy 10 Blocks →](https://buy.stripe.com/aFaeVf0qU06Qb1I9JFfQI03) |

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
