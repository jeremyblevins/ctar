# CTAR Framework 1.1.0 Specification

## Purpose

This specification defines the Cyber Threat Assessment Report (CTAR)
Framework as a modular, evidence-based methodology for producing
professional cyber threat assessments.

## Architecture

### Part I: Governance

-   Governance Charter
-   Code of Ethics
-   AI Participation Policy
-   Publication Safety Review

### Part II: Analytical Tradecraft

-   Methodology Standard
-   Analytical Framework
-   Source Reliability Matrix
-   Data Authenticity Policy

### Part III: Report Construction

-   Report Template
-   Report Profiles
-   Style Guide
-   Annex Policy

### Part IV: Domain Guides

-   Historical Practice Guide
-   ATT&CK Mapping Guide
-   Defensive Mapping Guide

## Normative Language

The key words SHALL, SHOULD, MAY, MUST, and SHOULD NOT are interpreted
as described in RFC 2119.

## Intelligence Lifecycle

Direction → Collection → Validation → Correlation → Analysis → Review →
Publication → Lessons Learned.

## Evidence Model

Evidence SHALL be distinguished from interpretation and analyst
assessment. Every key judgment SHALL include an explicit confidence
statement.

## Report Classes

Operational, Historical, Vulnerability, Threat Actor, Campaign, Product
Risk, Strategic.

## Required Report Sections

1.  Intelligence Header
2.  Executive Summary
3.  Purpose
4.  Key Judgments
5.  Evidence
6.  Technical Analysis
7.  Impact Assessment
8.  Analyst Assessment
9.  Recommendations
10. Confidence
11. Sources
12. Revision History

## Historical CTAR Requirements

Historical reports SHOULD additionally include Historical Context,
Timeline, Strategic Significance, Enduring Lessons, and Influence on
Future Operations.

## Annexes

ATT&CK mappings, D3FEND mappings, timelines, technical appendices,
educational appendices, engineering analyses, and bibliographies MAY be
attached.

## Versioning

Semantic Versioning is adopted.


## Publication Filename Convention

All official CTAR artifacts SHALL use:

`CTAR-<YEAR>-<CLASS>-<SEQUENCE>-<DESCRIPTOR>.<EXT>`

All derivative publication formats SHALL retain the identical basename.
