MediaWiki Ansible Playbook
==========================

Simple Ansible playbook for installing a secure and fast MediaWiki 1 installation on Debian 8.

Superuser privileges are required for most commands, so make sure to run the playbook with -b (and -K if you use a sudo password).

Variables
---------

- vhostname (e.g. "en.wikipedia.org")
- mediawiki_major_version (e.g. 28)
- mediawiki_minor_version (e.g. 2)
- article_path_name (e.g. "wiki" or "w")
