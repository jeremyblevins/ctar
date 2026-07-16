# CTAR Methodology Standard (CTAR-MS)

**Version:** 2.0.0  
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

# 3. Core Analytical Principles

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


# Publication Metadata

Official CTAR publications SHALL use the filename convention:

`CTAR-<YEAR>-<CLASS>-<SEQUENCE>-<DESCRIPTOR>.<EXT>`

The descriptor SHALL identify the report subject using uppercase, hyphen-separated words. All generated publication formats SHALL retain the same basename.
