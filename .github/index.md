---
abstract: Basic information about the CI/CD processes in this repo.
authors:
  - name: Xander Harris
    email: xandertheharris@gmail.com
date: 2024-07-23
title: CI/CD
---

## Dependabot

Stay away from zero days with Dependabot.

```{literalinclude} /.github/dependabot.yml
:language: yaml
```

## Workflows

GitHub Actions provides a pretty complete CI/CD system and they'll let you
run a lot of pipelines for free.

### Ansible Lint

[![Ansible Lint](https://github.com/edwardtheharris/ansible-kcp/actions/workflows/ansible.yml/badge.svg)](https://github.com/edwardtheharris/ansible-kcp/actions/workflows/ansible.yml)

This is the configuration for the various lint tools used here.

```{literalinclude} /.ansible-lint
:language: yaml
```

### Documentation

[![Documentation](https://github.com/edwardtheharris/ansible-kcp/actions/workflows/documentation.yml/badge.svg)](https://github.com/edwardtheharris/ansible-kcp/actions/workflows/documentation.yml)

Build and deploy the GitHub Pages docs.

```{literalinclude} /.github/workflows/documentation.yml
:language: yaml
```
