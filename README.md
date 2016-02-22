Role Name
=========

Manages Linux pam.d configuration. Very simple role to manage our needs. Easy to customize later on.

Requirements
------------

Teste with Ansible 1.9.4

Role Variables
--------------

Defaults given

```
pam_enabled: False

pam_use_sssd: False

# Use per-user /tmp, /var/tmp and /dev/shm directories?
pam_use_namespace: False
pam_tmp_inst_dir: /l/tmp-inst/
pam_var_tmp_inst_dir: /l/vartmp_inst/
```

Dependencies
------------

This role is written to be standalone.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-pam }

License
-------

Apache License
Version 2.0, January 2004


Author Information
------------------

https://github.com/mhakala

https://github.com/jabl
