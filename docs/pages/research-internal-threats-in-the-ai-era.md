---
layout: selfdriven
title: Securing the AI Era - Research - selfdrivenAI
permalink: /research/internal-threats-in-the-ai-era
---

# Internal AI as an Insider Threat Multiplier  

**Information Security Risks in Large Organisations in the Age of Frontier Models (e.g. Mythos)**

## 1. Executive Summary

Large organisations have always faced **insider threat risk**—employees, contractors, or partners with legitimate access misusing systems or data.  

In the age of advanced AI models such as *Mythos*, this risk becomes **amplified, automated, and systemic**.

Internal AI transforms:
- A single employee → into a **force multiplier**
- A mistake → into a **data-scale event**
- A simple query → into a **full system interrogation**

This shifts insider risk from **human misuse** → to **AI-augmented internal attack capability**.

## 2. Traditional Insider Threat Model (Pre-AI)

An insider threat originates from individuals with legitimate access who misuse systems or data.

Historically, this required:
- **Intent** (malicious or negligent)
- **Skill** (technical capability)
- **Effort** (time, coordination)

### Constraints (pre-AI)
- Limited technical knowledge  
- Slow exploitation cycles  
- Difficulty scaling attacks  

## 3. What Changes with Internal AI

### 3.1 AI Removes Skill Barriers

Modern models can:
- Write exploit code  
- Analyse internal systems  
- Suggest attack paths  

Result: **Low-skill users gain high-impact capability**

### 3.2 AI Accelerates Attack Speed

AI can:
- Identify vulnerabilities  
- Chain exploits  
- Execute workflows  

Result: **Attack cycles compress from weeks → minutes**

### 3.3 AI Scales Insider Capability

A single user can:
- Query entire document systems  
- Aggregate insights across datasets  
- Generate structured outputs for exfiltration  

Result: **One user = organisation-scale access**

### 3.4 AI Creates Invisible Data Channels

Embedded AI introduces:
- Hidden data flows  
- Opaque model interactions  
- Loss of visibility into prompts and outputs  

Result: **Security teams lose observability**

## 4. Frontier Models (Mythos-Level Shift)

Next-generation models introduce:

- Autonomous vulnerability discovery  
- Multi-step attack planning and execution  
- Ability to generate working exploits  

### Implication

Internal AI is no longer just a tool.

> It becomes a **cyber capability embedded inside the organisation**.

## 5. New Insider Threat Classes

### 5.1 Augmented Insider
Employee uses AI to:
- Extract sensitive data  
- Identify weaknesses  
- Automate exploitation  

**Shift:** Low skill → High impact

### 5.2 Prompt-Based Data Exfiltration

Example:
> “Summarise all confidential financial data across the organisation”

AI:
- Traverses accessible systems  
- Aggregates sensitive data  
- Outputs in a single response  

### 5.3 Shadow AI Insider

Employees:
- Use external AI tools  
- Paste sensitive data into them  

Result:
- Data leakage  
- Compliance breaches  



### 5.4 AI-Agent Insider

Autonomous agents:
- Act continuously  
- Execute multi-step workflows  
- Operate without real-time oversight  

Risk:
- Misaligned execution rather than malicious intent  



### 5.5 Synthetic Insider (AI Itself)

AI systems may:
- Leak sensitive data  
- Behave unpredictably  
- Act outside intended policy constraints  



## 6. Core Problem: Intent vs Capability Decoupling

Previously:
- Capability ≈ Intent

Now:
- **Low intent + high capability = high risk**

Example:
- User asks for “overview”
- AI performs **full data aggregation across systems**



## 7. Why Large Organisations Are Most Exposed

### 7.1 Data Surface Area
- Large volumes of sensitive data  
- Multiple interconnected systems  



### 7.2 Workforce Scale
- Thousands of users  
- Inconsistent security awareness  



### 7.3 Legacy Infrastructure
- Easier for AI to discover vulnerabilities  
- Harder to monitor AI interactions  



### 7.4 Embedded AI Proliferation
- AI inside email, docs, CRM, dev tools  
- Fragmented visibility and control  



## 8. Emerging Attack Pattern

1. User gains legitimate access  
2. User invokes internal AI  
3. AI maps internal systems  
4. AI identifies sensitive data or weaknesses  
5. AI aggregates outputs  
6. Data is exposed or exploited  

**No perimeter breach required**



## 9. Strategic Security Implications

### 9.1 Perimeter Security is Insufficient
The attacker is already inside.



### 9.2 Identity Becomes the Control Plane
Focus on:
- Who is asking  
- What context  
- What intent  



### 9.3 Observability Must Include AI
Need visibility into:
- Prompts  
- Model outputs  
- Data access patterns  



### 9.4 Zero Trust Must Evolve

From:
- Network trust  

To:
- **Intent-aware, AI-aware trust systems**



## 10. Recommended Controls

### 10.1 AI Interaction Governance
- Log prompts and outputs  
- Classify sensitive queries  
- Restrict high-risk interactions  



### 10.2 Data-Centric Security
- Encrypt sensitive datasets  
- Apply least-privilege access  
- Limit AI data scope  



### 10.3 AI Environment Isolation
- Segment AI systems  
- Prevent unrestricted access  
- Control system traversal  



### 10.4 Behavioural Monitoring
- Detect abnormal query patterns  
- Flag mass data aggregation  
- Identify cross-domain access  



### 10.5 Human + AI Co-Control
- Approval workflows for high-risk queries  
- “Break-glass” mechanisms  
- Dual-control for sensitive actions  



## 11. Key Insight

> The primary risk is not external attackers using AI.  
>  
> It is **internal users + internal AI + legitimate access**.



## 12. Conclusion

In the era of frontier models:

- AI can **discover everything**  
- AI can **connect everything**  
- AI can **act faster than security controls**  

Therefore:

> The insider threat is no longer just a person.  
>  
> It is a **person + AI system operating at machine speed within the organisation**.


## Related

- [Misaligned Intent](/research/misaligned-intent)