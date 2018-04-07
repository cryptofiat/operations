# Ansible playbooks for pi's

- setup users, dns server, general hardening
- update dns server


# openvpn routing
- sysctl_config managed in security role
    net.ipv4.ip_forward: 1
