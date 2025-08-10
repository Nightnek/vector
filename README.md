Role Name
vector
=========

Requirements
Ubuntu linux >=20.04
--------------

Role Variables
vector_version: "0.41.1"
vector_os_arch: "x86_64"
vector_workdir: "/tmp/vector"
vector_os_user: "vector"
vector_os_group: "vector"
vector_data_dir: "/var/lib/vector"
--------------

Dependencies
clickhouse
lighthouse
------------

Example Playbook
- name: Vector
  hosts: vector
  gather_facts: false
  tags: vector
  roles:
    - vector
----------------

License
-------

BSD

Author Information
Grigory Stasenko
github.com/Nightnek
------------------
