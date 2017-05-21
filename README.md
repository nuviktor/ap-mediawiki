MediaWiki Ansible Playbook
==========================

Simple Ansible playbook for installing a secure and fast MediaWiki 1 installation on Debian 8.

Superuser privileges are required for all tasks, so make sure to run the playbook with -b (and -K if you use a sudo password).

Variables
---------

- vhostname (e.g. "en.wikipedia.org")
- vhostaliases (optional, a list of host values that should also be served by the wiki)
- mediawiki_major_version (e.g. 28)
- mediawiki_minor_version (e.g. 2)
- install_path (e.g. "/var/www/wiki"), make sure there is no trailing slash
- article_path_name (e.g. "wiki" or "w", default "wiki")
- apache_port (e.g. 80, default 80)
