Role Name
=========

Register to Red Hat Network and enables repositories of RHOSP.

Requirements
------------

* RHEL 6/7
* RHN Subscription

Role Variables
--------------

    rhn_user: foouser 
    rhn_password: somepass
	rhosp_version: 6.0

User and password are required if the host is not already registered.

Example Playbook
----------------

    - hosts: servers
      roles:
         - abelboldu.rhn-rhosp 
           rhn_user: foouser
	       rhn_password: somepass
	       rhosp_version: 6.0
License
-------

Apache 2.0

Author Information
------------------

Abel Boldú <abel.boldu (-) gmx.com>
