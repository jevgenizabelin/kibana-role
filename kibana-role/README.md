Kibana role
=========

Роль для установки kibana на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и RHEL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| kibana_version | "7.14.0" | Параметр, который определяет какой версии elasticsearch будет установлен |


Example Playbook
----------------

    - hosts: all
      roles:
         - kibana_role

License
-------

MIT

Author Information
------------------

JZ:ee.jzabelin@gmail.com
