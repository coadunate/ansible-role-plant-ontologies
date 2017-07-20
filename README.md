Plant Ontologies
=========

This role installs different ontologies onto a VM.

Requirements
------------

After cloning and before running the role, a `main.yml` file needs to be created which will list the different ontologies that you would like to install.

This role comes with **4** YAML files for the P2IRC themes which list the required ontologies for their respective themes. The file names of those themes are listed as under:

- Theme 3.1 -> theme3.1ontologies.yml
- Theme 3.2 -> theme3.2ontologies.yml
- Theme 3.3 -> theme3.3ontologies.yml
- Theme 3.5 -> theme.3.5ontologies.yml


**EXAMPLE 1** - `main.yml` file for installing Ontologies related to P2IRC Theme 3.1.

    - hosts: host_name_here
      tasks:
        - include: theme3.1ontologies.yml


License
-------

CC-BY

Author Information
------------------

Coaduante Organization
