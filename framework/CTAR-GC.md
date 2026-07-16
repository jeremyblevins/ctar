# CTAR Governance Charter (CTAR-GC)

**Version:** 1.1.0\
**Status:** Draft Standard

## 1. Purpose

This Governance Charter establishes the governing principles,
organizational structure, and lifecycle management processes for the
Cyber Threat Assessment Report (CTAR) Framework. It ensures CTAR remains
an open, evidence-based, vendor-neutral methodology for producing cyber
threat assessments.

## 2. Scope

This charter governs:

-   The CTAR Framework
-   Methodology standards
-   Report templates
-   Analytical guidance
-   Domain-specific practice guides
-   Supporting annexes
-   Reference implementations
-   Official publications

## 3. Guiding Principles

The framework SHALL be:

-   Evidence-driven
-   Objective
-   Transparent
-   Reproducible
-   Vendor-neutral
-   Technically accurate
-   Ethically responsible

Evidence SHALL be clearly distinguished from interpretation and analyst
judgment.

## 4. Framework Architecture

The CTAR Framework consists of:

1.  Governance Documents
2.  Methodology Standards
3.  Analytical Tradecraft
4.  Report Standards
5.  Domain Practice Guides
6.  Annexes

## 5. Report Profiles

The following report classes are officially recognized:

-   Operational CTAR
-   Historical CTAR
-   Vulnerability CTAR
-   Threat Actor CTAR
-   Campaign CTAR
-   Strategic CTAR
-   Product Risk CTAR

Additional report profiles MAY be approved through the framework change
process.

## 6. Governance Roles

### Framework Maintainer

Responsible for overall stewardship of the framework.

### Technical Editor

Maintains consistency, terminology, formatting, and document quality.

### Contributing Analyst

Authors or revises framework documents and CTAR products.

### Peer Reviewer

Evaluates technical accuracy, analytical rigor, and adherence to
standards.

### Release Manager

Coordinates versioning, publication, and archival of official releases.

## 7. Normative Language

Normative terms such as SHALL, SHOULD, MAY, MUST, and SHOULD NOT are
interpreted according to RFC 2119 conventions.

## 8. Versioning

CTAR adopts Semantic Versioning.

-   Major: Breaking structural or methodological changes.
-   Minor: New capabilities that preserve compatibility.
-   Patch: Editorial corrections and clarifications.

## 9. Change Control

Framework modifications SHALL follow this lifecycle:

1.  Proposal
2.  Technical Review
3.  Governance Approval
4.  Version Assignment
5.  Publication
6.  Archival of Superseded Version

## 10. Intelligence Independence

Analysts SHALL:

-   Separate evidence from assessment.
-   Explicitly identify assumptions.
-   State confidence for key judgments.
-   Document significant conflicting evidence when available.

## 11. Historical CTAR Governance

Historical CTARs SHOULD include:

-   Historical Context
-   Chronology
-   Source Criticism
-   Technical Reconstruction
-   Strategic Significance
-   Enduring Lessons

Confirmed facts SHALL be distinguished from reconstructed events and
analyst interpretation.

## 12. Publication Policy

Official framework releases SHALL include:

-   Revision history
-   Change summary
-   Version identifier
-   Publication date

## 13. Deprecation Policy

Deprecated documents SHALL remain archived for at least one major
framework release and SHALL clearly identify their replacement.

## 14. Quality Assurance

Framework documents SHOULD undergo peer review before release and SHOULD
maintain internal consistency through cross-references.

## 15. Future Roadmap

Future governance enhancements may include:

-   Machine-readable schemas
-   Digital signatures
-   Conformance testing
-   API governance
-   Collaborative editorial workflows

## 16. Publication File Naming

Official CTAR publications SHALL use the standardized filename convention:

`CTAR-<YEAR>-<CLASS>-<SEQUENCE>-<DESCRIPTOR>.<EXT>`

Where the descriptor is uppercase and hyphen-separated. All derivative artifacts (Markdown, PDF, HTML, DOCX, etc.) SHALL share the identical basename and differ only by file extension.

## Revision History

  -----------------------------------------------------------------------
  Version                  Date           Description
  ------------------------ -------------- -------------------------------
  1.0.0                    Initial        Original Governance Charter
                           Release        

  1.1.0                    2026-07-06     Expanded governance for modular
                                          CTAR framework, report
                                          profiles, semantic versioning,
                                          change control, and historical
                                          CTAR support.
  -----------------------------------------------------------------------
