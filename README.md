Role Name
=========

Ansible Galaxy role for insalling php5-fpm

Role Variables
--------------

`
php5fpm_max_children: 10
php5fpm_start_servers: 4
php5fpm_min_spare_servers: 2
php5fpm_max_spare_servers: 6
php5fpm_max_requests: 2000
`

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: sparkfabrik.php5-fpm, php5fpm_max_children: 10, php5fpm_start_servers: 4, php5fpm_min_spare_servers:2, php5fpm_max_spare_servers:6, php5fpm_max_spare_servers:2000 }

License
-------

BSD
