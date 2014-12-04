# Ansible Role: nginx


A role to setup nginx

## Requirements

## Role Variables
- `nginx_install_type: mainline`  
   current options are `mainline` to use the [nginx.org deb source](http://nginx.org/en/linux_packages.html) or `ubuntu` to use the default Ubuntu deb source. Switching between install types is not currently supported. Future versions may standarize on one source and possibly support building from source.
- `nginx_enable_default_https: false`  
   Set to `true` if you would like to create a default host for https requests. To use this you must pass in the appropriate `nginx_private_key` and `nginx_private_key`.
- `nginx_enable_default_http: true`  
   Set to `false` fi you do not want create a default host for http requests.

## Dependencies

## Example Playbook

    - hosts: servers
      roles:
         - MatthewMi11er.nginx

## License

MIT

## Author Information
