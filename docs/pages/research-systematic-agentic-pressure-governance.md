---
layout: default
title: Governance Risks - Systematic Agentic Pressure - Research - selfdriven AI
permalink: /research/systematic-agentic-pressure/governance
---

## Governance Risks due to Systematic AI-automated Attack Pressure

### What Changes Now

**AI-enabled attack agents don’t “create a new threat category” — they compress time and scale**.  

What used to be a weeks-long campaign can become a continuous, automated loop: probe → learn → adapt → re-attack.

For boards, the practical implication is simple:

**Central cloud is a trust concentrator.**  
If identity/control-plane is compromised, the blast radius is cross-system and often cross-vendor.

Recent national and standards bodies are explicitly treating AI (including agents) as a cybersecurity risk driver that requires updated controls and governance.

- [nvlpubs.nist.gov](https://nvlpubs.nist.gov/nistpubs/ir/2025/NIST.IR.8596.iprd.pdf)

---

### Why cloud hubs are disproportionately exposed

**Cloud concentrates:**

- Identity (SSO, OAuth tokens, service accounts)
- Control planes (IAM, org policies, Kubernetes, serverless)
- Supply chain (CI/CD, registries, artifacts)
- High-value data + logs

So a “minor” compromise (token theft, CI runner access, mis-scoped role) can become:
- rapid privilege escalation,
- lateral movement across accounts/projects,
- persistence via federated identity,
- and high-confidence exfiltration using “normal” APIs.

Threat reporting shows material scale and cost impacts already at national level (e.g., high report volume and rising average losses).

- [Cyber Security Australia](https://www.cyber.gov.au/sites/default/files/2025-10/Annual%20Cyber%20Threat%20Report%202024-25%20factsheet%20for%20businesses%20and%20organisations.pdf)

---

### Board-level risk statements (how this hits the business)

#### 1) Operational continuity risk (outage + lockout)
**Scenario:** attacker gains admin identity or modifies org/IAM policies.  
**Impact:** services disrupted, production locked, recovery slowed (because access tooling is also cloud-based).  
**Board question:** “Can we recover if the cloud admin plane is hostile for 72 hours?”

#### 2) Systemic supply-chain risk (correlated failure)
**Scenario:** CI/CD compromise, poisoned artifacts, dependency injection, registry abuse.  
**Impact:** many systems infected at once; remediation requires rebuild/redeploy at scale.

#### 3) Data protection & regulatory risk (exfiltration that looks normal)
**Scenario:** attacker uses legitimate APIs (export/snapshot/copy) after identity compromise.  
**Impact:** not just breach cost—secondary harm, notification obligations, loss of trust.

#### 4) Financial risk (economic DoS / cost attack)
**Scenario:** attacker drives serverless/GPU/egress usage to inflate bills or exhaust quotas.  
**Impact:** real cash burn; pressure to disable controls “to restore service.”

#### 5) Governance risk (decision speed mismatch)
**Scenario:** attacker iterates faster than human response loops.  
**Impact:** incident decisions degrade; “manual approval everywhere” becomes impossible.

ENISA’s threat landscape work highlights the increasing systemic nature of attacks and supply-chain dependency effects across sectors.

- [enisa.europa.eu](https://www.enisa.europa.eu/sites/default/files/2025-10/ENISA%20Threat%20Landscape%202025.pdf)

---

### Top 5 controls that reduce expected loss fastest (board oversight set)

1) **Phishing-resistant MFA / passkeys for all admins + Tier-0 accounts**
   - eliminate weakest path into the control plane  
   - measure: % admin accounts passkey-enabled; % legacy MFA eliminated

2) **Short-lived credentials + minimal scopes (no long-lived keys)**
   - move workloads/CI to OIDC federation where possible  
   - measure: # long-lived keys; mean token lifetime; wildcard policy count

3) **Guardrails in code: policy-as-code + drift detection**
   - prevent “permission sprawl” and configuration regression  
   - measure: drift MTTR; blocked insecure changes; privileged role growth

4) **Supply-chain hardening: signed builds + provenance + protected pipelines**
   - treat CI/CD as production infrastructure  
   - measure: % signed artifacts; pipeline change controls; secret exposure events

5) **Immutable evidence: separate-account logging + tamper alarms**
   - assume attackers will try to blind you  
   - measure: logging coverage; alerts on log disable/delete; retention integrity

