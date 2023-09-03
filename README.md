# Ansible Role: graylog

[![Lint](https://github.com/dcjulian29/ansible-role-graylog/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-graylog/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-graylog.svg)](https://github.com/dcjulian29/ansible-role-graylog/issues)

This an Ansible role to install Graylog, a log management system.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.graylog
  src: https://github.com/dcjulian29/ansible-role-graylog.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
