Firewalld
=========

Ce role permet l'ouverture de port public en tcp et udp sur firewalld.

Requirements
------------

firewalld installed.

Platform
--------

Debian ou RHEL

Role Variables
--------------

<pre><code>firewall_port_tcp:
  - 3000
  - 443

firewall_port_udp:
  - 3000
  - 443
</code></pre>

Dependencies
------------

Ce role se télécharge automatiquement à partir du requirements.yml


Author Information
------------------

Starfly Env Team
