# Ansible Docker [![Build Status](https://travis-ci.org/gmauro/ansible-playonlinux.svg?branch=master)](https://travis-ci.org/gmauro/ansible-playonlinux)
[Ansible](https://wwww.ansible.com) role to install [PlayOnLinux](http://www.playonlinux.com) on Ubuntu or Debian systems .  


## Usage

Clone this repo into your roles directory:

```bash
$ git clone https://github.com/gmauro/ansible-playonlinux.git roles/playonlinux
```

And add it to your play's roles:

```yaml
- hosts: ...
  roles:
    - playonlinux
    - ...
```

This role comes preloaded with multiple available defaults. You can override each one in your hosts/group vars, in your inventory, or in your play. See the annotated defaults in ``defaults/main.yml`` for help in configuration.