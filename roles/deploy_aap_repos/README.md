deploy_aap_repos
=========

A role to deploy Ansible Automation Platform Server repos to a subscribed Redhat Host

Requirements
------------

RHEL8 or RHEL9 host that is subscribed via subscription-manager to Red Hat

Role Variables
--------------

None

Dependencies
------------

collections:
	- rsquared.infra

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: deploy_aap_repos

License
-------

MIT

Author Information
------------------

Randy Romero  
binbashroot@gmail.com
