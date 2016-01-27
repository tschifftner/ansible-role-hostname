# Ansible Role: hostname

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-hostname.svg)](https://travis-ci.org/tschifftner/ansible-role-hostname)

Sets hostname on Debian/Ubuntu linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
hostname: 'web01.example.com'
```

## Dependencies

None.

## Example Playbook

    - hosts: server
      roles:
        - { role: tschifftner.hostname }

## Supported OS
Ansible          | Debian Jessie    | Ubuntu 14.04    | Ubuntu 12.04
:--------------: | :--------------: | :-------------: | :-------------: 
1.9              | Yes              | Yes             | Yes
2.0              | Yes              | Yes             | Yes

## License

MIT / BSD

## Author Information

 - Tobias Schifftner, @tschifftner