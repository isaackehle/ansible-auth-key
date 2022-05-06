# Ansible Role - auth-key

Create, add and remove OpenSSH authorization keys

Available on Ansible Galaxy: [isaackehle.auth-key](https://galaxy.ansible.com/isaackehle/auth-key)

## Examples

```YAML
- hosts: all
  roles:
    - { role: isaackehle.auth-key, do_create: true, tags: ["create"] }
```

## Linting

```bash
yamllint -c yamllint.yaml .
ansible-lint .
```

## License

MIT

## Author Information

Isaac Kehle
@isaackehle ([twitter](https://twitter.com/isaackehle), [github](https://github.com/isaackehle), [linkedin](https://www.linkedin.com/in/isaackehle))
