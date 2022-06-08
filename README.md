NAT Policy Configuration
=========

Configure NAT Policy for Junos.

Requirements
------------


Role Variables
--------------
nat_policies: List of Dictionaries containing NAT Policy

nat_policies_settings: Dictionary containing settings for NAT Policy


Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_nat_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
