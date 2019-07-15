# apt-cacher-ng

An [Ansible] role to install/configure [apt-cacher-ng]
- (Client/server configurations)

## Requirements

None

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

```[yaml]
---
- hosts: all
  become: true
  vars:
  roles:
    - role: ansible-apt-cacher-ng
      apt_cacher_server: rpi-host-000
  tasks:
```

## License

MIT

## Author Information

- Larry Smith Jr.
- Menno van Rahden

[Ansible]: <https://www.ansible.com>
[apt-cacher-ng]: <https://www.unix-ag.uni-kl.de/~bloch/acng/>
