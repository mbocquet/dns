# DNS

Ansible role to install and configure DNS (bind9). Can be plugged to DHCPs server(s).

## Requirements

None.

## Role Variables

Many. See defaults/main.yml

## Dependencies

None.

## Install this roles as submodule of an existing GIT repository

`git submodule add https://git.sekoya.org/mb/dns.git roles/dns`

## Example Playbook

    - hosts: servers
      roles:
         - dns


    - hosts: servers
      roles:
         - { role: dns, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
