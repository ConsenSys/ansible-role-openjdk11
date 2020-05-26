# Ansible Role: OpenJDK11

### Description
Ansible role that will install, configure and runs OpenJDK 11 on linux 

### Table of Contents
  - [Supported Platforms](#supported-platforms)
  - [Dependencies](#dependencies)
  - [Role Variables](#role-variables)
  - [Example Playbook](#example-playbook)
  - [License](#license)
  - [Author Information](#author-information)

### Supported Platforms
```
* Debian
* Ubuntu
* Redhat(CentOS/Fedora)
* Amazon
```

### Dependencies

* linux

### Role Variables:
n/a

### Example Playbook
1. Install via github

```
ansible-galaxy install git+https://github.com/pegasyseng/ansible-role-openjdk11.git
```

Create a requirements.yml with the following:
```
---
- hosts: localhost
  connection: local
  force_handlers: True

  roles:
  - role: ansible-role-openjdk11

```

Run with ansible-playbook:
```
ansible-playbook -v /path/to/requirements.yml
```


### License

Apache


### Author Information

PegaSysEng, 2019
