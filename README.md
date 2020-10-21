Raspberry-Git-Server
=========

Setup a GIT-Server with Raspberry OS and USB Drive

Requirements
------------

1) You have to be able to access your Raspberry via SSH already.
2) You need an empty USB Stick with the name "GIT"
3) The USB Stick have to be ext4 formatted

Role Variables
--------------

```
diskName: "GIT"
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: raspberrypi
      remote_user: pi
      become: yes
      
      roles:
        - role: raspberry-git-server

License
-------

MIT

Author Information
------------------

Ruslan Walch