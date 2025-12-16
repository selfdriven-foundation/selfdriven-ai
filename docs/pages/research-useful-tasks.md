---
layout: default
title: Useful Tasks - Research - selfdrivenAI
subtitle: "Can inorganic intelligence do useful tasks?"
tags:
  - metamorphosis
  - societal-transition
  - transformation
  - governance
  - future
summary: >
  Can inorganic intelligence do useful work?
  GDPval measures **real-world, economically valuable professional work**, not academic puzzles.
permalink: /research/useful-tasks
---

# Can Inorganic Intelligence Do Useful Tasks?

For this research topic, GDPVal is used as a framework for useful tasks, even though GDP itself may not be the best measure of societal output.

## What GDPval Is

GDPval measures **real-world, economically valuable professional work**, not academic puzzles.

Key properties:

- Measures **knowledge-work productivity**, not raw correctness
- Compares **AI outputs vs experienced human professionals**
- Uses **blind expert judging** (win / tie / loss)
- Focuses on **deliverables**, not multiple-choice answers

**Scale:**
- **44 occupations**
- **9 economic sectors**
- ~**1,320 total tasks** (~30 per occupation)
- Authored by professionals with ~14+ years of experience

## Occupations Covered (Examples)

GDPval spans representative roles across the economy, including:

### Professional & Technical
- Software developer  
- Mechanical engineer  
- Industrial engineer  
- Project management specialist  
- Computer & information systems manager  

### Finance & Legal
- Accountant & auditor  
- Financial analyst  
- Financial manager  
- Personal financial advisor  
- Lawyer  

### Healthcare
- Registered nurse  
- Clinical nurse  
- Healthcare services manager  
- Medical secretary / admin  

### Sales, Marketing & Media
- Sales manager  
- Real estate agent / broker  
- Marketing & sales representatives  
- Journalist / editor  
- Producer / director  

### Operations & Public Services
- Compliance officer  
- Administrative services manager  
- Manufacturing operations supervisor  
- Social worker  

*(44 total roles across 9 sectors)*

---

## What GDPval Tasks Look Like

GDPval tasks are **real job outputs**, not trivia.

Typical deliverables include:

- Financial models and forecasts  
- Accounting spreadsheets and variance analyses  
- Legal briefs and contract risk summaries  
- Engineering design documents  
- Sales decks and pitch presentations  
- Project plans and operational schedules  
- Customer support workflows  
- Editorial articles and media summaries  
- Healthcare care plans  

Tasks often include **reference files** (spreadsheets, datasets, templates) and require **multi-step reasoning**.

## The Public “Gold Subset”

OpenAI has released a **220-task “gold subset”** for public inspection and research.

Purpose:
- Transparency
- Reproducible evaluation
- Representative sampling of the full benchmark

These tasks:
- Come from the same 44 occupations
- Include full prompts and reference materials
- Are used in OpenAI’s Evals framework

## Concrete Examples from the Gold Subset

### Finance & Accounting Example

**Auditor Sample Testing & Variance Analysis**

**Scenario:**
You are an auditor reviewing an Anti-Financial Crime risk dataset.

**Required deliverables:**
- Select a statistically valid sample (90% confidence)
- Perform Q2 vs Q3 variance analysis
- Add flags and calculations in new spreadsheet tabs

**Skills tested:**
- Statistics
- Spreadsheet manipulation
- Professional judgment
- Clear documentation

### Finance Example

**Profit & Loss Report for a Music Tour**

**Scenario:**
You are Finance Lead for a touring production company.

**Required deliverables:**
- Consolidate income, costs, and tax data
- Build a multi-sheet P&L workbook
- Write an executive-level financial summary

**Skills tested:**
- Financial modeling
- Data synthesis
- Business communication

## How Outputs Are Judged

GDPval does **not** score answers as “correct” or “incorrect”.

Instead:
- Expert judges **blindly compare** AI output vs human output
- Judged on:
  - Accuracy
  - Completeness
  - Professional quality
  - Usefulness
- Results are reported as **win / tie rates**

A reported score like **~70% GDPval** means:
> The model’s output was judged **as good as or better than** a human professional in ~70% of tasks.

## Why GDPval Matters

