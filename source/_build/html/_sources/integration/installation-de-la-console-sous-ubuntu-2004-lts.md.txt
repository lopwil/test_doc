---
title: "Installation de la console sous Ubuntu 20.04 LTS"
slug: "installation-de-la-console-sous-ubuntu-2004-lts"
hidden: false
createdAt: "2021-06-01T10:12:55.289Z"
updatedAt: "2021-06-28T07:38:26.255Z"
---
[block:api-header]
{
  "title": "Installation"
}
[/block]
Wisper met à disposition un paquet .deb pour l'installation de la console sous Ubuntu 20.04 LTS. Ce paquet est également compatible avec Fedora et les autres distributions RedHat.

Ces paquets peuvent être installés en utilisant l'interface graphique ou en ligne de commande. L'installation via l'interface graphique nécessite le paquet gdebi pour pouvoir installer le paquet .deb s'il n'est pas pris en charge par défaut.

L'installation en ligne de commande se fait avec la commande suivante.
[block:code]
{
  "codes": [
    {
      "code": "sudo dpkg -i consoleCebox233-linux.deb",
      "language": "shell"
    }
  ]
}
[/block]
Une fois celui-ci installé, le terminal indique que la console peut être lancée par l'icône de lancement ou en ligne de commande.

La console est alors prête à être lancée. Se référer à [l'installation sur Windows](doc:installation-de-la-console#pour-windows-) pour les identifiants à renseigner.