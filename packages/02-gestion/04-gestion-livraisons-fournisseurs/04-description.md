# UC 02-04 : gestion des livraisons des fournisseurs

Le système doit permettre de gérer les stocks, afin notamment de vérifier la présence des ingrédients requis avant de valider une commande.

A la réception d'une livraison d'un fournisseur, il est nécessaire de tenir les stocks à jour. Ainsi, en cas d'arrivée d'un nouveau produit, celui-ci devra être inséré dans la base de données ainsi que sa quantité. En cas d'arrivée de produit existant, il faudra simplement modifier la quantité de ce dernier.

Idéalement, ce système devra être fortement automatisé afin d'affranchir les acteurs (n'importe quel employé de la pizzeria peut être concerné) d'opérations fastidieuses et peu gratifiantes. Il peut être envisagé de mettre en place un système de scan de codes-barres à la réception des livraisons du grossiste qui mettrait à jour les arrivées de produits.
