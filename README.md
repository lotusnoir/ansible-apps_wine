# ansible-apps_wine

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_wine-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_wine)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_wine.svg)](https://github.com/lotusnoir/ansible-apps_wine/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_wine?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_wine)
[![downloads](https://img.shields.io/ansible/role/d/56109)](https://galaxy.ansible.com/lotusnoir/apps_wine)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56109)](https://galaxy.ansible.com/lotusnoir/apps_wine)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Install and configure wine to install windows applications.
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_wine
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_wine


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
