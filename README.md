## nagios-plugin-hipsaint

[![CI](https://github.com/Oefenweb/ansible-nagios-plugin-hipsaint/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-nagios-plugin-hipsaint/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-nagios--plugin--hipsaint-blue.svg)](https://galaxy.ansible.com/Oefenweb/nagios-plugin-hipsaint)

Set up (the latest, or a specific version of) [HipSaint](https://github.com/hannseman/hipsaint) in Debian-like systems.

#### Requirements

* `pip` (will not installed)

* `python(2|3)` (will be installed)

#### Variables

* `nagios_plugin_hipsaint_python_version_major` [default: `2`]: Python version to install `hipsaint` for.
* `nagios_plugin_hipsaint_python_version` [default: `nagios_plugin_hipsaint_python_version_major`]: Deprecated

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
