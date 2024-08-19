# Ansible Role: Lynis

Installs [Standard Notes](https://standardnotes.com/) on Linux.

## Role Variables

```
standardnotes_working_director
standardnotes_port
standardnotes_db_username
standardnotes_db_password
standardnotes_db_root_password
```

## Dependencies

None.

## Example Playbook

```yaml
- hosts: server1
  roles:
    - charlesshook.standardnotes
```

## License

MIT