NIST’s preliminary Cybersecurity Framework Profile for AI emphasizes securing AI systems, AI-enabled defense, and resilience to AI-enabled attacks—useful framing for governance and control selection.  [nvlpubs.nist.gov](https://nvlpubs.nist.gov/nistpubs/ir/2025/NIST.IR.8596.iprd.pdf)

---

### “Minimum viable board dashboard” (monthly)
- **Tier-0 identity posture:** passkey coverage, break-glass drills completed, privileged role count
- **Key risk exposure:** long-lived keys, wildcard IAM policies, external-facing admin surfaces
- **Supply chain integrity:** signed build coverage, critical pipeline changes, SBOM/provenance coverage
- **Detection survivability:** immutable log coverage, log disruption events, incident MTTD/MTTR
- **Cost-attack controls:** quota configuration coverage, abnormal spend alerts, egress caps

---

### Immediate board actions (30–60 days)
1) Approve a **Tier-0 Identity Program** (admins + CI/CD + cloud org owners).  
2) Require a **cloud blast-radius exercise**: “stolen admin token” tabletop + restore test.  
3) Mandate **supply-chain protections** on top 10 production services (signed builds + protected pipelines).  
4) Fund **immutable logging + response automation** with human gating.  
5) Require a written policy: **“No long-lived keys in production by default.”**

CISA’s joint guidance explicitly includes AI agents in the security integration scope—use it as an external anchor for internal requirements.

- [cisa.gov](https://www.cisa.gov/news-events/alerts/2025/12/03/cisa-australia-and-partners-author-joint-guidance-securely-integrating-artificial-intelligence)

---

# Magnitude of Cloud Risk Increase (2023 → 2025)  
## Board-level assessment of AI-automated attack escalation

---

## Executive summary

Compared to approximately two years ago, the **effective risk exposure of central cloud services has increased by roughly 5×–20×**.

This is **not** because attackers suddenly discovered radically new exploits.  
It is because **AI-driven automation compresses time, scales coverage, and removes human friction** from the attack lifecycle.

In practical terms:
> Failures that were once *local, slow, and containable* are now more likely to be *systemic, fast, and compounding*.

## What fundamentally changed in two years

### 1. Kill-chain compression (≈ 5–10× faster)

**2023**
- Reconnaissance, phishing, exploitation were semi-manual
- Campaigns had pauses (human review, handoffs)
- Attackers optimised per-target

**2025**
- AI agents run continuous recon → exploit → adapt loops
- Payloads and paths mutate automatically
- Thousands of targets tested in parallel

**Impact**
- Defender response windows shrink from hours/days to minutes/hours
- Human approval cycles are outpaced

### 2. Attack surface coverage expansion (≈ 10×)

**2023**
- Common ports, known misconfigurations
- Selective API probing

**2025**
- Full API graph enumeration
- Permission-shape discovery (unusual scope combinations)
- Continuous re-checking as infrastructure drifts

**Impact**
- “Edge cases” are now systematically found
- Temporary mistakes become exploitable events

### 3. Identity compromise amplification (≈ 5× impact per failure)

**2023**
- Credential theft expensive and noisy
- MFA bypass attempts unsophisticated

**2025**
- Personalised, context-aware phishing
- Automated OAuth token abuse and replay
- Statistical optimisation of MFA fatigue and consent attacks

**Impact**
- Single identity failure more likely to cascade into control-plane access

### 4. Supply-chain blast-radius growth (≈ 10–20×)

**2023**
- Supply-chain attacks required deep access or luck
- Limited lateral scaling

**2025**
- AI agents generate credible PRs, packages, config changes
- CI/CD systems probed continuously
- One weak repo can affect many services

**Impact**
- Correlated, multi-system failure risk rises sharply

### 5. Persistence and patience (qualitative step-change)

**New condition**
- Attack agents do not “finish”
- They watch indefinitely
- They re-test after every deploy
- They exploit momentary openings (debug flags, temp roles, rushed fixes)

**Impact**
- Security must be continuous, not periodic
- “Mostly secure” no longer holds

---

## Risk multiplier model (board-usable)

Risk can be approximated as:

Risk ≈ Likelihood × Impact

| Dimension | ~2023 | ~2025 | Multiplier |
|---------|------|-------|-----------|
Likelihood of compromise | Medium | High | ~3–5× |
Speed to full compromise | Hours–days | Minutes–hours | ~5–10× |
Blast radius | Single system | Multi-system / tenant | ~3–5× |
Detection lag | Manageable | Often outpaced | ~2–3× |

**Combined (non-linear) effect:**  
**~5×–20× increase in realised risk exposure**

---

## Why this is non-linear

These factors **compound**:
- Faster compromise means less containment
- Wider blast radius increases impact per incident
- Continuous probing increases probability of eventual success

Small control gaps now produce disproportionately large outcomes.

---

## Core board takeaway

> Two years ago, cloud security incidents were usually **local and recoverable**.  
> Today, the same failures are more likely to be **systemic, fast-moving, and financially material**.

This is why modern cloud governance must treat:
- **Identity** as Tier-0 infrastructure  
- **CI/CD and APIs** as production attack surfaces  
- **Containment and resilience** as primary objectives, not just prevention  

---

## Related
- [Systematic Agentic Pressure](/research/systematic-agentic-pressure)