---
abstract: Ansible etcd deployment role readme.
date: 2025-06-14
title: ansible etcd readme
---

A simple Ansible role to deploy a single node etcd cluster.

## Usage

See the local `site.yml`, or the snippet below

```yaml
---
- name: Install etcd
  hosts: etcd
  roles:
    - role: etcd
      tags:
        - etcd
```

### Kubernetes the Hard Way

This is part of the
[Kubernetes the Hard Way](https://edwardtheharris.github.io/k8s-the-hard-way/)
project.
