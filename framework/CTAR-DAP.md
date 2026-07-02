# CTAR Data Authenticity Policy (CTAR-DAP)

**Document ID:** CTAR-DAP  
**Version:** 1.1.0  
**Status:** Current  
**Effective Date:** 1 July 2026

---

## Normative Language

The key words **"MUST"**, **"MUST NOT"**, **"REQUIRED"**, **"SHALL"**, **"SHALL NOT"**, **"SHOULD"**, **"SHOULD NOT"**, **"RECOMMENDED"**, **"MAY"**, and **"OPTIONAL"** in this document are to be interpreted as described in RFC 2119 and RFC 8174 when, and only when, they appear in all capital letters.

---

# 1. Purpose

The CTAR Data Authenticity Policy establishes requirements for verifying the authenticity and integrity of evidence used in Cyber Threat Assessment Reports (CTARs).

The objective is to ensure that analytical conclusions are based upon information that is demonstrably authentic, traceable, and reproducible.

---

# 2. Scope

This policy applies to all evidence referenced in CTAR assessments, including:

- Documents
- Technical reports
- Indicators of Compromise (IOCs)
- Malware analysis
- Screenshots
- Log files
- Network captures
- Timeline data
- Digital artifacts

---

# 3. Guiding Principles

Evidence should be:

- Authentic
- Traceable
- Reproducible
- Corroborated
- Properly attributed

Analysts shall distinguish verified information from assumptions or estimates.

---

# 4. Evidence Categories

Each Evidence Register entry **MUST** receive exactly one authenticity designation.

Approved authenticity designations are:

- **Verified**
- **Corroborated**
- **Reported**
- **Disputed**
- **Retracted**

Analysts **MUST** distinguish verified facts from assumptions and estimates.

Evidence with a status of **Reported** or **Disputed** **SHOULD NOT** serve as the sole basis for significant analytical conclusions.

## Verified

Evidence independently confirmed through authoritative or corroborating sources.

Examples:

- CERT advisories
- Official vendor bulletins
- Court documents
- Digitally signed reports

---

## Corroborated

Evidence supported by multiple independent sources but lacking direct confirmation.

---

## Reported

Evidence appearing in a single credible source.

Reported information **MUST** be clearly identified as such.

---

## Unverified

Evidence that has not been independently validated.

Unverified evidence **SHOULD NOT** serve as the sole basis for significant analytical conclusions.


## Verified

Evidence independently confirmed through authoritative or corroborating sources.

Examples:

- CERT advisories
- Official vendor bulletins
- Court documents
- Digitally signed reports

---

## Corroborated

Evidence supported by multiple independent sources but lacking direct confirmation.

---

## Reported

Evidence appearing in a single credible source.

Reported information should be clearly identified as such.

---

## Unverified

Evidence that has not been independently validated.

Unverified information shall not serve as the sole basis for significant analytical conclusions.

---

# 5. Authenticity Verification

Where practical, analysts should verify:

- Publication source
- Document integrity
- Digital signatures
- File hashes
- Publication dates
- Original authorship

---

# 6. IOC Verification

Indicators of Compromise should be verified before inclusion.

Examples include:

- File hashes
- Domains
- URLs
- IP addresses
- Registry keys
- Process names

Analysts should identify whether IOCs are:

- Observed
- Historical
- Inferred

---

# 7. Historical Evidence

Historical assessments frequently rely upon archived material.

Analysts should distinguish:

- Contemporary reporting
- Later historical analysis
- Retrospective interpretation

---

# 8. Artificial Intelligence

Artificial Intelligence may assist in locating potential evidence.

AI-generated content **MUST NOT** be treated as evidence.

All AI-generated information **MUST** be independently verified before inclusion in a CTAR.

---

# 9. Estimates and Assumptions

Analysts shall explicitly identify:

- Estimated values
- Assumptions
- Unknowns
- Conflicting information

Estimates should never be presented as established fact.

---

# 10. Evidence Traceability

Every significant analytical conclusion should be traceable to one or more documented evidence sources.

Every CTAR **MUST** include an Evidence Register and an Evidence Traceability Matrix (ETM) identifying the relationship between evidence and analytical conclusions.

---

# 11. Prohibited Practices

Analysts shall not:

- Fabricate evidence.
- Alter technical artifacts.
- Remove contextual information.
- Present AI-generated text as original evidence.
- Misrepresent confidence or authenticity.

---

# 12. Relationship to Other CTAR Documents

This policy should be used in conjunction with:

- CTAR-MS (Methodology Specification)
- CTAR-SRM (Source Reliability Matrix)
- CTAR-AIPP (Artificial Intelligence Participation Policy)
- CTAR-PSR (Publication Safety Review)