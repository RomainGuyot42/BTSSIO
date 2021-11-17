# Virtualisation du reseau
--

Un VLAN (Virtual Local Area Network ou Virtual LAN, en français Reseau Local Virtuel) est un reseau local regroupant un ensemble de machines de facon logique et non physique.
---

## Typologie de VLAN
--

### VLAN de niveau 1

Les Vlans par port associent un port d'un switch à un numero de Vlan. On dit alors que le port est tague suivant le Vlan donne. Le switch entretien ensuite une table qui lie chaque Vlan au port associe. Le taggage des ports peut se faire de maniere statique ou dynamique 
--

### VLAN de niveau 2

Egalement appele VLAN MAC, ou MAC Address-Based VLAN. Il consiste a definir un reseau virtuel en fonction des adresses MAC des stations. Ce type de VLAN est beaucoup plus souple que le VLAN par port car le reseau est independant de la localisation de la station.
--

### VLAN de niveau 3

Les Vlans de niveau 3 permettent de regrouper plusieurs machines suivant le sous reseau auquel elles appartiennent. La mise en place de Vlan de niveau 3 est conditionne par l'utilisation d'un protocole IP
