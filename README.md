# Role OpenVPN server

This role installs OpenVPN, configures it as a server, sets up networking (iptables), and can optionally create client certificates.

## Tested OS

- Ubuntu 18.04

## Role Variables

- `openvpn_clients` default `[]`
- `openvpn_fetch_config_dir` default `/tmp/openvpn-clients`

Other variables are defined in `defaults /main.yml` and can be overwritten.

## License

GPLv2

## Author Information

[Devops.works](https://www.devops.works). Based on [ansible-role-openvpn](https://github.com/kyl191/ansible-role-openvpn) written by Kyle Lexmond.
