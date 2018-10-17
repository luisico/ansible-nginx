Nginx
=====
Install and configure Nginx httpd server.

Ports 80, 443 or your custom ports need to be open. This role does not handle opening the ports.

Nginx can be configured by suppliying a file in `nginx_main_conf_path` or content in `ginx_main_conf_content`.

Requirements
------------
See `meta/main.yml`.

Role Variables
--------------
None.

Dependencies
------------
This role depends on EPEL.

Example Playbook
----------------
Example:
```
- hosts: server
  roles:
    - nginx
```

TODO
----
- Support different versions.
- Support repo from nginx site.
- Improve documentation.
- Option to disable server on port 80.
- Simplify ciphers.

Licence
-------
Released under the [MIT license](https://opensource.org/licenses/MIT).

Author Information
------------------
Luis Gracia while at [The Rockefeller University](https://www.rockefeller.edu):
- lgracia [at] rockefeller.edu
- GitHub at [luisico](https://github.com/luisico)
- Galaxy at [luisico](https://galaxy.ansible.com/luisico)

Rebecca Bennett while at [The Rockefeller University](https://www.rockefeller.edu).
