# CTAR Methodology Specification (CTAR-MS)

**Document ID:** CTAR-MS  
**Version:** 1.1.0  
**Status:** Current  
**Effective Date:** 1 July 2026

---

## Normative Language

The key words **"MUST"**, **"MUST NOT"**, **"REQUIRED"**, **"SHALL"**, **"SHALL NOT"**, **"SHOULD"**, **"SHOULD NOT"**, **"RECOMMENDED"**, **"MAY"**, and **"OPTIONAL"** in this document are to be interpreted as described in RFC 2119 and RFC 8174 when, and only when, they appear in all capital letters.

---

# 1. Purpose

The Cyber Threat Assessment Report (CTAR) Methodology Specification establishes the standard analytical process for producing evidence-based cyber threat intelligence assessments.

The objective of the CTAR methodology is to provide a repeatable, transparent, and defensible framework that enables analysts to transform available evidence into structured intelligence products suitable for operational, educational, and research purposes.

The methodology emphasizes:

- Evidence over opinion
- Transparency over authority
- Reproducibility over intuition
- Human accountability over automation

---

# 2. Scope

This methodology applies to all reports produced under the CTAR Framework.

Applicable assessment types include:

- Historic Malware Analysis
- Threat Actor Assessments
- Vulnerability Assessments
- Campaign Assessments
- Incident Assessments
- Technology Risk Assessments
- Emerging Threat Assessments

---

# 3. Guiding Principles

The CTAR methodology is founded upon the following principles.

## Evidence-Based Analysis

Every analytical conclusion **MUST** be traceable to documented evidence.

## Transparency

Assumptions, limitations, and confidence should be documented.

## Reproducibility

Independent analysts reviewing the same evidence should be capable of reaching substantially similar conclusions.

## Analytical Integrity

Evidence **MUST NOT** be omitted to support predetermined conclusions.

## Human Accountability

Artificial Intelligence **MAY** assist analytical work, but responsibility for published assessments **MUST** remain with the human analyst.

---

# 4. Analytical Workflow

The CTAR methodology consists of eight phases.

## Phase 1 – Define the Assessment

Identify:

- Subject
- Scope
- Intended audience
- Assessment objectives
- Intelligence questions

Deliverable:

Assessment Plan

---

## Phase 2 – Evidence Collection

Collect available evidence including:

- Government publications
- Vendor analyses
- Academic research
- Technical reports
- Historical reporting
- Primary artifacts

Deliverable:

Evidence Package

---

## Phase 3 – Evidence Validation

Validate collected information.

Activities include:

- Authenticity verification
- Source corroboration
- IOC verification
- Timeline verification
- Attribution review

Deliverable:

Validated Evidence Set

---

## Phase 4 – Analytical Assessment

Analyze the validated evidence.

Activities include:

- Timeline reconstruction
- Technical analysis
- Impact assessment
- Attribution assessment
- Confidence assessment

Deliverable:

Assessment Findings

---

## Phase 5 – Report Development

Produce a CTAR using the Report Template.

Required sections **MUST** follow the CTAR Report Template.

Deliverable:

Draft CTAR

---

## Phase 6 – Human Verification

The analyst **MUST** verify:

- factual statements
- source citations
- technical accuracy
- IOC validity
- analytical conclusions

Artificial Intelligence **MUST NOT** be considered authoritative evidence.

Deliverable:

Verified Assessment

---

## Phase 7 – Publication Safety Review

Evaluate the report for:

- sensitive information
- operational risk
- weaponizable content
- ethical considerations

Deliverable:

Approved Publication

---

## Phase 8 – Publication

Publish the finalized assessment.

---

# 5. Evidence Standards

Evidence should be categorized as:

- Primary
- Secondary
- Tertiary

Every significant analytical conclusion **MUST** be supported by one or more documented evidence items.

---

# 5A. Evidence Traceability Standard

Every evidence item **MUST** receive a unique Evidence ID (e.g., E-001).

Every CTAR **MUST** include:

- Evidence Register
- Evidence Traceability Matrix (ETM)
- References

Every significant analytical conclusion **MUST** cite one or more Evidence IDs.


---

# 6. Source Evaluation

Sources **MUST** be evaluated using the CTAR Source Reliability Matrix.

Factors include:

- authority
- independence
- timeliness
- corroboration
- authenticity

---

# 7. Confidence Assessment

Each major conclusion shall receive a confidence rating.

Recommended categories:

- High
- Moderate
- Low

Confidence reflects the quality of supporting evidence rather than certainty.

---

# 8. Indicators of Compromise

Historical and operational indicators shall be distinguished.

Where possible:

- verify IOCs
- identify provenance
- document confidence
- distinguish observed from inferred indicators

---

# 9. Artificial Intelligence

AI may assist with:

- summarization
- drafting
- organization
- editing

AI shall not replace:

- evidence validation
- analytical judgment
- confidence assessment
- publication approval

---

# 10. Deliverables

Every completed CTAR **MUST** include:

- Executive Summary
- Assessment Scope
- Historical Context
- Threat Overview
- Technical Assessment
- Timeline
- Impact Assessment
- Attribution Assessment
- Indicators of Compromise
- Defensive Measures
- Confidence Assessment
- Source Reliability Assessment
- Data Authenticity Review
- Appendix A – Evidence Register
- Appendix B – Evidence Traceability Matrix (ETM)
- References
- Lessons Learned

---

# 11. Analyst Responsibilities

Analysts are responsible for:

- validating evidence
- documenting assumptions
- identifying uncertainty
- distinguishing fact from analysis
- maintaining objectivity

---

# 12. Continuous Improvement

The CTAR Framework shall evolve through documented revisions.

Changes shall be tracked in the project CHANGELOG.

Major revisions should preserve backward compatibility where practical.