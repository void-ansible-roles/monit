monit
=====


What is does this role do?
--------------------------

This role installs the monit service manager.  More information about the monit service manager can be found on the [Monit website](https://mmonit.com/monit/).


Meta
----

Files Managed:
  * /etc/monit.conf.d/
  * /etc/sv/monit/run
  * /var/service/monit

Defaults Provided:
  * None

Variables Required:
  * None

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * [network](https://github.com/void-ansible-roles/network)
