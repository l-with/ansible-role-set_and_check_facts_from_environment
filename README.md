# Ansible Role set and check facts from environment

set and check facts from environment variables

## Role Variables

### `set_and_check_facts_from_environment_required_vars`

the list of variables to get from environment

The variables are looked from the environment variables with the same name as in the list but in upper cases.
If the environment variable is not set, ansible.builtin.failed is used to fail.
