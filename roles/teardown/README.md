Role Name
=========

Destroys Azure VMs and their Dependencies including NIC, subnet, IP, vnet, security group, storage account, and resource group

Requirements
------------
- This role uses multiple azure_rm_* modules
- Azure subscription, service principle, and credentials.  
- See Getting Started with Azure: https://docs.ansible.com/ansible/guide_azure.html

Role tags
--------------
teardown


Example Playbook, site.yml
----------------

    - hosts: servers
      roles:
         - {role: teardown, tags: ['teardown']}

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
