Monitoring-role
================

Устанавливает Prometheus, Alertmanager, Grafana

Requirements
------------

Для Prometheus нужен Node Exporter или другой, которых миллион )

Role Variables
--------------

Смотри 

Dependencies
------------

Смотри `Requirements`

Example Playbook
----------------

```yml
- name: Install Monitoring
  hosts: monitoring
  roles:
    - role: monitoring-role
```

License
-------

BSD

Author Information
------------------

Frolls
