# Ansible role for hadolint

This role will install hadolint docker linter.
# Usage example
    ansible-galaxy install renderqwerty.hadolint

Add this to your playbook:

    - name: install hadolint to localhost
      hosts: localhost
      connection: local
      become: yes
      gather_facts: true
      vars:
        - version: 'v1.10.4'
        - dest_path: /bin
      roles:
        - renderqwerty.ansible_galaxy_hadolint

# License

MIT License

# Author

http://github.com/RenderQwerty/