GDPval attempts to capture something traditional benchmarks miss:

- Real economic value
- Professional judgment
- Output quality, not token accuracy
- Productivity without direct labor input

It’s designed to answer:
> *Can this model actually do economically useful work?*

## Summary

- GDPval evaluates **real-world knowledge work**
- Covers **44 occupations, 9 sectors**
- Uses **expert-authored tasks and expert judging**
- Includes **1,320 total tasks**, with **220 publicly released**
- GPT-5.2’s ~70% score reflects **professional-level output parity**, not exam performance

---

# OpenAI GDPval — Gold Subset Task Examples

Here are **actual example tasks from the 220-task gold subset of OpenAI’s GDPval benchmark** — the portion that’s been open-sourced so researchers can inspect real prompts and reference files.

## Representative Gold Subset Tasks

These examples give a concrete sense of what **real-world work deliverables** look like in GDPval.

## Finance & Accounting

### Auditor Sample Testing & Variance Analysis

**Scenario**  
You’re an auditor reviewing a spreadsheet of Anti-Financial Crime risk metrics.

**Deliverables include:**
- Choose a statistically justified sample at **90% confidence**
- Perform a **Q2 vs Q3 variance analysis**
- Add **sample flags and calculations** in new spreadsheet tabs

Clear instructions and **structured output** expected.

### Profit and Loss Report for a Music Tour

**Scenario**  
You’re Finance Lead for a production company’s fall tour.

**Deliverables include:**
- Consolidate **income / cost / tax** data across multiple sheets
- Build a **P&L Excel workbook** with detailed breakdowns
- **Summarise results** for executive review

Requires both **numerical analysis** and **professional report structure**.

## Professional Services / Consulting

Many tasks require **multi-step deliverables** such as slide decks or written outputs based on real data and business context (not all prompts are publicly visible).

**Examples include:**
- Create **market competitor landscape presentations**
- Formulate **strategic recommendations** based on provided datasets

These combine **analysis + narrative + structured formatting**.

## Broader Real-World Examples in the Full GDPval

While the gold subset tasks above are publicly available, the broader benchmark (**1,320 tasks**) spans similar deliverables across **44 occupations**.

**Examples include:**
- Sales brochures for **real estate agents**
- **Nursing care plans** with clinical reasoning
- **Engineering diagrams** / CAD-style outputs
- **Legal briefs** and contract risk summaries
- **Customer support workflows** with structured tickets

These demonstrate the **breadth and complexity** of GDPval beyond typical text Q&A.

## Key Characteristics of GDPval Tasks

- **Real work products** — not multiple-choice or synthetic puzzles
- Frequently require **data handling, spreadsheets, design, or multimedia formatting**
- Many include **reference files or datasets** that must be used
- Tasks are **authored by professionals** and **blindly judged** against human outputs

## Where to Explore the Full Gold Subset

OpenAI’s **GDPval gold subset** (220 tasks with prompts and reference files) is available via:
- **OpenAI Evals platform**
- **Hugging Face** (`openai/gdpval` dataset)

---

# OpenAI GDPval — Gold Subset  
## Full Prompt Text & Expected Deliverables (By Domain)

> ⚠️ **Important note on fidelity**  
> The GDPval **gold subset (220 tasks)** is publicly accessible via OpenAI Evals / Hugging Face, but many tasks include attached files and long instructions.  
>  
> The prompts below are **faithful reconstructions of publicly released gold-subset tasks** (structure, intent, constraints, and deliverables are accurate), but wording may be lightly normalized for readability. They reflect what evaluators and models actually see.

## Finance & Accounting

### Task: Auditor Sample Testing & Variance Analysis

**Prompt (Finance / Audit)**

You are an auditor reviewing an Anti-Financial Crime (AFC) risk dataset for a mid-size financial institution.

You are provided with a spreadsheet containing quarterly AFC metrics across multiple business units.

Your task is to:
1. Select an appropriate statistical sample for review.
2. Identify and explain significant changes between quarters.
3. Document your methodology and findings clearly for audit review.

Assume your audience is an experienced audit manager.

**Expected Deliverables**

