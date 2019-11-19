# Dubzland: mDNS Repeater
[![Gitlab pipeline status (self-hosted)](https://git.dubzland.net/dubzland/ansible-role-mdns-repeater/badges/master/pipeline.svg)](https://git.dubzland.net/dubzland/ansible-role-mdns-repeater)

Installs and configures the avahi daemon for broadcastint mDNS packets.

## Requirements

Ansible version 2.0 or higher.

## Role Variables

None

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: dubzland.mdns-repeater
```

## License

MIT

## Author

* [Josh Williams](https://codingprime.com)
