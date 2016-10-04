Disable SElinux
===============

This role disables SELinux (at the next reboot) on RHEL/CentOS/Fedora systems and sets it in permissive mode before the reboot.

Example Playbook
-------------------------

This is an example playbook:

    - hosts: servers
      roles:
         - { role: stardata.disable-selinux }

License
-------

GPLv3

Author Information
------------------

Authored by Gilberto Ficara for Stardata S.r.l. - http://www.stardata.it
