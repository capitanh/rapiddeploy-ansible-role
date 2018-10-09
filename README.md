Rapiddeploy ansible role
=========
This role will download and install Midvision RapidDeploy

Requirements
------------
None

Role Variables
--------------
This role requires the following variables to be defined elsewhere in the playbook that uses it:
```yaml
  rapiddeploy_user:       rdeploy                         #Rapid Deploy system user
```

Dependencies
------------
None

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------
Register the role in requirements.yml:
```yaml
    - src: capitanh.rapiddeploy-ansible-role
      name: rapiddeploy
```
Include it in your playbooks:
```yaml
    - hosts: servers
      roles:
      - rapiddeploy
```
License
-------
BSD

