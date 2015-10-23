Getting started
===============

.. contents::
   :local:

Example inventory
-----------------

FIXME

Example playbook
----------------

Here's an example playbook which uses ``debops.influxdb_server`` role::

    ---

    - name: Configure influxdb_server
      hosts: debops_influxdb_server
      sudo: True

      roles:
        - role: debops.influxdb_server
          tags: influxdb_server
