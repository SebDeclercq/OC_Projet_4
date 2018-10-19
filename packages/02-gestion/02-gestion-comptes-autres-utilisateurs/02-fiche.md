# UC 02-02 : gestion des comptes d'autres utilisateurs

## Présentation du cas

Un utilisateur aux droits étendus doit pouvoir manipuler les comptes d'autres utilisateurs.

Ce scénario étend l'UC 02-01 *"gestion des comptes utilisateurs"* en tant que __point d'extension__.

## Prérequis / condition(s) initiale(s)

L'utilisateur possède des droits étendus.

## Objectif(s)

Garantir la validité des informations utilisateurs en base.

## Acteur(s) principal(aux)

Opérateur de commande ou administrateur.

## Acteur(s) secondaire(s)

N/A

## Événement déclencheur

Un utilisateur aux droits étendus doit créer, modifier ou supprimer un compte utilisateur.

## Étape par étape

1. L'utilisateur est connecté et se rend sur la page de gestion des comptes.
2. L'utilisateur mène les actions qu'il désire.

## Scénarios alternatifs

2. 1. L'utilisateur souhaite créer un compte.
   2. Il complète le formulaire dédié avec les informations requises.
   3. A la soumission, le système contrôle la validité des nouvelles données, les enregistre ou les refuse
   4. et redirige l'utilisateur vers la page de gestion des comptes en l'alertant du succès ou de l'échec de l'opération.


2. 1. L'utilisateur souhaite modifier un compte.
   2. Il édite les informations qu'il désire grâce à un formulaire.
   3. A la soumission, le système contrôle la validité des nouvelles données, les enregistre ou les refuse
   4. et redirige l'utilisateur vers la page de gestion des comptes en l'alertant du succès ou de l'échec de l'opération.


2. 1. L'utilisateur souhaite supprimer un compte.
   2. Dans un formulaire dédié, il saisit deux fois son mot de passe et fournit une éventuelle explication.
   3. A la soumission, le système demande une dernière fois la validation de la suppression et l'opère si validée.
