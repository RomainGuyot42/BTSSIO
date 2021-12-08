# Les risques de la virtualisation
---

## Les risques intrinseques 
En mutualisant les serveurs sur une meme machine, on augmente la criticité de la machine. 
La panne materielle d un serveur hote entraine  l arret de l ensemble des services consolides sur la machine.
--

La virtualisation entraine une augmentation des risques de securite informatique.
---

## Securite des acces

Le fait qu il soit beaucoup plus facile d etablir une connection entre des VM, presente un risque supplementaire en cas d erreur ou de malveillance de configuration.
--

La console est une machine virtuelle, particulierement sensible puisque les operations executees peuvent impacter l ensemble des VM supportees. Il est donc indispensable d'en controler parfaitement les acces. Des accès illicites seraient lourds de consequences !
