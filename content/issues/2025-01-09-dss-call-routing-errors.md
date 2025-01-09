---
section: issue
title: DSS Call Routing Errors
date: 2025-01-08T06:02:18.841Z
resolved: true
draft: false
informational: false
pin: false
resolvedWhen: 2025-01-08T08:05:18.848Z
affected:
  - SIPTrunk
  - WebexCalling
severity: down
---
Call routing for all DSS services was broken this morning at 7:02 AM for SIP Trunks and Webex Calling.\
\
We have since identified the issue and have deployed a fix.\
\
As of 9:05 AM calls are being correctly routed but we are keeping the services monitored.



# P﻿ost Mortem





**Affected Services:**

| **Service** | **Impact** |
| ----------- | ---------- |
| DSS         | **MAJOR**  |

**Affected Products:**

| **Product**   | **Impact**  |
| ------------- | ----------- |
| SIP Trunk     | **MAJOR**   |
| Webex Calling | **PARTIAL** |

**Start Date of Incident:**

08/01/2025 07:02 CET

**Resolution Date of Incident:**

08/01/2025 09:05 CET

**Summary of Incident:**

Calls were not being correctly routed by the platform causing errors for both inbound and outbound calls.

The cause was a bug in a specific software version of the RTP Server that caused an OOM error.

**Mitigation Steps:**

1. Restarted the affected services

**Resolution Steps:**

1. Update the RTP Server to permanently fix the issue

**Action Items:**

* Improve our alerting system so that in the future we can take proactive action in similar cases
* Change SIP Server responses to SIP OPTION so that in similar cases customer endpoints will be able to correctly fail-over to the secondary node