# Ansible: auth-key

Create OpenSSH authorization keys, and push to a server

Available on Ansible Galaxy: [pgkehle.auth-key](https://galaxy.ansible.com/pgkehle/auth-key)

# Examples

## Create Keys 

```YAML
- hosts: all
  roles:
    - { role: pgkehle.auth-key, do_create: true, tags: ["create"] }
```

## License

MIT

## For local development testing

```bash
rsync -a ~/code/ansible-auth-key/* ~/.ansible/roles/pgkehle.auth-key
```

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))
