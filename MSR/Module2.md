# Virtualisation du stockage
---

## Principe de base

La virtualisation du stockage est de gerer une interface qui permet de dissocier la gestion physique des disques (et des baies de stockage) vis-a-vis des serveurs qui l'utilisent.
---

## DAS

Direct-attached storage (ou disque en attachement direct) decrit un type de peripherique de stockage relie directement a un ordinateur et non accessible a d’autres ordinateurs ou un serveur. L’exemple le plus typique d’un stockage DAS est le disque dur interne d’un ordinateur ou d’un serveur.
--

## NAS

Network Attached Storage ou serveur de stockage en reseau. Cette methode permet de connecter une baie de stockage sur le reseau au moyen de plusieurs protocoles tels que AFS, CIFS, FTP, NFS, SSH, WebDav. Des peripheriques heterogenes, connectes sur un meme segment reseau, peuvent y acceder a travers une adresse IPv4 ou IPv6.
--

## SAN

Storage Area Network ou réseau de stockage en français. Cette méthode permet de mutualiser les baies de stockage dans un réseau dédié
--

## Avantages du NAS et SAN par rapport au DAS

 L’environnement de stockage est évolutif. 
 A tout moment, des ressources peuvent être ajoutées au fur et à mesure de l’augmentation de la demande. 
 Les ressources non utilisées peuvent être facilement attribuées à un autre serveur ou dédiée à une autre utilisation 
 L’administration est centralisée sur un seul périphérique de stockage. Le technicien n’a plus besoin de gérer une multitude de périphériques indépendants.
