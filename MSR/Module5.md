# Les risques de la virtualisation
---

## Les risques intrinseques 
En mutualisant les serveurs sur une meme machine, on augmente la criticite de la machine. 
La panne materielle d un serveur hote entraine  l arret de l ensemble des services consolides sur la machine.
--

La virtualisation entraine une augmentation des risques de securite informatique.
---

## Securite des acces

Le fait qu il soit beaucoup plus facile d etablir une connection entre des VM, presente un risque supplementaire en cas d erreur ou de malveillance de configuration.
--

La console est une machine virtuelle, particulierement sensible puisque les operations executees peuvent impacter l ensemble des VM supportees. Il est donc indispensable d en controler parfaitement les acces. Des acces illicites seraient lourds de consequences !
--

Un administrateur ayant tous les droits sur l infrastructure de virtualisation pourrait par exemple, en quelques clics, stopper des VM. Ce qui reviendrait à couper l alimentation d une partie d'un datacenter ! 
Il lui serait aussi possible de supprimer purement et simplement, tout ou partie des VM. Ce qui reviendrait a detruire des serveurs physiques et les donnees associees !
