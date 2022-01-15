Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

---
## Liste des projets

Nom du projet | Description | Lien
---|---|----
GestionGlasses | Il s'agit du projet contenant notre application avec son code source, son dockerfile et un script docker-compose | [GestionGlasses](https://github.com/brikema/GestionGlasses)
GestionGlasses-role | Il s'agit du projet contenant notre rôle Ansible | [RoleAnsible](https://github.com/asemin08/GestionGlasses-role)
GestionGlasses-playground | Il s'agit du projet contenant notre playground Ansible | [PlaygroundAnsible](https://github.com/asemin08/GestionGlasses-playground)
GestionGlasses-terraform | Il s'agit du projet contenant notre script Terraform pour déployer l'application GestionGlasses | [Terraform](https://github.com/asemin08/GestionGlasses-terraform)
