# Strategic Think Skill (`strategic-think`)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Compatibility](https://img.shields.io/badge/Platforms-Antigravity%20%7C%20Claude%20%7C%20GitHub%20Copilot-green)](SKILL.md)
[![Frameworks](https://img.shields.io/badge/Strategic%20Frameworks-15%20Methodologies-purple)](references/frameworks.md)

An agentic skill that elevates AI models from reactive advice-givers into elite strategic advisors. 

Rather than jumping directly to generic platitudes, `strategic-think` enforces an interactive discovery phase, diagnoses the underlying core constraint (the "Crux"), selects complementary analytical frameworks, and delivers an execution-ready, stress-tested strategic plan with explicit trade-offs and pre-mortems.

---

## Table of Contents

- [Why Strategic Think?](#why-strategic-think)
- [How It Works: The 3-Phase Engine](#how-it-works-the-3-phase-engine)
- [Strategic Thinking Techniques Included](#strategic-thinking-techniques-included)
- [Repository Structure](#repository-structure)
- [Cross-Platform Installation & Usage](#cross-platform-installation--usage)
  - [Google Antigravity](#1-google-antigravity)
  - [Anthropic Claude (Claude Code & Claude.ai)](#2-anthropic-claude-claude-code--claudeai)
  - [GitHub Copilot Chat (VS Code & CLI)](#3-github-copilot-chat-vs-code--cli)
- [Example Interaction Walkthrough](#example-interaction-walkthrough)
- [Changelog](#changelog)

---

## Why Strategic Think?

Most AI responses to strategic queries suffer from three classic failure modes:
1. **Premature Solutioning:** Answering complex business or architectural dilemmas immediately without understanding the specific operating environment or constraints.
2. **Generic Lists ("Bad Strategy"):** Providing a 20-point checklist of things that "could" be done without forcing hard choices or defining what *not* to do.
3. **Optimism Bias:** Omitting pre-mortems, leading indicators, or objective kill criteria.

`strategic-think` turns your AI assistant into a disciplined thought partner. It diagnoses before prescribing, leverages 15 battle-tested decision frameworks, and produces actionable strategy kernels that maximize the probability of success.

---

## How It Works: The 3-Phase Engine

```
  ┌─────────────────────────────────────────────────────────────┐
  │ Phase 1: Strategic Discovery (Diagnostic Questioning)        │
  │ • Probes goal, bottlenecks, constraints, runway, and risks │
  │ • Supports "Quick Mode" for fully detailed prompts          │
  └──────────────────────────────┬──────────────────────────────┘
                                 │
                                 ▼
  ┌─────────────────────────────────────────────────────────────┐
  │ Phase 2: Diagnosis & Framework Selection                    │
  │ • Cynefin domain classification (Simple/Complex/Chaotic)    │
  │ • Crux identification (Rumelt's Kernel)                     │
  │ • Selects 2-4 complementary frameworks from reference guide │
  └──────────────────────────────┬──────────────────────────────┘
                                 │
                                 ▼
  ┌─────────────────────────────────────────────────────────────┐
  │ Phase 3: Actionable Strategy & Stress-Tested Execution      │
  │ • The Crux & Situation Diagnosis                            │
  │ • Guiding Policy & Non-Goals (Strict Trade-Offs)            │
  │ • Coherent Actions & Asymmetric Bets                        │
  │ • Pre-Mortem & Red-Team Stress Test                         │
  │ • Kill Criteria, Leading Indicators & 48-Hour Next Step     │
  └─────────────────────────────────────────────────────────────┘
```

### Phase 1: Strategic Discovery (Interactive Questioning)
When presented with a strategic dilemma, the skill halts premature execution and asks 4 to 6 sharp diagnostic questions across:
- **Winning Definition & Desired Outcome:** Concrete target metrics, qualitative goals, and time horizon.
- **Current Reality & Bottleneck:** What single constraint or resistance is holding back progress?
- **Asymmetric Constraints & Resources:** Available capital, team capabilities, technical debt, and political capital.
- **External Landscape & Competitive Dynamics:** Inertia, competitive moat, supplier/vendor leverage, or regulatory factors.
- **Previous Attempts & Lessons Learned:** What has already been tried, what failed, and why?
- **Failure Tolerance:** Reversible (Type 2) vs irreversible (Type 1) decision boundary.

*Note: If the user provides comprehensive context upfront or explicitly requests immediate execution, the skill enters **Quick Mode** and executes Phase 2 and Phase 3 directly.*

### Phase 2: Diagnosis & Framework Selection
The skill classifies the problem context using the **Cynefin Framework** and isolates **The Crux** (the most critical, conquerable sub-problem). It then selects 2 to 4 complementary frameworks tailored to the challenge from the included [references/frameworks.md](references/frameworks.md).

### Phase 3: Strategic Approach & Execution Plan
The final output is structured into a decisive strategic deliverable:
1. **The Crux (Situation Diagnosis):** The fundamental tension or leverage point.
2. **Guiding Policy & Trade-Offs:** The directional philosophy chosen, explicitly stating what the team **will NOT do**.
3. **Coherent Action Plan:** Sequenced actions that mutually reinforce each other, prioritizing high-leverage and asymmetric bets.
4. **Pre-Mortem & Red-Team Stress Test:** Anticipating 3 failure modes 12–18 months in the future with immediate preventative countermeasures.
5. **Leading Indicators & Kill Criteria:** Early warning metrics and predefined conditions for when to pivot or abandon.
6. **Immediate 48-Hour Next Step:** The single next concrete action to unlock forward momentum.

---

## Strategic Thinking Techniques Included

The skill incorporates 15 world-class strategic frameworks documented in detail in [references/frameworks.md](references/frameworks.md):

| Framework | Core Focus / Domain | When to Apply | Key Diagnostic Question |
| :--- | :--- | :--- | :--- |
| **[Cynefin Framework](references/frameworks.md#4-cynefin-framework)** | Domain Classification | High ambiguity, system categorization | *What kind of problem space are we in (Clear, Complicated, Complex, Chaotic)?* |
| **[Rumelt's Strategy Kernel](references/frameworks.md#1-rumelts-strategy-kernel--the-crux)** | Strategy Coherence & Crux | Core strategic design, resource allocation | *What is the fundamental crux, and do our actions mutually reinforce our guiding policy?* |
| **[Playing to Win](references/frameworks.md#3-playing-to-win)** | Market Competition | Business unit strategy, positioning | *Where will we play, how will we win, and what capabilities are non-negotiable?* |
| **[Wardley Mapping](references/frameworks.md#2-wardley-mapping)** | Landscape & Tech Evolution | Cloud/platform architecture, build vs buy | *How are components evolving from Genesis to Commodity, and where will value pool?* |
| **[Theory of Constraints](references/frameworks.md#8-theory-of-constraints-toc)** | Throughput & Bottlenecks | Engineering velocity, operations, pipelines | *What single constraint limits the throughput of the entire system?* |
| **[OODA Loop](references/frameworks.md#9-ooda-loop)** | Dynamic Execution | Fast-moving markets, crisis management | *How do we accelerate our Observe-Orient-Decide-Act tempo faster than the competition?* |
| **[Pre-Mortem & Red Teaming](references/frameworks.md#5-pre-mortem--red-teaming)** | Failure Prevention | Pre-launch, major architectural shifts | *Assuming this initiative fails catastrophically in 18 months, what caused it?* |
| **[Inversion Thinking](references/frameworks.md#6-inversion)** | Avoiding Stupidity | Risk management, foundational design | *How could we guarantee failure, and how do we systematically avoid those paths?* |
| **[Second-Order Thinking](references/frameworks.md#7-second-order--nth-order-thinking)** | Unintended Consequences | Policy changes, incentives, system changes | *And then what? What are the secondary effects 6 to 24 months out?* |
| **[Asymmetric Bets / Barbell](references/frameworks.md#10-asymmetric-bets--barbell-strategy)** | Capital & Resource Risk | High uncertainty, R&D investments | *How do we strictly cap downside while exposing ourselves to open-ended upside?* |
| **[Bayesian Updating & EV](references/frameworks.md#11-expected-value-ev--bayesian-updating)** | Probabilistic Decisions | Forecasting, feature prioritization | *What is the expected value, and how should new evidence update our priors?* |
| **[First Principles Thinking](references/frameworks.md#12-first-principles-thinking)** | Deep Innovation | Cost restructuring, breakthrough tech | *What are the foundational truths stripped of analogy and industry convention?* |
| **[Jobs-to-be-Done (JTBD)](references/frameworks.md#13-jobs-to-be-done-jtbd)** | Customer Demand | Product strategy, feature definition | *What core progress is the user hiring our product to achieve?* |
| **[Blue Ocean Strategy](references/frameworks.md#14-blue-ocean-strategy--value-innovation)** | Value Innovation | Breaking commodity traps | *What can we Eliminate, Reduce, Raise, and Create to escape price competition?* |
| **[Real Options Strategy](references/frameworks.md#15-real-options--strategic-optionality)** | Staged Commitments | Multi-year roadmaps, high-stakes bets | *What small investment today buys the right—not the obligation—to act tomorrow?* |

---

## Repository Structure

```text
strategic-think-skill/
├── SKILL.md                                 # Core agent skill instruction file (platform-agnostic)
├── README.md                                # Comprehensive documentation & user guide
├── references/
│   └── frameworks.md                        # In-depth guide to all 15 strategic frameworks & matrix
└── .github/
    └── prompts/
        └── strategic-think.prompt.md        # GitHub Copilot Chat prompt template / slash command
```

---

## Cross-Platform Installation & Usage

`strategic-think` is built to run natively across modern AI agent environments without proprietary vendor locking.

### 1. Google Antigravity

Antigravity automatically discovers skills defined with standard YAML frontmatter in workspace and configuration roots.

#### Option A: Workspace Installation (Project-Specific)
Clone or copy this skill into your repository's `.agents/skills/` directory:
```bash
mkdir -p .agents/skills/strategic-think
cp -r /path/to/strategic-think-skill/* .agents/skills/strategic-think/
```

#### Option B: Global Configuration (Available Across All Workspaces)
Install the skill into your global Antigravity config directory:
```bash
# Linux / macOS
mkdir -p ~/.gemini/config/skills/strategic-think
cp -r /path/to/strategic-think-skill/* ~/.gemini/config/skills/strategic-think/

# Windows (PowerShell)
New-Item -ItemType Directory -Force -Path "$HOME\.gemini\config\skills\strategic-think"
Copy-Item -Recurse -Force "C:\path\to\strategic-think-skill\*" "$HOME\.gemini\config\skills\strategic-think\"
```

#### Antigravity Usage
Antigravity activates the skill automatically when relevant queries are detected, or you can trigger it directly:
> *"I need to develop a strategic plan for migrating our monolithic platform to microservices while maintaining 99.99% uptime."*

---

### 2. Anthropic Claude (Claude Code & Claude.ai)

Claude Code supports project-level and user-level skills adhering to the Agent Skills standard.

#### Option A: Claude Code Global Installation
```bash
# Linux / macOS
mkdir -p ~/.claude/skills/strategic-think
cp -r /path/to/strategic-think-skill/* ~/.claude/skills/strategic-think/

# Windows (PowerShell)
New-Item -ItemType Directory -Force -Path "$HOME\.claude\skills\strategic-think"
Copy-Item -Recurse -Force "C:\path\to\strategic-think-skill\*" "$HOME\.claude\skills\strategic-think\"
```

#### Option B: Claude Code Project Installation
Place the directory inside `.claude/skills/` in your workspace:
```bash
mkdir -p .claude/skills/strategic-think
cp -r /path/to/strategic-think-skill/* .claude/skills/strategic-think/
```

#### Option C: Claude.ai Web / Projects
1. Create a new Claude Project in [claude.ai](https://claude.ai).
2. Upload [SKILL.md](SKILL.md) and [references/frameworks.md](references/frameworks.md) to the Project Knowledge.
3. Paste the contents of `SKILL.md` into the Project Custom Instructions.

#### Claude Usage
Run within Claude Code:
```bash
claude "Let's think strategically about expanding our product into EMEA enterprise accounts."
```

---

### 3. GitHub Copilot Chat (VS Code & CLI)

GitHub Copilot Chat supports workspace skills and prompt templates.

#### Installation
1. Copy the skill into your project's `.github/skills/` directory:
   ```bash
   mkdir -p .github/skills/strategic-think
   cp -r /path/to/strategic-think-skill/* .github/skills/strategic-think/
   ```
2. The prompt wrapper is pre-configured at [`.github/prompts/strategic-think.prompt.md`](.github/prompts/strategic-think.prompt.md).

#### GitHub Copilot Usage
In VS Code Copilot Chat, invoke the prompt file or mention the skill:
```text
/strategic-think We are deciding between building an in-house vector search pipeline vs adopting managed cloud vector databases.
```

---

## Example Interaction Walkthrough

Here is a realistic example demonstrating the interactive discovery and structured strategic output.

### 1. User Dilemma
> **User:** *"We are an 18-person B2B developer-tools startup with $2.5M in seed funding and 14 months of runway. We're getting inbound interest from two Fortune 500 banks wanting custom on-prem deployments, but our self-serve cloud product is just starting to see organic traction (15% MoM growth). Should we pivot our roadmap to build enterprise on-prem capabilities?"*

---

### 2. Phase 1: Interactive Diagnostic Response
The skill does not reply with *"Yes, enterprise deals bring revenue"* or *"No, stay focused on cloud"*. Instead, it asks:

> **Agent:**
> *"Before formulating our strategic recommendation, let's clarify key operational and financial realities:*
>
> 1. **Deal Economics & Commitments:** *Are the two banks willing to sign binding paid pilot agreements (e.g., $150k+ ACV each) with upfront milestone payments, or are these exploratory RFPs?*
> 2. **Engineering Tax:** *What specific on-prem requirements do they mandate (air-gapped networks, FIPS compliance, custom RBAC/LDAP)? How many engineers would be diverted for 6 months?*
> 3. **Self-Serve Velocity:** *What is your current self-serve Net Retention Rate and monthly churn? Is self-serve growth constrained by lack of features or lack of distribution?*
> 4. **Runway Sensitivity:** *At your current burn rate ($180k/mo), does taking on enterprise support shorten or extend your runway without a Series A?*
> 5. **Long-Term Winning Identity:** *In 3 years, are you fundamentally a self-serve developer platform (Datadog/Postman) or high-touch enterprise software (Palantir)?*"

---

### 3. User Brief Answer
> **User:** *"1. One bank offered a $180k paid pilot; the other is talking unpaid PoC. 2. Air-gapped Kubernetes + custom SSO; would consume 3 of our 5 backend engineers for 4 months. 3. Self-serve churn is low (1.2%), growth is distribution-constrained. 4. Unpaid PoCs burn runway; paid pilot extends runway by 1 month. 5. Long-term we want to be a self-serve platform with an enterprise tier later."*

---

### 4. Phase 2 & 3: Strategic Output

The agent synthesizes the situation using **Rumelt's Kernel**, **Barbell Strategy**, and **Theory of Constraints**:

```markdown
### Situation Diagnosis & The Crux
- **Domain:** Complex / Complicated Boundary (Cynefin)
- **The Crux:** Diverting 60% of core backend engineering into bespoke on-premise infrastructure risks stalling your organic 15% MoM self-serve distribution before reaching product-market velocity, while unpaid/bespoke pilots will accelerate cash depletion.

### Guiding Policy & Core Trade-Offs
- **Policy:** Protect self-serve product momentum as primary value engine; treat enterprise as an asymmetric revenue hedge only if fully customer-funded and standardized via containerized deployment.
- **Explicit Trade-Off (What We Will NOT Do):**
  - We will NOT build custom one-off codebranches or accept unpaid proof-of-concepts.
  - We will NOT support air-gapped installations that require bespoke manual patching.

### Coherent Action Plan
1. **The Paid Barbell Pilot (Asymmetric Bet):** Counter-offer Bank A with a standardized "Customer-Hosted Enterprise Edition" deployed via Helm charts. Contractually require 50% upfront payment ($90k) and explicitly scope out custom code branches.
2. **Decline Unpaid Distraction:** Politely decline Bank B's unpaid PoC with an offer to join the hosted private beta.
3. **Dedicated Contractor Shield:** Use a portion of Bank A's upfront payment to contract a dedicated Kubernetes deployment specialist rather than derailing the 3 core platform engineers.
4. **Self-Serve Growth Investment:** Keep the core engineering team focused on self-serve onboarding friction to solve the distribution bottleneck.

### Pre-Mortem & Red-Team Stress Test
- **Failure Mode 1 (Custom Branch Trap):** Bank A demands bespoke auditing integrations, trapping 2 engineers indefinitely.
  - *Countermeasure:* Contractual SLA specifying support only for standard container images; custom work billed at prohibitive T&M rates ($350/hr).
- **Failure Mode 2 (Self-Serve Growth Stalls):** Self-serve MoM growth slips from 15% to 4% due to neglected roadmap.
  - *Countermeasure:* Cap total internal engineering time spent on Bank A at 20% max (1 engineer equivalent).

### Leading Indicators & Kill Criteria
- **Kill Criterion:** If Bank A fails to sign the paid agreement within 30 days or rejects the standardized container distribution, terminate enterprise negotiations immediately and revert 100% focus to self-serve.
- **Leading Indicator:** Self-serve weekly signups must stay above +10% MoM throughout Q2.

### 48-Hour Next Step
Draft a 1-page Terms Sheet for Bank A specifying: Standard Helm-based deployment, $180k ACV ($90k upfront), no bespoke branch maintenance, 30-day acceptance window.
```

---

## Changelog

All notable changes to this project are documented in this section.
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) and [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

### [1.0.0] - 2026-11-13

#### Added
- Initial release of the `strategic-think` cross-platform agent skill.
- Core 3-Phase Strategic Engine:
  - Phase 1: Strategic Discovery & Diagnostic Questioning (with Quick Mode escape hatch).
  - Phase 2: Diagnosis & Framework Selection (Cynefin Domain Classification + Rumelt's Crux).
  - Phase 3: Actionable Strategic Synthesis with Guiding Policies, Coherent Actions, Pre-Mortem stress tests, leading indicators, and 48-hour next steps.
- Comprehensive [references/frameworks.md](references/frameworks.md) manual featuring 15 strategic frameworks:
  - Rumelt’s Strategy Kernel & Crux
  - Wardley Mapping
  - Playing to Win (Lafley & Martin)
  - Cynefin Framework (Dave Snowden)
  - Pre-Mortem & Red Teaming (Gary Klein)
  - Inversion Thinking (Jacobi / Munger)
  - Second-Order Thinking
  - Theory of Constraints (Goldratt)
  - OODA Loop (John Boyd)
  - Asymmetric Bets & Barbell Strategy (Nassim Taleb)
  - Expected Value & Bayesian Updating
  - First Principles Thinking
  - Jobs-to-be-Done (Clayton Christensen)
  - Blue Ocean / Value Innovation (Kim & Mauborgne)
  - Real Options & Strategic Optionality
- Cross-platform installation and execution support for:
  - Google Antigravity (`~/.gemini/config/skills/` and `.agents/skills/`)
  - Anthropic Claude Code & Claude.ai (`~/.claude/skills/`, `.claude/skills/`, and Project Knowledge)
  - GitHub Copilot Chat (`.github/skills/` and `.github/prompts/strategic-think.prompt.md`)
- Complete end-to-end B2B startup interaction walkthrough example.
