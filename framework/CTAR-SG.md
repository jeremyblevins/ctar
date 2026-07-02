# CTAR Style Guide (CTAR-SG)

**Document ID:** CTAR-SG  
**Version:** 1.1.0  
**Status:** Current  
**Effective Date:** 1 July 2026

---


## Normative Language

The key words **"MUST"**, **"MUST NOT"**, **"REQUIRED"**, **"SHALL"**, **"SHALL NOT"**, **"SHOULD"**, **"SHOULD NOT"**, **"RECOMMENDED"**, **"MAY"**, and **"OPTIONAL"** in this document are to be interpreted as described in RFC 2119 and RFC 8174 when, and only when, they appear in all capital letters.

---

# 1. Purpose

The CTAR Style Guide establishes formatting, terminology, and writing conventions for all Cyber Threat Assessment Reports (CTARs).

Its purpose is to ensure that CTAR products are clear, consistent, professional, and easily understood by technical and non-technical audiences.

---

# 2. Writing Principles

CTAR reports should be:

- Clear
- Concise
- Accurate
- Objective
- Evidence-based
- Reproducible

Avoid unnecessary jargon whenever plain language conveys the same meaning.

---

# 3. Voice and Tone

Use:

- Third-person perspective
- Professional language
- Objective wording
- Neutral tone

Avoid:

- Personal opinions
- Emotional language
- Marketing language
- Sensationalism

Example:

Preferred:

> The malware propagated through email attachments.

Not:

> The devastating malware aggressively attacked victims.

---

# 4. Tense

Use:

Past tense

- Historical assessments
- Completed incidents

Present tense

- Current framework guidance
- General technical facts
- Ongoing threats where appropriate

---

# 5. Terminology

Use standardized cybersecurity terminology whenever practical.

Examples:

- Indicator of Compromise (IOC)
- Tactics, Techniques, and Procedures (TTPs)
- Initial Access
- Command and Control (C2)
- Privilege Escalation
- Defense Evasion

Avoid unexplained abbreviations.

---

# 6. Headings

Recommended hierarchy:

# Report Title

## Major Section

### Subsection

#### Supporting Topic

Avoid deeper heading levels unless necessary.

---

# 7. Lists

Use bulleted lists for:

- Characteristics
- Recommendations
- Evidence

Use numbered lists only when sequence matters.

---

# 8. Tables

Tables should be used for structured information.

Examples:

- Timelines
- IOC summaries
- ATT&CK mappings
- Confidence assessments
- Source reliability

Every table should include descriptive column headings.

---

# 9. Dates and Times

Use ISO 8601 format whenever practical.

Example:

2026-07-01

Spell out historical dates when appropriate for readability.

---

# 10. Numbers

Spell out numbers one through nine.

Use numerals for:

- Measurements
- Dates
- Technical values
- Versions
- Percentages

Example:

Approximately 45 million systems.

---

# 11. Citations

Prefer primary sources.

Where possible, cite:

- Government publications
- Vendor advisories
- Academic research
- Official documentation

Avoid citing AI-generated text as evidence.

---

# 12. Figures and Images

Images should:

- Support analytical findings.
- Include captions.
- Identify the source.
- Respect copyright restrictions.

Decorative images should be avoided.

---

# 13. Code and Technical Content

Use fenced code blocks for:

- Commands
- Configuration
- File names
- Registry paths
- Scripts

Operational exploit code should not be included in public CTARs.

---

# 14. Confidence Language

Confidence assessments should use standardized terms.

Approved values:

- High
- Moderate
- Low

Avoid:

- Very High
- Fairly Certain
- Maybe
- Probably

---

# 15. AI Disclosure

Material AI assistance should be acknowledged when appropriate.

Routine proofreading or grammar correction need not be disclosed.

---

# 16. Accessibility

CTAR reports should:

- Use descriptive headings.
- Avoid unnecessary color dependence.
- Use meaningful table headings.
- Provide alt text for images where supported.

---

# 17. File Naming

Framework Documents

CTAR-MS.md

CTAR-SG.md

CTAR-DAP.md

Historical Reports

CTAR-1988-0001-Morris-Worm.md

CTAR-2000-0002-ILOVEYOU.md

Supporting Documents

CHANGELOG.md

ROADMAP.md

README.md

---

# 18. Versioning

Framework documents shall include:

- Document ID
- Version
- Status
- Effective Date

CTAR reports shall include:

- CTAR ID
- Report Version
- Framework Version

---

# 20. Evidence Traceability Standard

## Evidence Identifiers

Evidence identifiers **MUST** use the format:

- E-001
- E-002
- E-003

## Inline Evidence Citations

Evidence **MUST** be cited inline using Evidence IDs.

Example:

> The Department of Justice announced charges against the subject [E-001].

## Required Appendices

Every CTAR **MUST** include:

- Appendix A – Evidence Register
- Appendix B – Evidence Traceability Matrix (ETM)

## Evidence Register

The Evidence Register **MUST** contain the following columns:

- Evidence ID
- Evidence
- Type
- Publication Date
- Source Organization
- Reliability
- Authenticity
- Used In
- Hyperlink

Hyperlinks **SHOULD** reference the original source whenever practical.


---

# 19. Relationship to Other CTAR Documents

This Style Guide supports all documents within the CTAR Framework and should be used in conjunction with the Methodology Specification and Report Template.