# k3s

Ansible role to install k3s using the official k3s install script.

Supported Operating Systems:
- [x] Ubuntu Server 20.04 LTS

This role will configure a new host with everything required to run a single
node k3s cluster.

## Dependencies

### On host running ansible

Ansible Collection Kubernetes

```sh
$ ansible-galaxy collection install community.kubernetes
```

### On host being provisioned with Ansible

The following tools will automatically be installed by this role:
- python3 pip
- helm
- python pylint
- python openshift
