Role Name
=========

Just download the [script_caller](https://github.com/kleinstuff/script_caller) script on {{ script_caller__dest }}

Requirements
------------

Internet access.
Linux.

Role Variables
--------------

script_caller__dest: Destination to download the script. Default: /usr/bin/script_caller.sh

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: istall-script_caller }
```

License
-------

BSD

Author Information
------------------

[RKlein](https://rklein.com.br).
