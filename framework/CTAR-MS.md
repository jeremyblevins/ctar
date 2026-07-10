# CTAR Methodology Standard (CTAR-MS)

**Version:** 2.1.0  
**Status:** Draft Standard

---

# 1. Purpose

The CTAR Methodology Standard establishes the analytical process used to produce Cyber Threat Assessment Reports (CTARs). It defines the minimum methodological requirements necessary to produce assessments that are transparent, evidence-based, reproducible, and technically rigorous.

This document is normative for all official CTAR products.

---

# 2. Relationship to Other Framework Documents

This standard complements other components of the CTAR Framework.

- CTAR-GC defines governance and lifecycle management.
- CTAR-RT defines report structure and presentation.
- CTAR-SRM defines source reliability evaluation.
- CTAR-DAP defines evidence authenticity requirements.
- CTAR-AIPP defines acceptable AI participation.
- CTAR-ATM (Analytical Tradecraft Manual) provides advanced analytical techniques.

Where conflicts exist, Governance Charter requirements SHALL take precedence.

---

# 3. CTAR Analytical Product Types

The Cyber Threat Assessment and Reporting (CTAR) Framework supports multiple analytical products. Although each product serves a different purpose, all SHALL follow the methodological principles defined in this standard unless explicitly exempted.

## 3.1 Cyber Threat Assessment Reports (CTARs)

Cyber Threat Assessment Reports evaluate current or emerging cybersecurity events, vulnerabilities, threat actors, campaigns, technologies, or risks. Their primary purpose is to support operational awareness and informed decision-making.

## 3.2 CTAR Historical Case Studies

CTAR Historical Case Studies apply the CTAR methodology to historically significant cyber incidents, campaigns, or operations whose principal value lies in education rather than time-sensitive reporting.

Unlike current Cyber Threat Assessment Reports, Historical Case Studies emphasize analytical reasoning, strategic context, historical perspective, and enduring defensive lessons.

Historical Case Studies SHALL:
- Apply the same evidence-based analytical methodology required of CTAR reports.
- Distinguish clearly between established facts, analytical judgments, assumptions, and uncertainty.
- Include explicit confidence assessments.
- Present sufficient historical context.
- Translate historical observations into practical defensive and educational lessons.
- Encourage critical thinking.

Examples include CTAR-H-1988-001 (Morris Worm), CTAR-H-2000-001 (ILOVEYOU), CTAR-H-2010-001 (Operation Olympic Games), CTAR-H-2017-001 (NotPetya), and CTAR-H-2020-001 (SolarWinds).

## 3.3 Common Methodology

Regardless of product type, every official CTAR publication SHALL:
- Be evidence-based.
- Clearly separate evidence from analysis.
- Communicate confidence explicitly.
- Identify uncertainty and intelligence gaps.
- Apply the CTAR Source Reliability Matrix.
- Comply with the CTAR Governance Charter.

> **CTAR Principle:** CTAR is methodology-driven, not product-driven.

---

# 4. Core Analytical Principles

Every CTAR SHALL be:

- Evidence-driven
- Objective
- Transparent
- Reproducible
- Technically accurate
- Vendor-neutral
- Explicit about uncertainty

Analysts SHALL distinguish between:

- Observed facts
- Corroborated evidence
- Analytical interpretation
- Estimates
- Assumptions
- Confidence judgments

These categories SHALL NOT be conflated.

---

# 4. Analytical Workflow

Every CTAR SHALL follow the following analytical lifecycle.

## Phase 1 — Problem Definition

The analyst SHALL define:

- Scope
- Assessment objective
- Intended audience
- Timeframe
- Key analytical questions

---

## Phase 2 — Evidence Collection

Evidence MAY include:

- Vendor advisories
- Government publications
- Threat intelligence
- Malware analysis
- Vulnerability databases
- Academic research
- Digital forensics
- Open-source intelligence
- Historical records

Evidence SHALL be documented sufficiently to support independent review.

---

## Phase 3 — Source Evaluation

Sources SHALL be evaluated according to CTAR-SRM.

Evaluation SHOULD consider:

