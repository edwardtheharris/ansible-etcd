---
abstract: Install etcd and enable the service on Arch
authors
  - name: Xander Harris
    email: xandertheharris@gmail.com
title: Install and enable etcd
---

An Ansible role to install etcd on ArchLinux.

## Requirements

A target host running ArchLinux.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

This role can be used with a playbook similar to this one.

```{code-block} yaml
- name: Install etcd
  hosts: servers
  roles:
    - { role: etcd }
  ```

## License

Copyright (c) 2025 Xander Harris. All rights reserved.

### Author Information

```{sectionauthor} Xander Harris <xandertheharris@gmail.com
```
