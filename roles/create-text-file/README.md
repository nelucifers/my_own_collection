Ansible role: create-text-file
=========

This role create text file with your content.

Role Variables
--------------

User variables are located in (defaults/main.yml[defaults/main.yml])

| Name | Default Value | Description |
|------|---------------|-------------|
| path | /tmp/example.txt | Path to file |
| content | 'Test content' | Content written to file |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - create-text-file

License
-------

This project is licensed under MIT License.


