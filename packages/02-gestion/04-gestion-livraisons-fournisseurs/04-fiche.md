# UC 02-04 : gestion des livraisons des fournisseurs

## Présentation du cas

Afin de tenir les stocks à jour, il est nécessaire de modifier la base de données à la réception de nouveaux produits livrés par des fournisseurs.

## Prérequis / condition(s) initiale(s)

N/A

## Objectif(s)

Tenir les stocks à jour afin de garantir la bonne exécution des commandes.

## Acteur(s) principal(aux)

N'importe quel employé est susceptible de réceptionner une livraison.

## Acteur(s) secondaire(s)

N/A

## Événement déclencheur

Réception d'une livraison de produits.

## Étape par étape

1. Réception d'une livraison de produits.
2. Déballage et scan des codes-barres.
3. Mise à jour automatique de la base de données à jour (produits et quantité).

## Scénarios alternatifs

3. 1. Le produit existe en base.
   2. Seule la quantité disponible pour ce produit est modifiée.

<!-- -->

3. 1. Le produit n'existe pas en base.
   2. Insertion du produit et de sa quantité.
