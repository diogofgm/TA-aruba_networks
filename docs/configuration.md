---
layout: default
title: Configuration
nav_order: 5
---
# Configuration
## Splunk
- Configure a new index (e.g. wifi) for the new logs

### Receiving syslogs on Splunk
NOTE: Its recommended to use a separate and dedicated syslog solution (e.g. rsyslog, syslog-ng, etc).
- Configure new TCP port (e.g. 514) pointing to the new index using the "aruba:syslog" sourcetype

### Monitoring log files
- Configure a new file monitor input pointing to the new index using the "aruba:syslog" sourcetype

## Aruba
- Configure syslog outputs
For more information please refer to the [Aruba documentation](http://support.arubanetworks.com/default.aspx).
