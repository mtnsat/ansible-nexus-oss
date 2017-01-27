# Ansible Nexus OSS Role

[![Build Status](https://travis-ci.org/mtnsat/ansible-nexus-oss.svg?branch=master)](https://travis-ci.org/mtnsat/ansible-nexus-oss)

## Description

*ansible-nexus-oss* is an [Ansible](http://ansible.com) role.
Use this role to install Sonatype Nexus OSS.

## Provides

* Sonatype Nexus OSS server

## Requirements

* Ansible 2.0 or higher
* Ubuntu Server 14.04

## Usage

Clone this repo into your roles directory ( See [ansible documentation](http://docs.ansible.com/playbooks.html#roles) for more information on roles ) and include it in your playbook

### Default vars
Override any of the following if necessary

```yaml
---
nexus_version: 2.12.0
## checksum from curl http://download.sonatype.com/nexus/oss/nexus-{{ nexus_version }}-bundle.tar.gz.sha1
nexus_bundle_checksum: sha1:1a9aaad8414baffe0a2fd46eed1f41b85f4049e6
nexus_unpackaged_version: 2.12.0-01
nexus_base_dir: /opt
nexus_home: /opt/nexus
nexus_data_dir: /data
```

Mad Creds
-------
Forked from [codingbunch/ansible-nexus-oss](https://github.com/codingbunch/ansible-nexus-oss)
