---
abstract: >-
  This is the documentation index for an Ansible role to deploy a  
  single node etcd cluster.
authors:
   - name: Xander Harris
     email: xandertheharris@gmail.com
date: 2024-03-08
title: Etcd Roles Index 
---

## Role Documentation

```{toctree}
etcd/readme
```

### Indices and tables

- {ref}`genindex`
- {ref}`modindex`
- {ref}`search`

### Glossary

```{glossary}
Calico
   Calico is a networking and security solution that enables Kubernetes
   workloads and non-Kubernetes/legacy workloads to communicate seamlessly and
   securely. More information is available
   [here](https://docs.tigera.io/calico/latest/about/).

CNI
   Container Network Interface used to manage networking between and inside
   clusters.

HA
   High Availability; in this context we mean specifically HA k8s clusters
   as described
   [here](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/high-availability/).

kubeadm
   A program that allows the creation and management of Kubernetes clusters
   with the command line. More information is available
   [here](https://kubernetes.io/docs/reference/setup-tools/kubeadm/).

kubeconfig
   A file that contains context and authentication information for one or more
   {term}`K8S` clusters. Usually kept in a folder in a user's home directory
   ({file}`.kube/config`).

kube-vip
   A network stack that can be used to enable cloud-style network resources
   on a bare metal {term}`K8S` cluster. More information is available
   [here](https://kube-vip.io/docs/installation/static/).

kubie
   A handy tool for switching k8s contexts and namespaces. More information is
   available [here](https://github.com/sbstp/kubie).

K8S
   Kubernetes; Ancient Greek for navigator or guide, in modern English usage
   it is a container orchestration system designed by Google and documented
   [here](https://kubernetes.io).
```
