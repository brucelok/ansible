
Role Name
=========

Just an example
Ansible role for performing OS specific customizations for Nova hypervisors build.
such as upgrade kernel for meltdown/spectre fix on RHEL 7.4
and upgrade Cisco VIC card kernel module (kmod-enic)
reboot a server and wait for SSH

Requirements
------------
None

Role Variables
--------------
- k_version
- static_repo
- static_repo_url
- enic_desired


Dependencies
------------
None

Example Playbook
----------------

  - hosts: servers
    roles:
      - role: os_customize

License
-------
GPLv3

Author Information
------------------
lok.bruce@gmail.com
