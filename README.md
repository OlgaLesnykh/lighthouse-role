lighthouse-role
=========

The role can install and tune lighthouse, nginx on Centos 7

Requirements
------------

1. Centos 7 OS

Role Variables
--------------

|     vars            |        description             |
|---------------------|--------------------------------|
| lighthouse_git      | lighthouse package source      |
| lighthouse_dir      | Work directory from lighthouse |
| lighthouse_home_dir | Home directory from lighthouse |
| nginx_user          | User from install nginx        |

Example Playbook
----------------

```yaml
- name: Install LightHouse
  hosts: servers
  roles:
    - lighthouse
```


License
-------

MIT

Autor Infomation
----------------

Olga Lesnykh
