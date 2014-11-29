# Ansible Role: nginx


A role to setup nginx

## Requirements

## Role Variables
- `nginx_install_mainline: true` will use the mainline debs from nginx.org instead of the standard trusty ones. Swithching between sources is not currently supported. Future versions may standarize on one source and possible support building from source.

## Dependencies

## Example Playbook

    - hosts: servers
      roles:
         - MatthewMi11er.nginx

## License

MIT

## Author Information
