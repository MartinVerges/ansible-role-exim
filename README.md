# Ontic Exim ![Status](https://img.shields.io/badge/project-maintained-brightgreen.svg)

| Branch             | Build               | Galaxy              | Release              |
| :----------------- | :------------------ | :------------------ | :------------------- |
| **master**         | [![Build](https://img.shields.io/travis/ontic/ansible-role-exim/master.svg)](https://travis-ci.org/ontic/ansible-role-exim) | [![Galaxy](https://img.shields.io/badge/galaxy-ontic.exim-blue.svg)](https://galaxy.ansible.com/ontic/exim/) | [![Release](https://img.shields.io/github/release/ontic/ansible-role-exim.svg)](https://github.com/ontic/ansible-role-exim/releases) |

## Introduction

This role installs Exim on RedHat/CentOS and Debian/Ubuntu Linux servers.

## Requirements

| Name                                                                                          | Version       |
| :-------------------------------------------------------------------------------------------- | :------------ |
None                                                                                            | N/A           |


## Installation

We strongly suggest installing this role using [Ansible Galaxy](https://galaxy.ansible.com) so that any dependencies
will get resolved and downloaded automatically. However, we've listed a few other alternatives.

### 1.1 Downloading

Download the project files as a `.zip` archive, extracting them into your `./roles/` directory.

### 1.2 Cloning

Clone the project it into your `./roles/` directory.

### 1.3 Ansible Galaxy

The easiest way to install this module is via the command line:

```
$ ansible-galaxy install ontic.exim
```

If you have multiple roles to install, the ansible-galaxy CLI can be fed a `requirements.yml` file.

```yml
- src: ontic.exim
```

```
$ ansible-galaxy install -r requirements.yml
```

Alternatively you could download the source by setting the repository in your `requirements.yml` file:

```yml
- src: git+https://github.com/ontic/ansible-role-exim.git
  version: master
  name: ontic.exim
```

### 2.1 Enabling

Enable the role in your playbook file.

```yml
- name: Example web server
  hosts: web_servers
  roles:
    - { role: ontic.exim }
```

## Documentation

Full documentation is available in the [docs](/docs) directory.

## Contributors

Below lists all individuals having contributed to the repository. If you would like to get involved, we encourage
you to do so by making a [pull](../../pulls) request or submitting an [issue](../../issues).

* [Adam Dyson](https://github.com/adamdyson)
* [Evgeny Lebedev](https://github.com/lebe-dev)

## License

Licensed under the BSD License. See the [LICENSE](/LICENSE) file for details.