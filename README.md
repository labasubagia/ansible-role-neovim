Neovim
=========

Ansible role to install [Neovim](https://neovim.io/) linux

Requirements
------------
- Ansible Core >= 2.16
- Tested Linux Distribution
  - Debian 12
  - Ubuntu 24.04
  - Fedora 40

> Note: Other distributions likely to work but not been tested

Role Variables
--------------

The following variables will change the behavior of this role (default values are shown below):

```yaml
---
neovim_url: https://github.com/neovim/neovim/releases/latest/download/nvim-linux64.tar.gz
neovim_state: present

```


Example Playbook
----------------
```yaml
- hosts: servers
  roles:
    - role: labasubagia.neovim
```

License
-------

MIT

Author Information
------------------

[Laba Subagia](https://github.com/labasubagia)
