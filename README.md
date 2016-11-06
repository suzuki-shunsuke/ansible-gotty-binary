gotty-binary
==============

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-gotty-binary.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-gotty-binary)

Install [gotty](https://github.com/yudai/gotty/) binary.

https://galaxy.ansible.com/suzuki-shunsuke/gotty-binary/

Requirements
------------

* tar

Role Variables
--------------

* gotty_version: The gotty version. The default is 0.0.13
* gotty_type: The default is linux_amd64. Please check [gotty's releases](https://github.com/yudai/gotty/releases)
* gotty_install_dir: Install directory. The default is /usr/local/bin
* gotty_become: The default is yes
* gotty_user: The default is root
* gotty_group: The default is root
* gotty_mode: The default is 0755

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: suzuki-shunsuke.gotty-binary
```

License
-------

MIT
