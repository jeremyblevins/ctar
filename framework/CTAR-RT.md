# CTAR Report Template Standard (CTAR-RT)

**Version:** 2.0.0  
**Status:** Draft Standard

---

# 1. Purpose

This standard defines the required structure and presentation of official Cyber Threat Assessment Reports (CTARs). Its purpose is to ensure consistency, readability, and analytical transparency across all CTAR publications.

This document specifies *how findings are communicated*. Analytical methods are defined in CTAR-MS.

---

# 2. Report Header

Every CTAR SHALL begin with the following metadata.

| Field | Required |
|---------|----------|
| CTAR Identifier | Yes |
| Report Title | Yes |
| Report Profile | Yes |
| Publication Date | Yes |
| Framework Version | Yes |
| Analyst | Optional |
| Organization | Optional |
| Revision | Yes |

Example:

```
CTAR-2026-0706-001

Gitea Docker Remote Code Execution Campaign

Operational CTAR

Published:
6 July 2026

Framework Version:
2.0

Revision:
1.0
```

---

# 3. Executive Summary (Required)

The Executive Summary SHALL provide a concise overview suitable for decision-makers.

It SHOULD include:

- What happened
- Why it matters
- Who is affected
- Overall risk
- Recommended actions

Length SHOULD generally not exceed one page.

---

# 4. Key Judgments (Required)

Key Judgments summarize the principal analytical conclusions.

Each judgment SHOULD include an associated confidence level.

Example:

• Threat actors are opportunistically scanning public Gitea instances.

Confidence: High

---

# 5. Situation Overview (Required)

Provides context for the assessment.

May include:

- Timeline
- Background
- Current activity
- Geographic scope
- Organizational impact

---

# 6. Technical Analysis (Required)

This section presents the evidence supporting the assessment.

May include:

- Vulnerability analysis
- Malware behavior
- Network observations
- Indicators of Compromise
- MITRE ATT&CK mapping
- Exploit chain
- Technical diagrams

Evidence SHALL be clearly separated from analytical interpretation.

---

# 7. Threat Assessment (Required)

Describes:

- Threat actor capability
- Intent
- Opportunity
- Likelihood
- Operational impact

This section synthesizes evidence into analytical conclusions.

---

# 8. Risk Assessment (Required)

Risk SHOULD consider:

- Likelihood
- Impact
- Exposure
- Detection capability
- Mitigation status

Frameworks such as NIST RMF, FAIR, or CVSS MAY be referenced where appropriate.

---

# 9. Confidence Assessment (Required)

Confidence SHALL be assigned to significant analytical judgments.

Recommended values:

- High
- Moderate
- Low

The rationale for confidence SHOULD be briefly explained.

---

# 10. Intelligence Gaps (Required)

This section identifies information unavailable at publication.

Examples include:

- Unknown attribution
- Missing forensic artifacts
- Incomplete victim reporting
- Pending vulnerability analysis

Explicitly identifying gaps improves analytical transparency.

---

# 11. Recommended Actions (Required)

Recommendations SHOULD distinguish between:

Immediate Actions

Near-Term Actions

Strategic Improvements

Recommendations SHOULD be actionable and technically feasible.

---

# 12. Sources (Required)

Sources SHALL be cited using the Source Reliability Matrix.

References SHOULD distinguish between:

Primary Sources

Secondary Sources

Supporting References

---

# 13. AI Participation Statement (Required)

Every official CTAR SHALL disclose the role of artificial intelligence.

Example:

> Portions of this report were assisted by artificial intelligence for drafting, summarization, and editorial refinement. Evidence validation, analytical conclusions, confidence assessments, and final publication approval were performed by a human analyst.

---

# 14. Optional Sections

The following sections MAY be included when applicable.

## MITRE ATT&CK Mapping

## Indicators of Compromise

## Detection Guidance

## Threat Hunting Queries

## YARA Rules

## Sigma Rules

## Timeline

## Campaign Chronology

## Historical Context

## Lessons Learned

## Appendices

---

# 15. Historical CTAR Requirements

Historical CTARs SHOULD additionally include:

- Historical Background
- Chronological Reconstruction
- Source Criticism
- Strategic Significance
- Enduring Lessons

Where uncertainty exists, reconstructed events SHALL be distinguished from documented historical facts.

---

# 16. Formatting Requirements

Official CTAR reports SHOULD:

- Use consistent heading hierarchy.
- Clearly label confidence levels.
- Separate evidence from assessment.
- Avoid unnecessary jargon.
- Use tables where appropriate.
- Clearly identify assumptions.

---

# Revision History

| Version | Date | Description |
|----------|------|-------------|
| 1.0.0 | Initial Release | Original report template |
| 2.0.0 | 2026-07-06 | Complete redesign aligning report presentation with CTAR Governance and Methodology standards. Introduced required vs. optional sections, standardized confidence reporting, intelligence gaps, AI participation statements, and profile-specific guidance. |
