# Ansible Role mafalb.postfix.server

## Basic Usage

```yaml
- name: install mafalb.postfix.server
  hosts: localhost
  roles:
  - role: mafalb.postfix.server
```

```yaml
- name: install mafalb.postfix.server
  hosts: localhost
  roles:
  - role: mafalb.postfix.server
    postfix_cfg:
      inet_interfaces: all
```

## Variables

```postfix_cfg``` dictioniary with postfix configuration directives. not implemented for all config directives.

## License

GPL-3.0-or-later
