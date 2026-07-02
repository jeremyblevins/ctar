# Cyber Threat Assessment Report (CTAR)

**CTAR ID:** CTAR-2000-0001\
**Version:** 1.0.0\
**Classification:** Public Release\
**Publication Date:** 2026-07-01\
**Threat Category:** Historic Malware Analysis\
**Subject:** ILOVEYOU (Love Letter) Worm

------------------------------------------------------------------------

# Executive Summary

The **ILOVEYOU** worm, also known as **Love Letter** or **Love Bug**,
emerged on **4 May 2000** and rapidly became one of the most destructive
malware outbreaks in Internet history. Distributed through a Visual
Basic Script (VBScript) email attachment, the worm relied on social
engineering rather than a software vulnerability. Once executed, it
propagated through Microsoft Outlook, overwrote selected file types,
modified the Windows Registry for persistence, and attempted to download
additional malicious components.

The outbreak infected an estimated 45--50 million computers worldwide
within days and caused an estimated **USD \$5--10 billion** in damages
through business interruption, recovery efforts, and lost productivity.

------------------------------------------------------------------------

# Assessment Scope

This report provides a historical cyber threat assessment of the
ILOVEYOU worm for educational purposes. It documents the malware's
characteristics, operational impact, attribution, defensive lessons, and
analytical confidence in accordance with the CTAR Framework.

------------------------------------------------------------------------

# Historical Context

At the time of the outbreak:

-   Microsoft Windows 95/98 and Windows NT dominated enterprise
    desktops.
-   Microsoft Outlook was widely deployed.
-   Email attachment filtering was uncommon.
-   Security awareness training was limited.
-   Antivirus updates were less frequent than modern cloud-based
    protection.

------------------------------------------------------------------------

# Threat Overview

  Attribute         Value
  ----------------- -----------------------
  Malware Name      ILOVEYOU
  Also Known As     Love Letter, Love Bug
  Malware Type      Email Worm
  Language          VBScript
  First Observed    4 May 2000
  Initial Access    Email Attachment
  Target Platform   Microsoft Windows

------------------------------------------------------------------------

# Technical Characteristics

## Initial Access

Email Subject:

`ILOVEYOU`

Attachment:

`LOVE-LETTER-FOR-YOU.TXT.vbs`

Because Windows hid known file extensions by default, many users saw
only `LOVE-LETTER-FOR-YOU.TXT`, increasing the likelihood of execution.

## Behavior

After execution the worm:

-   Copied itself into Windows system directories.
-   Modified Registry startup keys.
-   Sent itself to Outlook contacts.
-   Replaced selected media and script files.
-   Attempted propagation through shared drives.
-   Downloaded credential-stealing components.

------------------------------------------------------------------------

# Attack Lifecycle

  Phase              Activity
  ------------------ -----------------------------------------
  Initial Access     Malicious email attachment
  Execution          User opened VBScript attachment
  Persistence        Registry modifications
  Discovery          Outlook address enumeration
  Lateral Movement   Email self-propagation
  Collection         Password theft component
  Impact             File destruction and global propagation

------------------------------------------------------------------------

# Timeline

  Date              Event
  ----------------- ----------------------------------------------
  4 May 2000        First observed infections in the Philippines
  4 May 2000        Global propagation begins
  5 May 2000        Major organizations disconnect email systems
  5--6 May 2000     Antivirus signatures released
  Following weeks   Global remediation efforts

------------------------------------------------------------------------

# Operational Impact

-   Estimated infections: **45--50 million systems**
-   Estimated damages: **USD \$5--10 billion**
-   Widespread disruption across government, finance, education,
    military, and private industry.

------------------------------------------------------------------------

# Attribution Assessment

The malware is widely attributed to **Onel de Guzman** of the
Philippines. Contemporary reporting and subsequent investigations
indicate the worm evolved from earlier password-stealing scripts. No
successful criminal prosecution followed because Philippine law at the
time did not specifically criminalize malware creation and release.

------------------------------------------------------------------------

# MITRE ATT&CK Mapping

  Technique   Description
  ----------- -----------------------------------
  T1566.001   Phishing Attachment
  T1059       Command and Scripting Interpreter
  T1112       Modify Registry
  T1083       File and Directory Discovery
  T1105       Ingress Tool Transfer

------------------------------------------------------------------------

# Indicators of Compromise (Historic)

## Email Subject

`ILOVEYOU`

## Attachment

`LOVE-LETTER-FOR-YOU.TXT.vbs`

## Modified File Types

-   JPG
-   JPEG
-   MP3
-   VBS
-   JS
-   JSE

**Associated CVEs:** None. The worm relied on social engineering and
legitimate Windows functionality rather than exploiting a software
vulnerability.

------------------------------------------------------------------------

# Defensive Measures

-   Block executable email attachments.
-   Disable unnecessary scripting.
-   Display full filename extensions.
-   Maintain current endpoint protection.
-   Implement email gateway filtering.
-   Conduct regular security awareness training.

------------------------------------------------------------------------

# Confidence Assessment

  Assessment                   Confidence
  ---------------------------- ------------
  Malware functionality        High
  Timeline                     High
  Technical behavior           High
  Attribution                  Moderate
  Financial impact estimates   Moderate

------------------------------------------------------------------------

# Source Reliability Assessment

  Source                        Reliability
  ----------------------------- -------------
  CERT advisories               High
  Microsoft documentation       High
  Antivirus vendor analyses     High
  Academic publications         High
  Contemporary news reporting   Moderate

------------------------------------------------------------------------

# Data Authenticity Review

Verified facts include malware behavior, propagation method, persistence
mechanisms, and timeline. Infection counts and financial damages vary
across sources and should be treated as informed estimates.

------------------------------------------------------------------------

# Ethical Considerations

This report intentionally excludes malware source code, exploit
instructions, or operational guidance that would facilitate misuse. It
is intended solely for cybersecurity education and historical analysis.

------------------------------------------------------------------------

# Lessons Learned

-   Social engineering can rival software exploits in effectiveness.
-   User awareness is a critical security control.
-   Secure default configurations matter.
-   Layered defenses reduce organizational risk.
-   Evidence-based analysis improves the quality and reproducibility of
    cyber threat intelligence.

------------------------------------------------------------------------

# Overall Assessment

The ILOVEYOU worm remains one of the most significant malware incidents
in Internet history. Although technically simple, it demonstrated the
global consequences of social engineering, insecure defaults, and rapid
automated propagation. As a historical case study, it provides an
excellent example for applying the CTAR Framework and practicing
evidence-based cyber threat analysis.
