---
section: issue
title: Planned Network Maintenance in DC1
date: 2025-05-09T22:00:00.000Z
resolved: true
draft: false
informational: true
pin: false
resolvedWhen: 2025-05-09T23:56:00.000Z
affected:
  - SIP-Trunk
  - Partner-Portal
  - Wiki
severity: notice
---
#### UPDATE 23:56 CET 

The maintenance has been completed successfully.\
We will be monitoring the infrastructure for any anomaly, if you notice anything out of the usual please reach out to us.



\- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 



Please be advised that we have scheduled essential maintenance to upgrade the network infrastructure in our Data Center 1 (DC1). This work is necessary to enhance performance and reliability.

The maintenance window is planned as follows:

* **Start**: Friday, May 9th, 2025, at 22:00 CEST
* **End**: Saturday, May 10th, 2025, during the afternoon. (We will provide an update upon completion).

### Impact on Services:

During this maintenance period, service availability will be affected as follows:

* Services Temporarily Unavailable: The following services hosted in DC1 will be unreachable for the duration of the maintenance:

  * Wiki
  * Partner Portal
  * API
  * Website
* Services with Automatic Failover: The following services are designed to automatically failover to our Data Center 2 (DC2) and should continue operating without disruption for customers and partners:

  * SIP Trunk
  * Webex Calling

### Action Required for Seamless Failover:

To ensure the automatic failover functions correctly for SIP Trunk and Webex Calling, we kindly request that you verify that all necessary DC2 IP addresses are included in your network whitelists. Please refer to [our documentation for the complete list.](https://wiki.teameis.it/it/VoIP/Eis-Trunksip/Requisiti-Tecnici)

[](https://wiki.teameis.it/it/VoIP/Eis-Trunksip/Requisiti-Tecnici)

We apologize for any inconvenience this necessary maintenance may cause. Our team is available to clarify any doubts or answer any questions you may have.

Thank you for your understanding and cooperation.

Sincerely,

EIS NOC
