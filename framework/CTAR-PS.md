# CTAR Publication Standard (CTAR-PS)

**Version:** 1.0.0\
**Status:** Draft Standard

------------------------------------------------------------------------

# 1. Purpose

The CTAR Publication Standard establishes the minimum requirements for
the preparation, formatting, identification, and publication of official
Cyber Threat Assessment Reports (CTARs).

Its objectives are to:

-   Ensure consistency across published CTARs
-   Improve readability and professional presentation
-   Support long-term archival
-   Promote reproducibility
-   Facilitate automated publication
-   Establish a recognizable CTAR visual identity

This document is normative for all official CTAR publications.

------------------------------------------------------------------------

# 2. Relationship to Other Framework Documents

This standard complements:

-   CTAR-GC (Governance Charter)
-   CTAR-MS (Methodology Standard)
-   CTAR-RT (Report Template)
-   CTAR-AIPP (AI Participation Policy)
-   CTAR-DAP (Data Authenticity Policy)
-   CTAR-PSR (Publication Safety Review)

Where conflicts exist, CTAR-GC SHALL take precedence.

------------------------------------------------------------------------

# 3. Publication Principles

Official CTAR publications SHALL be:

-   Evidence-based
-   Professionally formatted
-   Technically accurate
-   Accessible
-   Reproducible
-   Traceable
-   Versioned
-   Publicly identifiable

------------------------------------------------------------------------

# 4. Publication Metadata

Every CTAR SHALL include:

-   Report ID
-   Title
-   Report Class
-   Framework Version
-   Publication Version
-   Publication Date
-   Publication Status
-   Analyst(s)
-   Confidence
-   AI Participation Statement
-   Revision History

------------------------------------------------------------------------

# 5. CTAR Report Identifier (CRI)

Every official report SHALL receive a permanent Report ID.

Example:

`CTAR-2026-PR-0001`

The Report ID SHALL remain constant throughout the report lifecycle.

------------------------------------------------------------------------

# 6. Standard Filename Convention

Every published artifact SHALL use:

`CTAR-<YEAR>-<CLASS>-<SEQUENCE>-<DESCRIPTOR>.<EXT>`

Example:

`CTAR-2026-PR-0001-PAYPAL-UPCOMING-POLICY-PRIVACY-ASSESSMENT.pdf`

All derivative artifacts SHALL retain the identical basename. Only the
file extension SHALL differ.

------------------------------------------------------------------------

# 7. Descriptor Requirements

Descriptors SHALL:

-   Be uppercase
-   Use hyphen separators
-   Describe the report subject
-   Avoid punctuation
-   Avoid analytical conclusions
-   Remain reasonably concise

------------------------------------------------------------------------

# 8. Publication Formats

Official CTAR publications MAY be distributed as:

-   Markdown
-   PDF
-   HTML
-   DOCX

Every format SHALL contain equivalent analytical content.

------------------------------------------------------------------------

# 9. Required Report Structure

Official CTAR publications SHALL include:

1.  Cover Page
2.  Executive Summary
3.  Key Judgments
4.  Purpose
5.  Scope
6.  Evidence
7.  Technical Analysis
8.  Impact Assessment
9.  Analyst Assessment
10. Recommendations
11. Confidence Assessment
12. Sources
13. AI Participation
14. Revision History
15. About the CTAR Framework

------------------------------------------------------------------------

# 10. Cover Page Requirements

The cover SHALL include:

-   CTAR logo
-   Report title
-   Report ID
-   Report class
-   Publication date
-   Framework version
-   Publication version
-   Publication status
-   Analyst
-   Optional hero image

------------------------------------------------------------------------

# 11. Headers and Footers

Header:

`Cyber Threat Assessment Report`

Footer:

`CTAR-2026-PR-0001 | Public Release | Page X of Y`

------------------------------------------------------------------------

# 12. Confidence Presentation

Confidence SHALL use the CTAR confidence scale:

-   High
-   Moderate
-   Low

Every key judgment SHALL include a confidence assessment.

------------------------------------------------------------------------

# 13. Evidence Presentation

Evidence SHALL be visually distinguishable from analyst assessment.

------------------------------------------------------------------------

# 14. Sources

Every CTAR SHALL include complete citations. Internet sources SHOULD
include clickable hyperlinks where supported.

------------------------------------------------------------------------

# 15. About the CTAR Framework

Every public CTAR SHALL reference:

https://www.ctarframework.org

------------------------------------------------------------------------

# 16. AI Participation

Official publications SHALL disclose material AI participation
consistent with CTAR-AIPP.

------------------------------------------------------------------------

# 17. Publication Status

Reports SHALL identify one of:

-   Draft
-   Review Draft
-   Public Release
-   Archived
-   Superseded

------------------------------------------------------------------------

# 18. Accessibility

Publications SHOULD support searchable text, accessible headings,
tables, and screen readers where practical.

------------------------------------------------------------------------

# 19. Versioning

Publications SHALL use Semantic Versioning and maintain a revision
history.

------------------------------------------------------------------------

# 20. Future Enhancements

Future revisions MAY include:

-   QR codes
-   DOI support
-   ORCID integration
-   Digital signatures
-   YAML and JSON metadata
-   Machine-readable schemas
-   Automated publication pipelines

------------------------------------------------------------------------

# Revision History

  -----------------------------------------------------------------------
  Version                  Date           Description
  ------------------------ -------------- -------------------------------
  1.0.0                    2026-07-15     Initial Publication Standard
                                          establishing report
                                          identification, metadata, file
                                          naming, publication formats,
                                          report structure,
                                          accessibility, and presentation
                                          requirements.

  -----------------------------------------------------------------------
