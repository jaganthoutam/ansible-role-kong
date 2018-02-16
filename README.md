Role for Kong, Kong-Dashboard and Jupyter
=========

This Role will install and configure Kong, Kong Dashboard with Postgresql integration.

Install and configure Jupyter.

Requirements
------------

This Role is required for IDE Bigbrain.
IDE uses KONG as a Web Proxy.
KONG DASHBOARD helps developers to make the proxy entry easily through UI.


Role Variables
--------------

Role variables are defined in Defaults folder.
User variable can be externalised in the main playbook file.

Dependencies
------------

Postgresql V9.4+
Python3.5 (Bigbrain works on Python3+)
openssl
perl
procps


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      remote_user: user
      become: true
      become_method: sudo
      roles:
         - ansible-role-kong

License
-------

Razorthink INC

Author Information
------------------

Nishan P A

Devops Team
Razorthink Inc

Contributors:

Arjun Das M
Nitanka Gogoi
Muhammed Shahin
