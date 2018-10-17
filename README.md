# pagerdutygtw
PagerDuty UIM Gateway Probe


# Change Log

## 2018-09 - version 1.020
- Upgrate to PagerDuty REST API V2 using JRE 1.8
- Support Incident allerts grouping

## 2016-11 - version 1.018
Quick fix to allow user to override service_key when synchronizing services defined in PagerDuty.
As Services are discovered by the probe, if the user has set an alternate service_key in the <services>
configuration, the user specified service_key will be kept.

## 2016-11 - version 1.017
Added configuration to control probe bootup performance for customers with large numbers of users and
services defined in PagerDuty.
