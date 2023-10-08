# freebsd-collection
[![galaxy](https://img.shields.io/badge/dynamic/json?style=flat&label=galaxy&prefix=v&url=https://galaxy.ansible.com/api/v3/collections/charlesrocket/freebsd/&query=highest_version.version)](https://galaxy.ansible.com/ui/repo/published/charlesrocket/freebsd/)
[![CI](https://github.com/charlesrocket/freebsd-collection/actions/workflows/ci.yml/badge.svg)](https://github.com/charlesrocket/freebsd-collection/actions/workflows/ci.yml)

Ansible collection for FreeBSD servers and desktops.

### Installation

`requirements.yml`:

```yaml
collections:
  - name: charlesrocket.freebsd
```

### Usage

```yaml
- name: Workstation playbook
  hosts: all

- name: Include playbook - station
  ansible.builtin.import_playbook: charlesrocket.freebsd.station
```

```yaml
- name: Server playbook
  hosts: all

- name: Include playbook - server
  ansible.builtin.import_playbook: charlesrocket.freebsd.server
```

[example variables](https://github.com/charlesrocket/freebsd-collection/tree/trunk/profiles/charlesrocket)

## Example

<img src="assets/screenshot.png" alt="screenshot" width="900"/>

```sh
# run as user
ansible-galaxy collection install charlesrocket.freebsd
ansible-playbook charlesrocket.freebsd.station -c \
    local -i "localhost," -e "profile=charlesrocket"
```
