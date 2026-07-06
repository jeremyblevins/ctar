# CTAR Publication Safety Review (CTAR-PSR)

**Version:** 2.0.0  
**Status:** Draft Standard

---

# 1. Purpose

The CTAR Publication Safety Review establishes minimum review requirements before the public release of a Cyber Threat Assessment Report (CTAR).

Its purpose is to reduce the risk of causing unintended harm while preserving analytical transparency and public value.

This review SHALL be completed prior to publication of official CTAR reports.

---

# 2. Guiding Principles

Publication SHALL balance:

- Transparency
- Public benefit
- Technical accuracy
- Operational security
- Ethical responsibility
- Legal obligations

Not every technically correct detail should necessarily be published.

---

# 3. Publication Review Objectives

Reviewers SHOULD determine whether publication could:

- Increase cyber risk
- Expose victims
- Reveal sensitive defensive capabilities
- Interfere with incident response
- Enable malicious activity
- Violate legal obligations

---

# 4. Technical Risk Review

Reviewers SHALL evaluate whether the report includes:

- Exploitable proof-of-concept code
- Active exploit instructions
- Operational malware
- Working command-and-control infrastructure
- Sensitive authentication material
- Private encryption keys
- Credentials
- Active attack infrastructure

Such information SHOULD be removed, summarized, or responsibly disclosed rather than publicly released.

---

# 5. Victim Protection

Reports SHOULD avoid unnecessarily disclosing:

- Personally identifiable information
- Customer information
- Internal network architecture
- Confidential business information
- Sensitive operational details

Victim organizations SHOULD be identified only when disclosure serves a legitimate analytical or public interest.

---

# 6. Responsible Vulnerability Disclosure

When discussing vulnerabilities, analysts SHOULD consider:

- Vendor notification status
- Public disclosure status
- Patch availability
- Active exploitation
- Coordinated vulnerability disclosure practices

CTAR does not replace responsible disclosure processes.

---

# 7. Legal Review

Analysts SHALL consider applicable:

- Copyright law
- Privacy law
- Contractual obligations
- Export controls
- Licensing restrictions
- Court orders

Questions of legal interpretation SHOULD be referred to appropriate legal counsel.

---

# 8. Ethical Review

Reviewers SHOULD assess whether publication:

- Could unnecessarily increase harm.
- Respects responsible disclosure.
- Accurately represents available evidence.
- Avoids sensationalism.
- Maintains analytical objectivity.

---

# 9. Attribution Review

Where threat attribution is discussed, reviewers SHOULD verify that:

- Attribution is supported by evidence.
- Confidence is clearly stated.
- Alternative explanations have been considered.
- Significant uncertainty is disclosed.

Unsupported attribution SHOULD NOT be presented as fact.

---

# 10. Final Publication Checklist

Before publication, reviewers SHOULD confirm:

☐ Evidence has been validated.

☐ Sources have been evaluated.

☐ Confidence assessments are complete.

☐ AI participation has been disclosed.

☐ Sensitive information has been reviewed.

☐ Legal and ethical considerations have been addressed.

☐ Report formatting complies with CTAR-RT.

☐ Required metadata is complete.

---

# 11. Exceptions

In rare circumstances, publication may proceed despite unresolved concerns when:

- Immediate public awareness outweighs potential risks.
- Significant public interest exists.
- Delay would materially increase harm.

Such decisions SHOULD be documented.

---

# 12. Continuous Review

Published CTAR reports MAY be revised when:

- New evidence becomes available.
- Significant errors are identified.
- Sensitive information is later determined to require redaction.
- Confidence assessments materially change.

Revisions SHALL be documented in the report history.

---

# Revision History

| Version | Date | Description |
|----------|------|-------------|
| 1.0.0 | Initial Release | Original Publication Safety Review |
| 2.0.0 | 2026-07-06 | Expanded publication review to include technical, legal, ethical, victim protection, attribution, and responsible disclosure considerations with a standardized pre-publication checklist. |
