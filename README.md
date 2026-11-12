# SAÉ5.02 - Téléphonie IP automatisée avec Ansible

Déploiement automatisé d'une téléphonie IP (Asterisk, MariaDB) pour une
PME d'une vingtaine de postes, dans des conteneurs Docker pilotés par
Ansible.

## Prérequis
- VM Debian 13 avec SSH et Ansible
- Docker et Docker Compose (installés par le rôle docker)

## Lancer le déploiement
    ansible-playbook -i inventory/hosts.ini playbooks/site.yml --ask-vault-pass
