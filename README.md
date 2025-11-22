# Steam OpenID MITM Phishing Analysis

## Overview
This repository documents the reverse engineering and security analysis of a malicious website impersonating steam login through an OpenID MITM flow. The purpose of this analysis is educational and defensive.

## What Happened
A Steam user was targeted by a phishing page offering fake "vote to win skins/knife" rewards. The site used a fake steam login to capture credentials and escalate via family sharing features.

##My Role
- Guided victim to create a steam support ticket  
- Reproduced attack in an isolated vm  
- Analyzed frontend bundle and network  
- Extracted indicators of compromise  
- Reported malicious infra  
- Published awareness video

## Key Findings
- Cloned Steam Login (csreserve-style kit)  
- OpenID MITM Credential Harvesting  
- Family view persistence attempt  
- Low-effort backend on disposable vps  
- Clear impersonation attempt

## Video
YouTube: https://youtu.be/qsYza5weW3E

## Disclaimer
For educational and defensive use only.
