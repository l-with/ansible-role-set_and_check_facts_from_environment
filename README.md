# Ansible Role set and check facts from environment

sets and checks facts from environment variables on control node

## Role Variables

### `set_and_check_facts_from_environment_required_vars`

the list of variables to get from environment

The variables are looked up from the environment variables with the same name as in the list, but in upper cases.
If the environment variable is not set, ansible.builtin.failed is used to fail.
