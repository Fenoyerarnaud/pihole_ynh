# Pi-hole pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/pihole.svg)](https://dash.yunohost.org/appci/app/pihole)  
[![Installer Pi-hole avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=pihole)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Pi-hole rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, merci de regarder [ici](https://yunohost.org/#/install_fr) pour savoir comment l'installer et en profiter.*

## Résumé
Blocage des publicités sur l'ensemble du réseau via votre propre matériel Linux

**Version embarquée:** 4.0

## Captures d'écran

![](https://i0.wp.com/pi-hole.net/wp-content/uploads/2016/12/dashboard212.png)

## Démo

Aucune démo pour cette application.

## Configuration

Utiliser le panneau d'administration de votre Pi-hole pour configurer cette application.

## Documentation

* Documentation officielle: Impossible à trouver
* Pi-hole en tant que serveur DHCP: [dhcp.md](./dhcp.md)
* Documentation YunoHost: Il n'y a pas d'autre documentation, n'hésitez pas à contribuer.

## Fonctionnalités spécifiques à YunoHost

* Accès privé au panneau d'administration.

#### Support multi-utilisateurs

#### Architectures supportées.

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/pihole%20(Community)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/pihole%20(Community)/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/jenkins/job/pihole%20(Community)%20(%7EARM%7E)/badge/icon)](https://ci-apps-arm.yunohost.org/jenkins/job/pihole%20(Community)%20(%7EARM%7E)/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/jenkins/job/pihole%20(Community)/badge/icon)](https://ci-stretch.nohost.me/jenkins/job/pihole%20(Community)/)

## Limitations

* Activer DHCP avec Pi-hole nécessite une configuration manuelle de votre routeur.
* Pi-Hole-FTL ne peut pas être mis à jour au-delà de la version 2.13.2, à cause de l'utilisation d'une option de dnsmasq non encore disponible sur Jessie.

## Informations additionnelles

## Liens

 * Reporter un bug: https://github.com/YunoHost-Apps/pihole_ynh/issues
 * Site de Pi-hole: https://pi-hole.net/
 * Site de YunoHost: https://yunohost.org/

---

Informations à l'intention des développeurs
----------------

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/pihole_ynh/tree/testing).

Pour tester la branche testing, merci de procéder ainsi.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pihole_ynh/tree/testing --verbose
ou
sudo yunohost app upgrade pihole -u https://github.com/YunoHost-Apps/pihole_ynh/tree/testing --verbose
```
