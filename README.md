# Ansible Roles

Common roles for Ansible.

For example, if your, say, `web` role depends on Nginx, you could pull in this repository as a Git submodule, add the submodule's directory to `roles_path` in your Ansible config, and require the `nginx` role defined here in your playbook.
