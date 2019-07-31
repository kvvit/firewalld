# Ansible Role: Firewalld

Configure firewalld on RHEL/CentOS servers.

## Requirements

No requirements

## Role Variables

Variables of port numbers and protocols (tcp/udp) in defaults/main.yml. You can change this variables as you wish

## Dependencies

 No dependencies

## Example Playbook

```yaml
- hosts: all
  roles:
    - role: kvvit.firewalld
      become: yes
```

## License

Free

## Author Information

This role has been created in 2019 by [Khramtsov Valentin](https://github.com/kvvit/)

