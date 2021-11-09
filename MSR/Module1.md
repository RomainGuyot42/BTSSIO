# Virtualisation
---

# Interets de la virtualisation
--

- Permet d'utiliser un logiciel sur un OS different de celui d'origine
- Faire cohabiter simultanement differents "univers" sur une machine
- creer differents environnements de developpement et/ou de tests specifiques sur une meme et unique machine.
---

# Outils de virtualisation
--

## VirtalBox

Avantages : 
- Facile d'utilisation
- Open Source

Inconvenient :
- Moins performant
- Donnees non chiffrees par défaut
--

## VM Ware

Avantages : 
- Performant 
- Donnees chiffrees

Inconvenient :
- Certaines foctionalitees sont payante 
--

## Hyper V

Avantages : 
- Performant
- Données chiffrées
- Deja installe sur W10 Pro
- Gratuit

Inconvenient :
- Difficile d'utilisation
- Uniquement sur Windows 10 Professionnel
---
 # Pricipes Fondamentaux
 --
 
 ## Cloisonnement
chaque système d’exploitation a un fonctionnement indépendant, et ne peut 
interferer avec les autres en aucune maniere.
--

## La transparence 
Le fait de fonctionner en mode virtualise ne change rien au fonctionnement du 
système d’exploitation et a fortiori des applications. 
La transparence implique la compatibilite : toutes les applications peuvent tourner sur un système virtualise, et leur fonctionnement n’est en rien modifie.
---

# Les Hyperviseurs
--

Un hyperviseur est une plateforme de virtualisation qui permet a plusieurs systèmes d’exploitation de travailler sur une meme machine physique en meme temps. 
--

## Hyperviseur de Type 1

