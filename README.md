# Ansible Roles

Common Ansible roles for use on Ubuntu 14.04.

For example, if your, say, `web` role depends on Nginx, you could pull in this repository as a Git submodule, add the submodule's directory to `roles_path` in your Ansible config, and specify the `nginx` role defined here as a [dependency](http://docs.ansible.com/ansible/playbooks_roles.html#role-dependencies) of your `web` role.
