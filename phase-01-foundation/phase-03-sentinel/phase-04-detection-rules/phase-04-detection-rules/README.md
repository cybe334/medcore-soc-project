# Phase 4 — Detection Rules & MITRE ATT&CK Mapping
**Days:** 51–70
**Status:** ⏳ Pending

## Objective
Build 30+ active detection rules in Microsoft Sentinel mapped to the
MITRE ATT&CK framework, covering the most critical threats facing
MedCore Pharmacy Ltd.

## Contents
- Custom KQL detection rules (30+)
- MITRE ATT&CK mapping table
- Watchlist configurations
- Fusion correlation rule setup
- UEBA configuration
- Atomic Red Team test results

## MITRE ATT&CK Coverage
| Technique | ID | Alert |
|---|---|---|
| Brute Force | T1110 | Multiple failed logons → success |
| PowerShell Abuse | T1059.001 | Encoded PowerShell detected |
| Valid Accounts | T1078 | Suspicious login unusual location |
| RDP Lateral Movement | T1021.001 | RDP from non-admin to server |
| New Account Creation | T1136 | Admin account outside business hours |
| Disable Security Tools | T1562.001 | Windows Defender disabled |
| Data Exfiltration | T1041 | Large outbound transfer unknown IP |
| Token Manipulation | T1134 | Token impersonation via RunAs |

## Milestone
✅ 30+ Active Detection Rules with Full MITRE Mapping