- Authenticity
- Independence
- Technical competence
- Corroboration
- Timeliness
- Historical reliability

---

## Phase 4 — Evidence Validation

Evidence SHALL be assessed for authenticity using CTAR-DAP.

Analysts SHOULD identify:

- Manipulated media
- AI-generated artifacts
- Translation limitations
- Archived material
- Incomplete datasets
- Missing context

---

## Phase 5 — Analysis

Analysis SHALL:

- Correlate evidence
- Identify patterns
- Evaluate competing explanations
- Distinguish causation from correlation
- Document analytical assumptions
- Identify knowledge gaps

Analysts SHOULD consider alternative hypotheses whenever reasonable.

---

## Phase 6 — Assessment Development

Assessments SHALL include:

- Key judgments
- Supporting evidence
- Confidence levels
- Information gaps
- Potential future developments

---

## Phase 7 — Peer Review

Official CTAR publications SHOULD undergo technical peer review before release.

Peer review SHOULD evaluate:

- Technical accuracy
- Logical consistency
- Source quality
- Confidence assignments
- Report completeness

---

# 5. Confidence Assessment

Every significant analytical judgment SHALL include an explicit confidence assessment.

Confidence reflects the analyst's assessment of the quality, quantity, consistency, and corroboration of available evidence. It does not represent statistical probability.

The recommended confidence scale is:

- High
- Moderate
- Low

Confidence SHOULD consider:

- Number of independent sources
- Source reliability
- Evidence consistency
- Technical validation
- Presence of conflicting information

---

# 6. Handling Uncertainty

Analysts SHALL explicitly identify uncertainty.

Sources of uncertainty MAY include:

- Incomplete evidence
- Conflicting reporting
- Limited technical visibility
- Attribution ambiguity
- Active investigations

Unknown information SHALL NOT be presented as fact.

---

# 7. Evidence vs Assessment

CTAR distinguishes between:

**Evidence**

Observable information directly supported by sources.

**Assessment**

Reasoned interpretation based on available evidence.

**Assumption**

A condition accepted for analytical purposes due to incomplete information.

**Estimate**

An informed judgment regarding unknown or future conditions.

These distinctions SHALL remain explicit throughout every report.

---

# 8. Analytical Independence

Analysts SHALL:

- Avoid advocacy
- Avoid confirmation bias
- Document significant conflicting evidence
- Revise conclusions when new evidence emerges
- Separate technical findings from policy recommendations

The purpose of a CTAR is to inform decision-makers rather than persuade them.

---

# 9. AI-Assisted Analysis

Artificial intelligence MAY assist with:

- Information summarization
- Data organization
- Language refinement
- Draft generation
- Pattern identification

AI SHALL NOT replace analyst judgment.

Human analysts remain responsible for:

- Evidence validation
- Source evaluation
- Technical accuracy
- Confidence assignment
- Final analytical conclusions

AI participation SHALL be disclosed in accordance with CTAR-AIPP.

---

# 10. Reproducibility

A CTAR SHOULD contain sufficient information for another qualified analyst to:

- Understand the evidence
- Reconstruct the analytical process
- Reach similar conclusions using the same evidence

Absolute reproducibility is not always possible due to changing threat intelligence.

---

# 11. Methodological Limitations

Analysts SHOULD acknowledge limitations such as:

- Intelligence gaps
- Restricted access
- Dynamic threat activity
- Conflicting reporting
- Time constraints
- Technical uncertainty

These limitations increase transparency and assist readers in interpreting confidence assessments.

---

# Revision History

| Version | Date | Description |
|----------|------|-------------|
| 1.0.0 | Initial Release | Original methodology standard |
| 2.0.0 | 2026-07-06 | Complete restructuring to align with CTAR Governance Charter v1.1.0. Introduced phased analytical workflow, evidence validation, confidence methodology, analytical independence, AI-assisted analysis, and reproducibility guidance. |
| 2.1.0 | 2026-07-10 | Introduced formal CTAR analytical product taxonomy, including Cyber Threat Assessment Reports and CTAR Historical Case Studies. Clarified that both product types follow the same evidence-based methodology while serving different operational and educational purposes. |
