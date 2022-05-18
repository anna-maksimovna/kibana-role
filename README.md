Kibana-role
=========

Роль для установки Kibana

Requirements
------------

Для ОС семейств debian и EL

Role Variables
--------------

|      vars      |         description         |
|:--------------:|:---------------------------:|
| kibana_version | Версия Kibana для установки |



Example Playbook
----------------


    - hosts: all
      roles:
         - { role: kibana-role }

License
-------

BSD

Author Information
------------------

Anna M
