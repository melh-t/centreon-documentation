---
id: applications-antivirus-clamav-ssh
title: Antivirus ClamAV
---

## Prerequisites

### Centreon Plugin

Install this plugin on each needed poller:

``` shell
yum install centreon-plugin-Applications-Clamav-Ssh
```

### SSH

SSH key exchange mut be done between poller and monitored server.

## Centreon Configuration

### Create a new host

Go to *Configuration \> Hosts* and click *Add*. Then, fill the form as shown by
the following table:

| Field                   | Value                           |
| :---------------------- | :------------------------------ |
| Host name               | *Name of the host*              |
| Alias                   | *Host description*              |
| IP                      | *Host IP Address*               |
| Monitored from          | *Monitoring Poller to use*      |
| Host Multiple Templates | App-Antivirus-Clamav-SSH-custom |

Click on the *Save* button.
