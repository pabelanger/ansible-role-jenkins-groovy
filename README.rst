================
ansible-role-jenkins-groovy
================

Ansible role to manage Jenkins groovy scripts

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-jenkins-groovy.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-jenkins-groovy
* Bugs: https://bugs.launchpad.net/ansible-role-jenkins-groovy

Description
-----------

Secure Shell is a cryptographic (encrypted) network protocol to allow remote
login and other network services to operate securely over an unsecured network.

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install Jenkins groovy scripts
      hosts: jenkin
      roles:
        - ansible-role-jenkins-groovy
