# Ansible Role: nginx


A role to setup nginx

## Requirements

## Role Variables
- `nginx_install_type: mainline` will use the mainline debs from nginx.org instead of the standard trusty ones. Swithching between sources is not currently supported. Future versions may standarize on one source and possible support building from source.
- `nginx_enable_default_https`
- `nginx_enable_default_http`
- `nginx_root`

## Dependencies

## Example Playbook

    - hosts: servers
      roles:
         - MatthewMi11er.nginx

## License

MIT

## Author Information
