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
      roles:
        - renderqwerty.hadolint

# License

MIT License

# Author

http://github.com/RenderQwerty/
