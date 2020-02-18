Access 102 - Access Building Blocks
==========================

This class covers the following topics:

- Client-Side/Server-Side Authentication
- SSO Methods
- Policy Types & Scopes
- Troubleshooting

Expected time to complete: **1.25 hours**

.. NOTE::
  All work for this lab will be performed exclusively from the Windows
  jumphost. No installation or interaction with your local system is
  required.


  Lab Components
  ^^^^^^^^^^^^^^

  The following table lists VLANS, IP Addresses and Credentials for all
  components:

  +------------------------+-------------------------+--------------------------+
  | Component              | VLAN/IP Address(es)     | Credentials              |
  +========================+=========================+==========================+
  | jumpbox.f5lab.local    | - Management 10.1.1.10  | - user1/user1            |
  |                        | - External   10.1.10.10 | - user2/user2            |
  |                        | - Internal   10.1.20.10 |                          |
  +------------------------+-------------------------+--------------------------+
  | BIG-IP1.f5lab.local    | - Management 10.1.1.4   | - admin/admin            |
  |                        | - External   10.1.10.4  |                          |
  |                        | - Internal   10.1.20.4  |                          |
  +------------------------+-------------------------+--------------------------+
  | BIG-IP3.f5lab.local    | - Management 10.1.1.5   | - admin/admin            |
  |                        | - External   10.1.10.5  |                          |
  |                        | - Internal   10.1.20.5  |                          |
  +------------------------+-------------------------+--------------------------+
  | dc.f5lab.local         | - Management 10.1.1.7   | - administator/i3NqCqRQ  |
  |                        | - Internal   10.1.20.7  |                          |
  +------------------------+-------------------------+--------------------------+
  | iis.f5lab.local        | - Management 10.1.1.6   | - administator/i3NqCqRQ  |
  |                        | - Internal   10.1.20.6  |                          |
  +------------------------+-------------------------+--------------------------+
  | web.f5lab.local        | - Management 10.1.1.9   |                          |
  |                        | - Internal   10.1.20.9  |                          |
  |			     		           | - Internal   10.1.20.19 |                          |
  +------------------------+-------------------------+--------------------------+
  | radius.f5lab.local     | - Management 10.1.1.8   |                          |
  |                        | - Internal   10.1.20.8  |                          |
  +------------------------+-------------------------+--------------------------+


.. toctree::
   :maxdepth: 1
   :glob:

   module*/module*
