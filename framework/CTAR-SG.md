# CTAR Style Guide (CTAR-SG)

**Version:** 2.0.0  
**Status:** Draft Standard

---

# 1. Purpose

The CTAR Style Guide establishes editorial and formatting conventions for Cyber Threat Assessment Reports (CTARs).

Its purpose is to ensure consistency, readability, and professionalism across all official CTAR publications.

This document governs presentation only. Analytical methodology is defined in CTAR-MS.

---

# 2. Writing Principles

CTAR reports SHOULD be:

- Clear
- Concise
- Objective
- Precise
- Technically accurate
- Accessible to the intended audience

Avoid unnecessary complexity.

Prefer direct language over rhetorical or sensational language.

---

# 3. Tone

CTAR uses an analytical tone.

Reports SHOULD:

- State observations objectively.
- Avoid emotional language.
- Avoid advocacy.
- Avoid speculation presented as fact.
- Avoid marketing language.

Preferred:

> Evidence indicates...

> Available reporting suggests...

> Analysis assesses...

Avoid:

> It is obvious...

> Clearly...

> Everyone knows...

> Without question...

---

# 4. Analytical Language

CTAR distinguishes between several forms of analytical expression.

## Observation

A directly observable fact.

Example:

"The vulnerability was assigned CVE-2026-12345."

---

## Evidence

Information supported by one or more sources.

Example:

"Vendor telemetry identified exploitation beginning on 4 July."

---

## Assessment

An analytical judgment based on available evidence.

Example:

"The activity is assessed to be opportunistic."

---

## Assumption

A condition accepted because information is incomplete.

Assumptions SHOULD be explicitly identified.

---

## Estimate

A reasoned judgment regarding future or unknown conditions.

Estimates SHOULD identify supporting rationale.

---

# 5. Confidence Statements

Confidence SHALL be expressed using standardized terminology.

Approved values:

- High
- Moderate
- Low

Confidence reflects the quality and consistency of available evidence.

Confidence does not represent statistical probability.

---

# 6. Terminology

Use consistent terminology throughout the CTAR Framework.

Preferred terms include:

- Threat Actor
- Campaign
- Indicator of Compromise (IOC)
- Tactics, Techniques, and Procedures (TTPs)
- Evidence
- Assessment
- Confidence
- Assumption
- Estimate

Avoid introducing multiple terms for the same concept within a report.

---

# 7. Acronyms

Spell out acronyms on first use.

Example:

> Indicators of Compromise (IOCs)

Common cybersecurity terms widely recognized by the intended audience MAY be exempt.

---

# 8. Numbers and Dates

Use:

- ISO 8601 dates where practical.
- Coordinated Universal Time (UTC) when precision is important.
- Metric units where applicable.
- Standard cybersecurity notation for ports, IP addresses, hashes, and CVEs.

Examples:

2026-07-06

14:35 UTC

TCP/443

SHA-256

---

# 9. Citations

Sources SHOULD:

- Be complete.
- Be traceable.
- Cite original sources whenever practical.
- Distinguish between primary and secondary reporting.

Avoid excessive citation of derivative reporting.

---

# 10. Tables and Figures

Every table or figure SHOULD include:

- Title
- Number
- Source (if applicable)

Figures SHALL support the analysis rather than decorate the report.

---

# 11. Lists

Bulleted lists SHOULD be used for:

- Recommendations
- Indicators
- Findings
- Procedures

Numbered lists SHOULD be used only when sequence is significant.

---

# 12. Formatting

Official CTAR reports SHOULD:

- Use consistent heading hierarchy.
- Number major sections.
- Use tables where appropriate.
- Clearly separate evidence from assessment.
- Maintain consistent typography throughout the document.

---

# 13. Inclusive and Neutral Language

Reports SHOULD avoid language that:

- Attributes motive without evidence.
- Uses unnecessary national or cultural stereotypes.
- Implies certainty beyond available evidence.

Technical precision should always take precedence over rhetorical impact.

---

# 14. Revision History

Published CTAR reports SHOULD include a revision history when substantive updates occur after initial publication.

Each revision SHOULD summarize significant analytical or editorial changes.

---

# Revision History

| Version | Date | Description |
|----------|------|-------------|
| 1.0.0 | Initial Release | Original Style Guide |
| 2.0.0 | 2026-07-06 | Reorganized as an editorial standard. Added standardized analytical language, confidence terminology, formatting conventions, citation guidance, and neutral writing principles. |
