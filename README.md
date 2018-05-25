# haproxy

Master: [![Build Status](https://travis-ci.org/sansible/haproxy.svg?branch=master)](https://travis-ci.org/sansible/haproxy)
Develop: [![Build Status](https://travis-ci.org/sansible/haproxy.svg?branch=develop)](https://travis-ci.org/sansible/haproxy)

* [Installation and Dependencies](#installation-and-dependencies)
* [Tags](#tags)
* [Examples](#examples)

This role installs HAProxy and can optionally start and enable the service.


## Installation and Dependencies

To install run `ansible-galaxy install sansible.haproxy` or add this to your
`roles.yml`.

```YAML
- name: sansible.haproxy
  version: v1.0
```

and run `ansible-galaxy install -p ./roles -r roles.yml`


## Tags

This role uses tags: **build** and **configure**

* `build` - Installs ...
* `configure` - Configures ...


## Examples

Simply include role in your playbook

```YAML
- name: Install and Configure haproxy
  hosts: somehost

  roles:
    - role: sansible.haproxy
```
