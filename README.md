# Ansible Role - auth-key

Create, add and remove OpenSSH authorization keys

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

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))
