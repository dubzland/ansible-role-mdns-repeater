# Dubzland: mDNS Repeater
[![Gitlab pipeline status (self-hosted)](https://img.shields.io/gitlab/pipeline/jdubz/dubzland-mdns-repeater?gitlab_url=https%3A%2F%2Fgit.dubzland.net)](https://git.dubzland.net/jdubz/dubzland-mdns-repeater/pipelines)

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
    - role: dubzland-mdns-repeater
```

## License

MIT

## Author

* [Josh Williams](https://codingprime.com)
