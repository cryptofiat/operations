# Base setup for new why-press client vm

# TODO
- review logging target
- log output for wp-cli should go to central log location
- install nginx waf

# Responsibilities
- updates base system
- creates administrative sudo users
- sets authorized public ssh keys
- installs common bash aliases
- adds nginx ppa
- installs base packages
- removes unneeded base services
- configures webserver basics
- configures local ssh config and hardens remote sshd
