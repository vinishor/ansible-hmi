# Ansible-hmi

## French version

### Description

Ce dépôt est utilisé pour les déploiements automatiques Ansible sur l'infrastructure HMI. Il contient la configuration globale et les roles utilisés par le playbook.  
La collection **community-general** est utilisée pour le bon fonctionnement du playbook (notamment sur la partie OpenSUSE de l'infra). Son installation est possible via les prérequis définies.

### Comment l'utiliser ?

Pour utiliser ce dépôt, reportez-vous aux playbooks correspondants :

 * *setup.yml* pour configurer un serveur pour la première fois
 * *nas.yml* pour configurer le serveur NAS
 * *monitoring.yml* pour configurer et mettre en place le système de monitoring
 * *localdns.yml* pour mettre à jour la configuration du resolveur DNS local

---

## English version

### Description

This repository is used for Ansible's automatic deployments on the HMI infrastructure. It contains the global confguration and the roles used by the playbook.  
The collection **community-general** is necessary for using the playbook (mainly for the OpenSUSE part). Its installation is possible thanks to the defined requirements.

### How to use it?

To use this repository, refer to the corresponding playbooks:

 * *setup.yml* to configure a server for the first time