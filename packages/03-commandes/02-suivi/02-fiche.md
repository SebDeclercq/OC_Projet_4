# UC 03-02 : suivi de commandes

## Présentation du cas

Le système doit proposer une méthode de suivi à l'utilisateur, de la validation finale de la commande à la livraison.

## Prérequis / condition(s) initiale(s)

Une commande est passée.

## Objectif(s)

Permettre au client de suivre l'avancée de sa livraison et mener des opérations correctives si l'étape de la livraison l'autorise.

## Acteur(s) principal(aux)

Client ou opérateur de commande ou gestionnaire.

## Acteur(s) secondaire(s)

N/A

## Événement déclencheur

L'utilisateur souhaite consulter l'état de sa commande et/ou la modifier (voire l'annuler).

## Étape par étape

1. L'utilisateur affiche la page dédiée à la commande de son choix.
2. L'utilisateur interagit avec sa commande.

## Scénarios d'exception

2. 1. L'utilisateur souhaite modifier la commande.
   2. Si le travail de réalisation de la pizza n'est pas encore en cours.
      1. L'utilisateur peut modifier le contenu de sa commande
      2. L'utilisateur peut modifier ses informations de livraison.
   3. Si la livraison n'est pas encore en cours.
      1. L'utilisateur peut modifier ses informations de livraison.

<!-- -->

2. 1. L'utilisateur souhaite annuler sa commande.
   2. Si l'état de la commande le permet, le système supprime la commande.
   3. Si le paiement a été réalisé en ligne, le système annule le paiement auprès du système bancaire.
