# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

An actively targeted vulnerability has been identified in SmarterTools SmarterMail, tracked as CVE-2025-52691, with a CVSS score of 10.0 (Critical). The flaw allows unauthenticated attackers to upload arbitrary files to any location on the mail server, potentially resulting in remote code execution (RCE).
 

 The **Outbreak Response - SmarterTools SmarterMail RCE** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/smartertools-smartermail-rce) contains information about the outbreak alert **Outbreak Response - SmarterTools SmarterMail RCE**. 

## Background: 

SmarterTools SmarterMail is an email and collaboration server positioned as an alternative to Microsoft Exchange. CVE-2025-52691 has been added to CISA’s Known Exploited Vulnerabilities (KEV) catalog as of January 26, 2026, indicating confirmed exploitation in the wild.


Successful exploitation could allow threat actors to gain full control of the affected mail server, deploy web shells, establish persistence, and pivot deeper into the environment. Public technical analysis and exploit research indicate active attacker interest and weaponization. 

## Announced: 

SmarterTools has released security updates to address a vulnerability in their SmarterMail software. Users and administrators of affected product versions are advised to update to SmarterMail version Build 9413 immediately.

 

## Latest Developments: 

January 29, 2026: Critical security fixes Provided by Smartertools.
https://www.smartertools.com/smartermail/release-notes/current

January 27, 2026: FortiGuard Labs released a Threat Signal.
https://www.fortiguard.com/threat-signal-report/6322/smartertools-smartermail-rce

January 26, 2026: This CVE was added to CISA's Known Exploited Vulnerabilities Catalog 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|