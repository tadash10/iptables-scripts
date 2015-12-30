[Iptables-scripts](https://github.com/jeremiedecock/iptables-scripts)
=====================================================================

Copyright (c) 2007,2015 Jeremie DECOCK (<http://www.jdhp.org>)

* Source code: <https://github.com/jeremiedecock/iptables-scripts>
* Issue tracker: <https://github.com/jeremiedecock/iptables-scripts/issues>

Description
-----------

This project contains some Iptables scripts made to setup Netfilter (the Linux
firewall).

Installation
------------

Type the following commands in a Linux console (from the administrator
account):

```shell
cp iptables-scripts/iptables-*.sh /etc/
chown root:root /etc/iptables-*.s
chmod 700 /etc/iptables-*.s
```

On `upstart` compatible systems (former Debian, Ubuntu, ...):

```shell
cp init-scripts/upstart/iptables.conf /etc/init/
chown root:root /etc/init/iptables.conf
chmod 644 /etc/init/iptables.conf
```

Bug reports
-----------

To search for bugs or report them, please use the Iptables-scripts Bug Tracker
at:

> <https://github.com/jeremiedecock/iptables-scripts/issues>

License
-------

This project is provided under the terms and conditions of the
[MIT License](http://opensource.org/licenses/MIT).

