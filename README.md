Ansible Role: memcached(pkg)
================================================================================
Install and configure memcached

- Install memcached using yum at CentOS 7
- Configure /etc/sysconfig/memcached

Requirements
--------------------------------------------------------------------------------

Role Variables
--------------------------------------------------------------------------------
The following variables are defined in defaults/main.yml file.

```yaml
memcached:
  enabled: true
  started: true
  ...
```

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - { role: azumakuniyuki.ar-memcached-pkg }
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](https://nyaan.jp)

