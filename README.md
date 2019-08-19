# ansible-works

## Background

The Ansible role `ansible-role-os_customize` which is an example and interim solution, helps to automate some of the complicated OS configuration for a legacy team.

## What major tasks are included

1. check and upgrade Linux kernel for some vulnerability fixes
2. customize some add-hoc configuration on OS network configuration which were missing from the greenfield build
3. customize configuration for OS boot-up
4. upgrade Cisco network card driver
5. disable firewalld and multipathd from OS
6. reboot OS if needed
7. verify kernel version after reboot
