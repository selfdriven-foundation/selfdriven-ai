---
layout: selfdriven
title: Situational-awareness-framework - selfdrivenAI
permalink: /situational-awareness-framework/organisations/deep-analysis
---
# The Emerging Organisation

## Machine in Control, Human in Context

**A deep analysis of Level 3 in the selfdriven Situational Awareness Framework for Organisations — and its implications for governance, identity, and human purpose**

- [selfdriven.foundation](https://selfdriven.foundation)
- [selfdriven.ai/research](https://selfdriven.au/research)
- March 2026
- Classification: Public

## Abstract

This paper examines the selfdriven Situational Awareness Framework for Organisations, a three-level maturity model that maps the evolving relationship between human decision-makers and AI systems. While Levels 1 and 2 describe familiar territory — tool-centric operations and collaborative human-machine workflows — Level 3, designated "Emerging: Machine in Control, Human in Context," represents a fundamentally different organisational paradigm. Drawing on Endsley's foundational three-level situation awareness model (perception, comprehension, projection), the Human Conductor model pioneered by the selfdriven Foundation, and contemporary research in human-AI teaming, this paper provides an in-depth analysis of what Level 3 means in practice: how organisations transition to it, what governance architectures sustain it, and why cryptographic identity infrastructure — specifically KERI/ACDC self-sovereign identity — is essential to making it work safely.

## 1. Introduction: The Situational Awareness Imperative

The concept of situational awareness (SA) has deep roots in human factors research, originating in aviation and military command-and-control contexts. Endsley's widely adopted three-level SA model defines awareness as a progression from perceiving elements in the environment (Level 1), through comprehending their meaning in relation to goals (Level 2), to projecting future states of the system (Level 3). This model has proven remarkably durable, informing decades of research in autonomous systems, cybersecurity, robotics, and human-AI teaming.

The selfdriven Situational Awareness Framework for Organisations adapts this foundational SA concept into an organisational maturity model — one that describes not the awareness of an individual operator, but the collective posture of an entire enterprise toward AI-driven decision-making. The framework's three levels — Legacy, Transitional, and Emerging — chart a progression from human-controlled, tool-centric operations through collaborative human-machine workflows to a paradigm where machines execute adaptive strategies autonomously within human-defined ethical boundaries.

The accompanying "before and after" diagram published at selfdriven.ai visualises this progression as a shift in the locus of control: from humans issuing instructions to tools, through humans co-deciding with machines, to humans defining context, values, and purpose while machines handle execution, adaptation, and optimisation at scale. This paper provides an overview of all three levels before dedicating its core analysis to Level 3 — the Emerging state — where the most profound organisational, ethical, and technical questions arise.

<img src="/assets/img/selfdriven-ai-before-after-situational-awareness-level.png" style="margin-top:20px; border-radius: 12px; width:100%; max-width: 800px;">

## 2. The Three Levels: An Overview

| Level | Situation | Core Characteristic | Strategic Risk | Horizon |
|-------|-----------|---------------------|----------------|---------|
| **1** | Legacy: Human-in-Control | Humans make all decisions; tools follow instructions | Obsolescence, bottlenecks | Now–3 years |
| **2** | Transitional: Human + Machine | Shared decision-making; humans interpret and challenge AI outputs | Bias, algorithmic drift | Now–5 years |
| **3** | Emerging: Machine-in-Control | Machines execute adaptively within human-defined ethical boundaries | Alignment loss, agency erosion | Now for Long-term |

### 2.1 Level 1 — Legacy: "Human in Control"

The defining phrase of Level 1 is *"We make all the decisions. The tools just do what we say."* Technology is positioned as a support function. Decision-making is manual, hierarchical, and slow. AI, if considered at all, is approached with suspicion or active avoidance. Data is siloed and departmentally owned. Innovation means incremental improvement, not transformation.

The strategic risk at Level 1 is obsolescence. Human bottlenecks constrain the speed of adaptation. Efficiency-focused organisations fall behind those that are insight-driven. The relevance horizon is estimated at two to three years before operations feel outdated. Evolution from Level 1 requires building AI literacy across leadership and staff, initiating data integration and cross-department collaboration, and piloting decision-support AI to augment — not replace — human expertise.

### 2.2 Level 2 — Transitional: "Human + Machine Collaboration"

The defining phrase of Level 2 is *"We decide with the machine, not just through it."* AI is treated as a partner in decision-making. Staff are trained to interpret and challenge AI outputs. Data becomes a shared strategic asset. Decisions migrate closer to where data lives. Governance emphasises explainability and bias mitigation.

This level aligns closely with contemporary research on human-AI teaming (HAT), where shared situation awareness between human and AI teammates is critical for effective performance. The research literature emphasises the need for transparency, explainability, and appropriate levels of trust — precisely the concerns that characterise Level 2 organisations. The strategic risk here is over-trust: the "AI says so" problem where unexamined algorithmic outputs are accepted without critical evaluation.

The relevance horizon at Level 2 is three to five years with adaptive governance. Evolution toward Level 3 requires establishing AI ethics and decision-oversight frameworks, tracking decision provenance (why and how choices are made), and forming cross-functional teams to co-design human-machine workflows.

### 2.3 Level 3 — Emerging: "Machine in Control / Human in Context"

The defining phrase of Level 3 is *"We define direction, not decisions."* This level is the primary subject of this paper and is examined in depth in the sections that follow.



## 3. Level 3: The Emerging Organisation

Level 3 represents a qualitative shift in organisational ontology, not merely a quantitative improvement in AI adoption. At this level, machines execute adaptive strategies within human-defined boundaries. Humans focus on values, ethics, and direction-setting. Continuous AI governance monitors drift and outcomes. The organisation behaves like an ecosystem, not a strict hierarchy. Culture prizes stewardship, creativity, and alignment.

### 3.1 The Inversion of the Decision Hierarchy

In traditional organisations (Level 1), the decision hierarchy flows downward: leadership sets strategy, middle management translates it into tactics, and operational staff execute through tools. AI enters this hierarchy in Level 2 as a co-participant at the tactical and operational layers. But Level 3 inverts the paradigm: machines occupy the entire execution and tactical space, while humans concentrate on the meta-strategic layer — defining purpose, values, ethical boundaries, and the conditions under which autonomous action is permissible.

This inversion is not delegation in the traditional sense. Delegation implies a principal who could, in theory, perform the delegated task. In a Level 3 organisation, the volume, velocity, and complexity of machine-executed decisions exceed human cognitive capacity by orders of magnitude. The human role becomes definitional rather than operational: setting the manifold within which autonomous agents navigate, rather than directing specific trajectories.

Endsley's original SA model provides an illuminating parallel. At Level 3 SA (projection), operators do not merely perceive and comprehend current states — they anticipate future states and act pre-emptively. The selfdriven framework's Level 3 transposes this concept to the organisational scale: the organisation itself operates in a state of continuous projection, with AI systems anticipating, adapting, and executing while humans project at a higher order — the trajectory of the organisation's values, the evolution of its ethical commitments, and the long-term alignment between machine action and human purpose.

### 3.2 The Human Conductor Model

The selfdriven Foundation operationalises Level 3 through the Human Conductor model. Each of the Foundation's eight Areas of Focus — Direction, Engagement, Enablement, Protocols, Sustainability, Processes, Accountability, and Organisational — is led by a human conductor who orchestrates AI agents rather than managing human teams in the traditional sense.

The conductor dedicates approximately seventy percent of their energy to their primary area and thirty percent across supporting areas. Conductors handle strategy, judgment, relationships, ethics, and accountability. AI agents handle volume, consistency, monitoring, reporting, and automation. Each conductor holds a KERI Autonomous Identifier (AID) with an ACDC role credential, and AI agents operate under KERI-delegated AIDs with scoped, time-limited authority.

The conductor metaphor is precise and deliberate. An orchestral conductor does not play every instrument; they interpret the score, set tempo and dynamics, make real-time adjustments based on what they hear, and ensure the ensemble produces a coherent whole. Similarly, a Level 3 human conductor does not make every decision — they define the score (strategy), set the tempo (priorities), adjust dynamics (resource allocation and risk tolerance), and ensure the ensemble of AI agents produces outcomes aligned with the organisation's values.

Critically, the conductor model preserves human agency without requiring human involvement in every operational decision. This is the essential distinction between Level 2 and Level 3: at Level 2, humans are in the decision loop; at Level 3, humans define the loop itself.

### 3.3 Cryptographic Identity as the Trust Foundation

A Level 3 organisation in which machines execute autonomously requires a trust architecture that is neither centrally administered nor dependent on human gatekeeping at each transaction. The selfdriven Foundation addresses this through KERI (Key Event Receipt Infrastructure) and ACDC (Authentic Chained Data Containers) — a self-sovereign identity stack that provides cryptographic roots of trust, verifiable credentials, and append-only audit trails.

The trust model operates in three layers:

1. **Key Events:** KERI provides the root of trust via an append-only Key Event Log (KEL) that records inception, rotation, interaction, and delegation events for every identifier in the system.
2. **Credentials:** ACDC credentials attest domain-specific claims — roles, authorities, scopes, time limits — anchored in the KERI identity layer.
3. **Operations:** Domain actions (transactions, attestations, governance votes) reference the credential layer, creating a complete chain of provenance from human-defined authority through machine-executed action.

In a Level 3 context, this architecture enables several critical capabilities:

**Delegated autonomy with cryptographic provenance** ensures that every AI agent action can be traced back through a delegation chain to a human conductor's KERI AID, even when the agent operated fully autonomously.

**Pre-rotation key commitment** means that even if an agent's current keys are compromised, the system can recover because next-key commitments are already embedded in the KEL.

**Scoped, time-limited authority** through ACDC credentials ensures that agents cannot exceed their defined operational boundaries — a cryptographic enforcement of the "human-defined boundaries" that characterise Level 3.

**Witness networks** distributed across multiple nodes provide tamper-evidence without centralised control, ensuring that the audit trail itself cannot be corrupted by any single agent or actor.

Without this identity infrastructure, Level 3 degenerates into either unchecked machine autonomy (no provenance, no boundaries) or a Level 2 bottleneck (humans must approve every significant action). KERI/ACDC provides the cryptographic bridge between human intent and machine execution that makes the Emerging paradigm viable.

### 3.4 Governance Architecture: The AI Constitution

The selfdriven framework identifies the primary evolution focus for Level 3 as threefold: define and encode an AI Constitution or Values Charter; use recursive oversight AI ("AI watching AI") for alignment; and redefine leadership around meaning, foresight, and human purpose.

The AI Constitution concept represents a formal encoding of the organisation's values, ethical boundaries, and operational constraints into a machine-interpretable framework that governs autonomous agent behaviour. This is not a static document but a living protocol — anchored in KERI interaction events so that every modification is immutably recorded and attributable to a specific human conductor's authority.

Recursive oversight — AI systems monitoring other AI systems for drift, bias, and boundary violations — addresses the fundamental scaling problem of Level 3. When machine-executed decisions outnumber human-comprehensible decisions by orders of magnitude, human oversight alone is insufficient. Instead, the governance architecture must be layered: AI agents execute within boundaries; oversight AI monitors for drift; human conductors review oversight reports and adjust boundaries; and the entire chain is anchored in KERI-verifiable event logs.

This creates what might be called a "governance stack" that parallels the trust stack. Just as KERI provides key events, ACDC provides credentials, and operations reference credentials, the governance stack provides values (the AI Constitution), policies (encoded boundary conditions), and monitoring (recursive oversight), all anchored in the same cryptographic identity infrastructure.

### 3.5 Risks and Failure Modes

The selfdriven framework identifies three strategic risks at Level 3: ethical drift, loss of agency, and misalignment with human or social goals. Each deserves careful examination.

**Ethical drift** occurs when the cumulative effect of individually acceptable autonomous decisions gradually shifts the organisation away from its stated values. Each decision may be within boundaries, but the aggregate trajectory diverges. This is analogous to concept drift in machine learning, but applied at the organisational-ethical level. Mitigation requires continuous trajectory monitoring (not just boundary checking) by oversight AI, with regular human conductor reviews of aggregate direction.

**Loss of agency** is the risk that human conductors become functionally ceremonial — nominally setting direction but unable to meaningfully intervene in or comprehend the machine-executed decision space. This "rubber stamp" failure mode is particularly insidious because it preserves the appearance of human oversight while hollowing out its substance. Mitigation requires maintaining genuine conductor competency through continuous education, requiring conductors to periodically "deep dive" into specific decision chains, and designing the governance architecture so that boundary modifications have material, observable effects on agent behaviour.

**Misalignment with human or social goals** extends beyond the organisation itself. A Level 3 organisation optimising effectively within its own value framework may produce externalities that are harmful to broader social interests. This is the classic alignment problem transposed to the organisational scale. The selfdriven framework's response — anchoring everything in verifiable, auditable identity infrastructure — provides at least the preconditions for external accountability: stakeholders, regulators, and the public can trace any machine-executed action back through the delegation chain to its human-authorised origin.

### 3.6 The Before-and-After Transition

The selfdriven.ai diagram visualises the transition across levels as a "before and after" shift in the situational awareness posture of the organisation. The "before" state (Levels 1 and 2) is characterised by human-centric control loops where technology amplifies but does not replace human judgment. The "after" state (Level 3) shows the organisation operating as an ecosystem in which the human role has been elevated — not diminished — to the domain of purpose, ethics, and direction.

This reframing is essential. The common fear that Level 3 represents human obsolescence misreads the framework. The human conductor is not less important at Level 3 — they are differently important. Their value lies not in processing information or making operational decisions (which machines now do better and faster) but in defining what the organisation stands for, what boundaries constrain its actions, and what trajectory it should follow. These are irreducibly human contributions: they require moral reasoning, cultural understanding, stakeholder empathy, and the kind of long-term meaning-making that cannot be delegated to an optimisation function.

The transition from Level 2 to Level 3 is not a single event but a graduated process. Organisations move into Level 3 domain by domain, function by function, as their governance architecture matures, their identity infrastructure is deployed, and their human conductors develop the competencies required for their elevated role. The selfdriven Foundation's eight Areas of Focus provide a structured framework for this transition, allowing each area to progress at its own pace while maintaining coherence across the whole.



## 4. Connections to Broader Research

The selfdriven Situational Awareness Framework draws on and extends several established research traditions. Endsley's three-level SA model (perception, comprehension, projection) provides the conceptual scaffolding, transposed from individual operators to organisational posture. The human-AI teaming (HAT) literature, particularly work on shared situation awareness, transparency, and explainability, informs the transition dynamics between Levels 2 and 3. Research on the Situation Awareness Framework for Explainable AI (SAFE-AI) connects SA levels to the informational needs of human users interacting with AI systems — a direct concern for Level 2 organisations evolving toward Level 3.

The framework also engages with the broader "situational awareness" discourse in AI safety, as articulated by Aschenbrenner and others, which concerns the awareness that both AI systems and human decision-makers need about the trajectory of AI capability development. While this discourse operates at the civilisational scale, the selfdriven framework provides a concrete, organisational-level instantiation of the same concern: how does an institution develop and maintain appropriate awareness of the AI systems it deploys, and how does it govern itself as those systems become increasingly autonomous?

The integration of KERI/ACDC self-sovereign identity infrastructure represents a novel contribution. While the HAT literature extensively discusses transparency and explainability, it rarely addresses the cryptographic provenance infrastructure needed to make transparency verifiable and tamper-evident at scale. The selfdriven approach treats identity not as an administrative convenience but as the load-bearing trust architecture of the entire Level 3 paradigm.



## 5. Implications and Future Directions

Level 3 of the selfdriven Situational Awareness Framework is not a prediction about a distant future — it is a design target that the selfdriven Foundation is actively building toward. The insurance oracles at selfdriven.insure, with their multi-step pipelines anchored in KERI interaction events, represent early instantiations of the pattern: AI-driven data processing and risk computation executing autonomously within human-defined actuarial and regulatory boundaries. The institutional wallet architecture at selfdriven.money, with its multi-signature vaults, RBAC, and compliance workflows under KERI-delegated authority, demonstrates the identity infrastructure in a financial context.

Several open questions remain for future research and development. How should the AI Constitution be structured to be both machine-interpretable and humanly meaningful? What metrics best capture ethical drift at the organisational scale? How can conductor competency be assessed and maintained as the decision space grows increasingly complex? How should external accountability mechanisms (regulatory, public, stakeholder) interface with the internal governance stack?

These questions are not merely theoretical. As AI systems continue to advance in capability and autonomy, every organisation will eventually face the transition the selfdriven framework describes. Those that develop the governance architectures, identity infrastructure, and human conductor competencies in advance will navigate the transition more safely and effectively than those that encounter Level 3 unprepared.



## 6. Conclusion

The selfdriven Situational Awareness Framework for Organisations provides a structured model for understanding the evolving relationship between human decision-makers and AI systems. Level 3 — Machine in Control, Human in Context — represents the most challenging and consequential stage of this evolution: one in which the human role is elevated to purpose, values, and ethical direction while machines handle execution, adaptation, and optimisation at scale.

This paper has argued that Level 3 is viable only when three conditions are met: a Human Conductor model that preserves genuine human agency over direction-setting; a cryptographic identity infrastructure (KERI/ACDC) that provides verifiable, tamper-evident provenance from human intent to machine action; and a layered governance architecture (AI Constitution, recursive oversight, conductor review) that scales with the complexity of autonomous operations.

The phrase "We define direction, not decisions" is not a retreat from human responsibility. It is the recognition that in a world of increasingly capable AI systems, the highest and most irreplaceable form of human contribution is not information processing or operational decision-making, but the definition of what matters, what boundaries constrain action, and what future the organisation is building toward. This is the situational awareness that Level 3 demands.

## References

Endsley, M. R. (1995). Toward a Theory of Situation Awareness in Dynamic Systems. *Human Factors*, 37(1), 32–64.

Endsley, M. R. (2023). Supporting Human-AI Teams: Transparency, Explainability, and Situation Awareness. *Computers in Human Behavior*, 140.

Chen, J. et al. (2024). Situation Awareness in AI-based Technologies and Multimodal Systems: Architectures, Challenges and Applications. *IEEE Access*.

Flathmann, C. et al. (2022). A Situation Awareness Perspective on Human-AI Interaction: Tensions and Opportunities. *International Journal of Human-Computer Interaction*.

Wickens, C. D. (2008). Situation Awareness: Review of Mica Endsley's 1995 Articles on Situation Awareness Theory and Measurement. *Human Factors*, 50(3), 397–403.

Aschenbrenner, L. (2024). Situational Awareness: The Decade Ahead. situational-awareness.ai.

selfdriven Foundation (2026). Situational Awareness Framework for Organisations. selfdriven.ai.

Smith, S. (2024). Key Event Receipt Infrastructure (KERI) Design. WebOfTrust/keri.

selfdriven Foundation (2026). Human Conductor Model: 8 Areas of Focus Operational Framework. selfdriven.foundation.

---

## As Podcast

<audio controls>
	<source src="/assets/audio/research-ai-situational-analysis-level-3.m4a" type="audio/mp4">
	Your browser does not support the audio element.
</audio>

---

- [selfdriven Situational Awareness Framework for Organisations](/situational-awareness-framework/organisations)

