# CTAR Report Template (CTAR-RT)

**Document ID:** CTAR-RT  
**Version:** 1.1.0  
**Status:** Current  
**Effective Date:** 1 July 2026

## Normative Language

The key words **"MUST"**, **"MUST NOT"**, **"REQUIRED"**, **"SHALL"**, **"SHALL NOT"**, **"SHOULD"**, **"SHOULD NOT"**, **"RECOMMENDED"**, **"MAY"**, and **"OPTIONAL"** in this document are to be interpreted as described in RFC 2119 and RFC 8174 when, and only when, they appear in all capital letters.

---

# Cyber Threat Assessment Report (CTAR)

**CTAR ID:** CTAR-YYYY-NNNN  
**Report Version:** 1.0  
**Framework Version:** 1.1.0  
**Classification:** Public Release  
**Publication Date:** YYYY-MM-DD  
**Author(s):**  
**Reviewer(s):**  
**Assessment Type:**  
**Status:** Draft | Review | Final

---

# Executive Summary

Provide a concise summary. Significant factual statements **MUST** be traceable to one or more Evidence IDs. of the assessment, including the threat, principal findings, and overall conclusions.

---

# Assessment Scope

Describe:

- Subject
- Objectives
- Scope limitations
- Intended audience
- Intelligence questions addressed

---

# Historical Context

Provide relevant historical or operational background necessary to understand the assessment.

---

# Threat Overview

Summarize:

- Threat name
- Aliases
- Category
- Discovery date
- Current status
- Platforms affected

---

# Technical Assessment

Describe technical characteristics including:

- Initial access
- Execution
- Persistence
- Privilege escalation (if applicable)
- Defense evasion
- Discovery
- Lateral movement
- Collection
- Command and control
- Impact

Not every subsection applies to every assessment.

---

# Timeline

Provide a chronological reconstruction of significant events.

---

# Indicators of Compromise (IOCs)

Where applicable, document:

- File hashes
- Filenames
- Domains
- URLs
- IP addresses
- Registry artifacts
- Processes
- Services
- Email subjects
- Attachments

Clearly distinguish:

- Observed
- Historical
- Inferred

---

# MITRE ATT&CK Mapping

Document applicable ATT&CK techniques and justify mappings.

---

# Associated Vulnerabilities

Document associated:

- CVEs
- CWEs
- Advisories

If none exist, explicitly state:

**Associated CVEs: None**

---

# Operational Impact

Describe:

- Systems affected
- Geographic impact
- Business disruption
- Financial estimates
- Operational consequences

---

# Attribution Assessment

Document:

- Suspected actor(s)
- Supporting evidence
- Alternative hypotheses
- Confidence assessment

---

# Defensive Measures

Summarize:

- Mitigations
- Detection opportunities
- Preventive controls
- Recovery recommendations

---

# Confidence Assessment

Assign confidence ratings to major analytical conclusions.

Example:

| Assessment | Confidence |
|------------|------------|
| Attribution | Moderate |
| Timeline | High |
| Technical Analysis | High |

---

# Source Reliability Assessment

Summarize the quality of sources used.

---

# Data Authenticity Review

Document:

- Verified facts
- Estimated information
- Assumptions
- Analytical limitations

---

# Ethical Considerations

Identify:

- Publication risks
- Sensitive information
- Omitted technical details

---

# Lessons Learned

Summarize strategic and operational lessons derived from the assessment.

---

# Analyst Verification Checklist

The analyst shall verify:

- [ ] Every factual claim has supporting evidence.
- [ ] Sources have been evaluated.
- [ ] IOCs have been validated.
- [ ] ATT&CK mappings are supported.
- [ ] CVEs have been researched.
- [ ] Confidence assessments are justified.
- [ ] Assumptions are documented.
- [ ] Publication Safety Review completed.

---

# Appendix A – Evidence Register

Every CTAR **MUST** include an Evidence Register.

| ID | Evidence | Type | Publication Date | Source Organization | Reliability | Authenticity | Used In | Hyperlink |
|----|----------|------|------------------|---------------------|-------------|--------------|---------|-----------|

---

# Appendix B – Evidence Traceability Matrix (ETM)

Every significant finding **MUST** map to one or more Evidence IDs.

| Finding | Supporting Evidence |
|----------|---------------------|

---

# References

Reports **MUST** provide complete bibliographic references.

Evidence **MUST** be cited inline using Evidence IDs (e.g., [E-001]).

---

<!-- Removed in v1.1.0: Replaced by required Evidence Register -->

| Evidence ID | Description | Source | Reliability |
|--------------|-------------|--------|-------------|

---

# Appendix C – Supporting Artifacts (OPTIONAL)

Examples include:

- Timelines
- IOC tables
- Network diagrams
- Screenshots
- Hash listings
- Reporting artifacts