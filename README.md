# operations
contains infrastructure automation scripts and operations-related documentation

NB check the wiki for howtos and guidelines

# content

## systemd
configuration files for services daemons

# req

- python
- set hostname
- system user must get linger option for systemd
loginctl enable-linger username
https://wiki.archlinux.org/index.php/Systemd/User
- system user must export specific env var
https://answers.launchpad.net/ubuntu/+source/systemd/+question/287454
