---
section: issue
title: MXP Infrastracture maintenance
date: 2026-04-02T21:30:00.000+02:00
resolved: true
draft: false
informational: true
pin: false
resolvedWhen: 2026-04-03T02:30:00.000+02:00
affected:
  - sip-trunk
severity: notice
---
#### **Scheduled Maintenance**

SIP Traffic Routing to Secondary Node

#### **Maintenance Window**

* **Start:** Thursday, April 2 at 21:30
* **End:** Friday, April 3 at 02:30 AM

#### **Overview**


During this scheduled maintenance window, we will be shifting our SIP traffic to our secondary node, which operates on the IP address `194.76.135.16`.

#### **Action Required**


To prevent any disruption to your service, please verify your firewall configurations. As outlined in our Wiki documentation, the following subnet must be added to your allowed network list (whitelist):

* **Required Subnet:** `194.76.135.0/24`

#### **Expected Impact**



* **No Impact:** Customers using the Webex Calling service, as well as customers who have already whitelisted the `194.76.135.0/24` subnet, will not experience any service disruption.
* **Service Interruption:** Customers who have ***not*** whitelisted the required subnet prior to the maintenance window will experience a drop in SIP connectivity once the traffic shift occurs.
