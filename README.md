Ansible Role: PhpMyAdmin
=========

[![Build Status](https://travis-ci.org/CarlosLongarela/ansible-role-phpmyadmin.svg?branch=master)](https://travis-ci.org/CarlosLongarela/ansible-role-phpmyadmin)

Install PhpMyAdmin with config file.

Requirements
------------

None.

Role Variables
--------------

    phpmyadmin_folder: "/home/webs/phpmyadmin"


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers

      gather_facts: no
      become: true

      vars:
        phpmyadmin_folder: "/home/webs/prestashop.test/public/phpmyadmin"

       roles:
         - { role: CarlosLongarela.phpmyadmin }

License
-------

GPLv2

Author Information
------------------

This role was created in 2017, May by [Carlos Longarela](mailto:carlos@longarela.eu), from [Taberna WordPress](https://tabernawp.com/).
