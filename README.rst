============================
ansible-role-jenkins-plugins
============================

Ansible role to manage Jenkins plugins

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-jenkins-plugins.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-jenkins-plugins
* Bugs: https://bugs.launchpad.net/ansible-role-jenkins-plugins

Description
-----------

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

ansible-role-jenkins
~~~~~~~~~~~~~~~~~~~~
See http://ansible-role-jenkins.readthedocs.org/ for more information.

Example Playbook
----------------

.. code-block:: yaml

    - name: Install Jenkins plugins
      hosts: jenkin
      roles:
        - ansible-role-jenkins-plugins
