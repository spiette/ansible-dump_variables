# dump_variables

This role will dump all variables in a yml file on the host, and will fetch it back locally.

## Usage

Create a playbook and apply to host(s) 

```
---
- name: Get all variables
  hosts: all
  roles:
    - dump_variables
```

