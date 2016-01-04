## nagios-plugin-hipsaint

[![Build Status](https://travis-ci.org/Oefenweb/ansible-nagios-plugin-hipsaint.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-nagios-plugin-hipsaint) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-nagios--plugin--hipsaint-blue.svg)](https://galaxy.ansible.com/list#/roles/6549)

Set up (the latest, or a specific version of) [HipSaint](https://github.com/hannseman/hipsaint) in Debian-like systems.

#### Requirements

* `pip` (will not installed)

* `python` (will be installed)

#### Variables

* `nagios_plugin_hipsaint_version`: [default: `latest`]: HipSaint version to install (e.g. `latest`, `0.5.2`)

## Dependencies

None

## Recommended

* `ansible-pip` ([see](https://github.com/Oefenweb/ansible-pip))
* `ansible-virtualenv` ([see](https://github.com/Oefenweb/ansible-virtualenv))

#### Example

```yaml
---
- hosts: all
  roles:
    - nagios-plugin-hipsaint
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-nagios-plugin-hipsaint/issues)!
