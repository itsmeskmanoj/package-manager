# einit

This is used to setup a machine before any other configuration management of the compute instances.

## Requirements 

Ubuntu 14.04 (Trusty Tahr), amd64

This role requires that the low-level packages useradd and groupadd be available.

Configurations expected to implement the role from the config file:
  "controller\_ipaddr"
  "janastuops\_passwd"
  "janastu\_servu\_passwd"


Role Variables

Note that to use this role, the credentials used to bootstrap the machine must be injected as environment variables. As such, if a bash interface is used, it can be stored as an rc file and *source*d in the script