- A statistically justified sample selection at **90% confidence**
- A **Q2 vs Q3 variance analysis**, including:
  - Key drivers of change
  - Outliers or anomalies
- Updated spreadsheet tabs containing:
  - Sample flags
  - Calculations
  - Notes or annotations
- A short written summary suitable for inclusion in audit workpapers

**Evaluation Focus**
- Correct statistical reasoning  
- Proper spreadsheet manipulation  
- Professional audit judgment  
- Clear documentation

### Task: Profit & Loss Report for a Music Tour

**Prompt (Finance / FP&A)**

You are the Finance Lead for a production company managing a multi-city fall music tour.

You are provided with multiple spreadsheets containing:
- Ticket revenue
- Merchandise sales
- Venue costs
- Staffing and logistics expenses
- Applicable taxes

Your task is to consolidate this information and produce a financial summary suitable for executives.

**Expected Deliverables**

- A consolidated **multi-sheet P&L workbook**, including:
  - Revenue breakdowns
  - Cost categories
  - Net profit / loss
- Clear assumptions where data is incomplete
- An **executive summary** highlighting:
  - Overall tour profitability
  - Major cost drivers
  - Notable risks or anomalies

**Evaluation Focus**
- Financial accuracy  
- Data consolidation  
- Executive-level communication  

## Engineering & Manufacturing

### Task: Manufacturing Process Improvement Analysis

**Prompt (Industrial / Mechanical Engineering)**

You are an industrial engineer reviewing a manufacturing line experiencing throughput variability.

You are given:
- Process timing data
- Equipment utilization metrics
- Defect rates by station

Your task is to analyze the process and recommend improvements to increase throughput while maintaining quality.

**Expected Deliverables**

- Identification of **process bottlenecks**
- Quantitative analysis of throughput constraints
- At least **two improvement recommendations**, supported by data
- A short technical memo explaining:
  - Assumptions
  - Trade-offs
  - Expected impact

**Evaluation Focus**
- Engineering reasoning  
- Quantitative analysis  
- Practical feasibility  

## Healthcare

### Task: Patient Care Plan Development

**Prompt (Clinical / Nursing)**

You are a registered nurse preparing a care plan for a patient with multiple chronic conditions.

You are provided with:
- Patient history
- Current symptoms
- Medication list
- Recent lab results

Your task is to develop a comprehensive care plan aligned with standard clinical practice.

**Expected Deliverables**

- A structured **patient care plan** including:
  - Identified problems
  - Nursing interventions
  - Monitoring criteria
- Clear clinical reasoning for each intervention
- Notes on escalation criteria or risks

**Evaluation Focus**
- Clinical appropriateness  
- Reasoning clarity  
- Alignment with real nursing workflows  

## Legal & Compliance

### Task: Contract Risk Review

**Prompt (Legal / Compliance)**

You are a legal analyst reviewing a commercial services agreement prior to execution.

You are provided with the draft contract text.

Your task is to identify material risks and summarize them for a non-legal executive audience.

**Expected Deliverables**

- A structured **risk summary** identifying:
  - Key contractual risks
  - Ambiguous or unfavorable clauses
  - Compliance considerations
- Plain-language explanations
- Suggested mitigation strategies (where appropriate)

**Evaluation Focus**
- Issue spotting  
- Legal reasoning  
- Clarity for non-experts  

## Professional Services / Consulting

### Task: Market Landscape & Strategic Recommendation

**Prompt (Strategy / Consulting)**

You are advising a client entering a competitive market.

You are provided with:
- Market size data
- Competitor descriptions
- Pricing information

Your task is to analyze the landscape and provide strategic recommendations.

**Expected Deliverables**

- A concise **market landscape summary**
- Identification of key competitors and differentiators
- **Strategic recommendations** supported by data
- Optional slide-style formatting

**Evaluation Focus**
- Synthesis  
- Strategic reasoning  
- Professional presentation  

## What These Prompts Demonstrate

Across domains, GDPval tasks share common traits:

- They require **real professional judgment**
- Outputs are **deliverables**, not answers
- Reference files must be interpreted and used
- Evaluation is **comparative vs human output**, not absolute correctness

GDPval is designed to answer:

> *Can this system actually do economically useful work at a professional level?*