# CTAR Source Reliability Matrix (CTAR-SRM)

**Version:** 2.0.0  
**Status:** Draft Standard

---

# 1. Purpose

The CTAR Source Reliability Matrix establishes a standardized methodology for evaluating the reliability, credibility, and analytical value of information used in Cyber Threat Assessment Reports (CTARs).

The objective is to improve transparency, reduce analytical bias, and support reproducible threat assessments.

This standard applies to all evidence used in official CTAR publications.

---

# 2. Relationship to Other Framework Documents

This standard supports:

- CTAR-MS by defining source evaluation procedures.
- CTAR-DAP by complementing evidence authenticity assessment.
- CTAR-RT by providing the basis for source summaries included in published reports.

---

# 3. Principles

Source evaluation SHALL assess:

- Reliability
- Credibility
- Relevance
- Corroboration

These characteristics are independent.

A technically accurate source may contain incomplete information.

A highly credible organization may publish preliminary assessments that require later revision.

---

# 4. Source Categories

Common CTAR source categories include:

- Government advisories
- Vendor security bulletins
- Academic research
- Incident response reports
- Malware analyses
- Vulnerability databases
- Digital forensic evidence
- Threat intelligence feeds
- Historical archives
- Open-source intelligence (OSINT)
- Media reporting
- Social media

No category is inherently reliable or unreliable.

Each source SHALL be evaluated independently.

---

# 5. Evaluation Criteria

Analysts SHOULD evaluate each source across the following dimensions.

## Authenticity

Can the origin of the information be reasonably verified?

Examples:

- Original publication
- Digitally signed document
- Official advisory
- Verified repository

---

## Technical Competence

Does the author demonstrate appropriate expertise?

Consider:

- Demonstrated methodology
- Technical detail
- Supporting evidence
- Peer recognition

---

## Independence

Was the information developed independently?

Independent reporting generally provides stronger analytical value than repeated citation of the same original source.

---

## Corroboration

Has the information been confirmed by independent evidence?

Multiple independent confirmations increase confidence.

Repeated publication of identical information does not constitute corroboration.

---

## Timeliness

Is the information current for the assessment?

Threat intelligence often changes rapidly.

Historical reports remain valuable when used appropriately.

---

## Transparency

Does the source explain:

- Methodology
- Data sources
- Analytical assumptions
- Limitations

Transparent reporting generally deserves greater confidence.

---

# 6. Reliability Assessment

Analysts SHOULD summarize source reliability using the following qualitative ratings.

## High Reliability

Characteristics:

- Original evidence
- Well documented
- Independently corroborated
- Technically detailed
- Transparent methodology

Examples:

- Vendor forensic reports
- Government advisories
- Court documents
- Academic publications
- Incident response reports

---

## Moderate Reliability

Characteristics:

- Generally credible
- Limited corroboration
- Some methodological uncertainty

Examples:

- Industry analysis
- Professional journalism
- Conference presentations

---

## Low Reliability

Characteristics:

- Anonymous sourcing
- Limited technical detail
- No corroboration
- Unclear methodology

Examples:

- Unverified social media
- Speculative reporting
- Rumors

Low reliability does not necessarily imply false information.

---

# 7. Corroboration Levels

CTAR recognizes four corroboration states.

| Level | Description |
|---------|-------------|
| Confirmed | Supported by multiple independent sources |
| Corroborated | Supported by at least one independent source |
| Unconfirmed | Reported by a single source |
| Contradicted | Conflicts with available evidence |

Corroboration SHALL be distinguished from reliability.

---

# 8. Source Bias

Analysts SHOULD consider potential bias.

Sources may exhibit:

- Commercial interests
- Political interests
- National interests
- Ideological interests
- Legal interests
- Marketing objectives

Bias does not automatically invalidate evidence.

---

# 9. Source Conflicts

When credible sources disagree, analysts SHALL:

- Document the disagreement.
- Explain competing interpretations.
- Assess which interpretation is better supported.
- Reflect uncertainty in confidence assessments.

---

# 10. Source Summary

Every CTAR SHOULD include a brief summary describing:

- Number of sources reviewed
- Diversity of sources
- Degree of corroboration
- Overall reliability

This summary improves transparency without requiring readers to examine every citation.

---

# 11. Limitations

Analysts SHALL recognize that:

- Reliable sources may later be corrected.
- Emerging incidents often contain incomplete information.
- Attribution remains inherently uncertain.
- Intelligence evolves over time.

Source evaluation is therefore iterative rather than permanent.

---

# Revision History

| Version | Date | Description |
|----------|------|-------------|
| 1.0.0 | Initial Release | Original Source Reliability Matrix |
| 2.0.0 | 2026-07-06 | Replaced organizational tiering with multidimensional source evaluation. Introduced standardized evaluation criteria, corroboration levels, conflict resolution guidance, and source summary requirements. |
