Role Clickhouse
=========

This role can install Clickhouse.

    Установка:
        clickhouse-client
        clickhouse-server
        clickhouse-common-static
    Создаётся БД
    Создаётся таблица для логов
    Создаётся пользователь для записи в БД
    Конфигурируется clickhouse-server для работы внешних подключений



Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

|Переменная|Описание| 
|-|--------|
|clickhouse_version|версия clickhous| 


Dependencies
------------


Example Playbook
----------------
```
hosts: clickhouse
roles:
  - role: clickhouse-role
```
License
-------

MIT

Author Information
------------------
Awertoss
