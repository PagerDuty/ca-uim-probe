# pagerdutygtw
PagerDuty UIM Gateway Probe


# Change Log

## 2016-11 - version 1.018
Quick fix to allow user to override service_key when synchronizing services defined in PagerDuty.
As Services are discovered by the probe, if the user has set an alternate service_key in the <services> 
configuration, the user specified service_key will be kept.

## 2016-11 - version 1.017
Added configuration to control probe bootup performance for customers with large numbers of users and 
services defined in PagerDuty.
