# ansible-role-utils

Helper Ansible Roles

## TLS Certificate `tlscert.yml`

```yaml
- name: "Include tasks from set_secret_vault_env"
    include_role:
    name: sourceshift.utils
    tasks_from: tlscert.yml
```
