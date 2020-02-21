# PROJET platerforme d'intégration continue

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)  [![forthebadge](http://forthebadge.com/images/badges/powered-by-electricity.svg)](http://forthebadge.com)

Projet CD du 20/02 au 21/02 2020. 
1. déployer une plateforme d'intégration continue (PIC) intégrant des outils de CI/CD.
2. développer une chaîne complète de déploiement continue permettant de faire des mise en production (MEP) automatiquement, avec possibilité de rollback.


## Pour commencer

Entrez ici les instructions pour bien débuter avec votre projet...

### Pré-requis

Vous devez absolument avoir Vagrant d'installé sur votre machine.
Si vous devez installer Vagrant [Cliquez ici](https://www.vagrantup.com/downloads.html)
Choisissez la bonne version à installer selon votre OS

### Installation

Il vous faudra d'abord récupérer les 4 dossiers suivants : 
- master-vagrant
- slave-vagrant
- test-vagrant
- prod-vagrant

Chacun de ces dossiers contient un Vagrantfile.
Sur le terminal windows, placez vous au niveau du dossier master-vagrant et lancez la commande :
vagrant up

Répétez l'opération dans chacun des dossiers -vagrant 

A la fin, vous devriez avoir 4 machines virtuelles qui tournent avec tout ce qu'il faut pour chaque machine.

## Démarrage

Dites comment faire pour lancer votre projet

## Fabriqué avec

* [Vagrant](https://www.vagrantup.com/)
* [Git](https://git-scm.com/)
* [Github](https://github.com/)
* [Gitlab](https://about.gitlab.com/)
* [Jenkins](https://jenkins.io/)
* [Java](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html)
* [Maven](https://maven.apache.org/)
* [Docker](https://www.docker.com/)
* [Ansible](https://www.ansible.com/)


## Auteurs

* **Raphaël Seguin** _alias_ [@raphaelSeguin](https://github.com/raphaelSeguin)
* **Sebastian Castaño Palacio** _alias_ [@NekoTorll](https://github.com/NekoTorll)
* **Salim Gharmoul** _alias_ [@Salimpossible](https://github.com/Salimpossible)

Lisez la liste des [contributeurs](https://github.com/raphaelSeguin/pic_tp/graphs/contributors) pour voir qui à aidé au projet !


## License

Ce projet est sous licence `` GTM ``


