# UC 02-03 : gestion des recettes

## Présentation du cas

Le système doit permettre la gestion de recettes de cuisine, allant de la consultation à la création en passant par la modification. Le formulaire de création de recettes doit inclure une section dédiée aux ingrédients et à leur quantité afin d'automatiser la gestion des stocks, ainsi qu'une option permettant l'affichage ou non du produit dans le catalogue.

## Prérequis / condition(s) initiale(s)

L'utilisateur possède des droits étendus.

## Objectif(s)

- Offrir des aide-mémoire aux pizzaiolos.
- Faciliter la gestion du catalogue.
- Faciliter l'automatisation de la gestion des stocks.

## Acteur(s) principal(aux)

Pizzaiolo ou administrateur.

## Acteur(s) secondaire(s)

N/A

## Événement déclencheur

Un utilisateur décide de consulter, créer ou modifier une recette de cuisine.

## Étape par étape

1. L'utilisateur est connecté et se rend sur la page de gestion des comptes.
2. L'utilisateur mène les actions qu'il désire.

## Scénarios alternatifs

2. 1. L'utilisateur souhaite consulter une recette.
   2. L'utilisateur emploie le moteur de recherche afin de récupérer la recette souhaitée.

<!-- -->

2. 1. L'utilisateur souhaite créer une recette.
   2. L'utilisateur complète le formulaire dédié et le valide.
   3. Le système contrôle automatiquement la disponibilité des stocks et affiche la recette en vente (ou indisponible) dans le catalogue de vente si l'affichage est autorisé.

<!-- -->

2. 1. L'utilisateur souhaite modifier une recette.
   2. Il édite la recette souhaitée et valide le formulaire.
   3. Le système contrôle automatiquement la disponibilité des stocks et affiche la recette en vente (ou indisponible) dans le catalogue de vente si l'affichage est autorisé.
