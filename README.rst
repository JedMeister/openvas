OpenVAS - Advanced vulnerability scanner and manager
====================================================

`OpenVAS`_ is an open source remote security vulnerability scanner, designed to
search for networked devices and computers, discover accessible ports and
services, and to test for vulnerabilities on any such ports; plugins allow for
further expansion. The framework is part of Greenbone Networks' commercial
vulnerability management solution from which developments are contributed to
the Open Source community since 2009.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- OpenVAS 9
- Custom port list for TurnKey appliances
- Custom scan config for TurnKey appliances
- Daily cron job to update vulnerability databases  

About NVT Feed
--------------

Greenbone maintains a public feed of Network Vulnerability Tests (NVTs) for the
OpenVAS project. It contains more than 50,000 NVTs, growing on a permanent
basis. This feed is configured as the default for OpenVAS and relates to the
Greenbone Security Feed which is part of the commercial Greenbone Security
Manager appliance products.

Though the Greenbone Community Feed and the Greenbone Security Feed share over
95% of the content, the Community Feed is never as current or as complete as the
Greenbone Security Feed.

Note: This appliance is not supported by Greenbone Networks. It relies on
OpenVAS community support.

Additional Features
-------------------

- SSL support out of the box.
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for remotely configuring the appliance.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, ShellInABox: username **root**
-  Greenbone Security Assistant (GSA): username **admin**

.. _OpenVAS: http://www.openvas.org
.. _TurnKey Core: http://www.turnkeylinux.org/core
