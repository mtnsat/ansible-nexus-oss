# Ansible Nexus OSS Role

[![Build Status](https://travis-ci.org/mtnsat/ansible-nexus-oss.svg?branch=master)](https://travis-ci.org/mtnsat/ansible-nexus-oss)

## Description

*ansible-nexus-oss* is an [Ansible](http://ansible.com) role.
Use this role to install Sonatype Nexus OSS.

## Provides

* Latest Sonatype Nexus OSS server

## Requirements

* Ansible 1.7 or higher
* Ubuntu Server 14.04

## Usage

Clone this repo into your roles directory ( See [ansible documentation](http://docs.ansible.com/playbooks.html#roles) for more information on roles ) and include it in your playbook

### Default vars
Override the following if necessary

```yaml
---
nexus:
  version: 2.12.0
  unpackaged_version: 2.12.0-01
  base_dir: /opt
  home: /opt/nexus
  data_dir: /data
```

Mad Creds
-------
Forked from [CodingBunch](https://github.com/codingbunch/ansible-nexus-oss)