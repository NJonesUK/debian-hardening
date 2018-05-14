Debian-Hardening
=========

An ansible role for hardening debian based systems. Built from the Debian 8 CIS Benchmark - CIS_Debian_Linux_8_Benchmark_v1.0.0.pdf

Requirements
------------
Only runs on debian-based systems.

Role Variables
--------------
Important ones are:
* disable_ipv6 - sets whether IPv6 is enabled on the network interfaces or not
* ufw_tcp_allow - list of TCP ports to allow through the firewall
* ufw_udp_allow - list of UDP ports to allow through the firewall

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in
regards to parameters that may need to be set for other roles, or variables that
are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: debian-hardening, x: 42 }

License
-------

BSD

Author Information
------------------

Authored by Nick Jones.
