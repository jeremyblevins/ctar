# CTAR Source Reliability Matrix (CTAR-SRM)

**Document ID:** CTAR-SRM  
**Version:** 1.0.0  
**Status:** Current  
**Effective Date:** 1 July 2026

---

# 1. Purpose

The CTAR Source Reliability Matrix establishes a standardized method for evaluating the reliability of information sources used in Cyber Threat Assessment Reports (CTARs).

The purpose of this document is to promote consistent evidence evaluation, improve analytical transparency, and support defensible intelligence assessments.

Source reliability should never be confused with analytical confidence. Reliable sources may still report incomplete information, and low-reliability sources may occasionally provide accurate information.

---

# 2. Principles

Source evaluation should consider:

- Authority
- Authenticity
- Independence
- Timeliness
- Corroboration
- Transparency

No single source should be considered authoritative solely because of its reputation.

---

# 3. Reliability Categories

## High Reliability

Characteristics include:

- Primary source
- Official documentation
- Direct observation
- Original technical analysis
- Transparent methodology
- Consistently accurate historical reporting

Examples:

- Government advisories
- Vendor technical analyses
- Digital forensic reports
- Academic research
- Court records
- Official incident reports

---

## Moderate Reliability

Characteristics include:

- Secondary reporting
- Credible journalism
- Industry analysis
- Independent summaries
- Professional blogs with cited evidence

Information should be corroborated whenever practical.

Examples:

- Technology news
- Industry white papers
- Security conference presentations
- Books
- Professional publications

---

## Low Reliability

Characteristics include:

- Anonymous reporting
- Unsourced claims
- Speculation
- Rumors
- Opinion pieces
- Social media without supporting evidence

These sources should not independently support analytical conclusions.

Examples:

- Anonymous forum posts
- Unsourced blog articles
- Unverified screenshots
- Social media speculation

---

# 4. Primary vs Secondary Sources

## Primary Sources

Primary sources originate from direct participants or original evidence.

Examples include:

- CERT advisories
- Incident response reports
- Malware analysis
- Reverse engineering reports
- Vendor bulletins
- Court filings

Primary sources should be preferred whenever available.

---

## Secondary Sources

Secondary sources interpret or summarize primary sources.

Examples include:

- News articles
- Books
- Academic summaries
- Industry reports

Secondary sources should be verified against primary evidence where possible.

---

# 5. Corroboration

Major analytical conclusions should be supported by multiple independent sources whenever practical.

Conflicting reporting should be documented rather than omitted.

---

# 6. Source Documentation

Each source should be documented with sufficient detail to permit independent verification.

Recommended metadata includes:

- Author
- Organization
- Publication Date
- Document Title
- URL or Identifier
- Date Accessed

---

# 7. AI-Generated Content

Artificial Intelligence is not considered a source of evidence.

AI-generated content may assist analysts but shall not be cited as supporting evidence.

Analysts remain responsible for locating and verifying original sources.

---

# 8. Source Conflicts

When sources disagree, analysts should:

- Document the disagreement.
- Evaluate the credibility of each source.
- Explain the reasoning for the adopted conclusion.
- Adjust confidence assessments as appropriate.

---

# 9. Best Practices

Analysts should:

- Prefer primary sources.
- Seek independent corroboration.
- Identify assumptions.
- Distinguish facts from interpretation.
- Document analytical limitations.
- Avoid circular citations.

---

# 10. Examples

| Source | Reliability |
|----------|-------------|
| CERT Advisory | High |
| Microsoft Security Bulletin | High |
| Vendor Malware Analysis | High |
| Peer-Reviewed Journal | High |
| Government Report | High |
| Industry White Paper | Moderate |
| Technology News | Moderate |
| Conference Presentation | Moderate |
| Personal Blog | Low–Moderate |
| Anonymous Forum | Low |
| Social Media Post | Low |
| AI Chat Response | Not Evidence |

---

# 11. Relationship to Confidence

Source Reliability evaluates the trustworthiness of evidence.

Confidence Assessment evaluates the analyst's confidence in a conclusion.

The two concepts are related but independent.

High-quality sources do not automatically produce high-confidence assessments, nor do low-confidence assessments necessarily imply poor sources.