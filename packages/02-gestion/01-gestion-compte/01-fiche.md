# UC 02-01 : gestion des comptes utilisateurs

## Présentation du cas

Un utilisateur décide de consulter, modifier ou supprimer son compte utilisateur.

## Prérequis / condition(s) initiale(s)

L'utilisateur est inscrit et possède un compte dans la base de données.

## Objectif(s)

Garantir à l'utilisateur la mainmise pleine et entière sur ses informations personnelles.

## Acteur(s) principal(aux)

Un utilisateur inscrit.

## Événement déclencheur

Un utilisateur décide de consulter, modifier ou supprimer son compte utilisateur.

## Étape par étape

1. L'utilisateur est connecté au site et se rend sur la page de gestion de son compte.
2. L'utilisateur consulte les informations stockées.
3. L'utilisateur mène les actions qu'il désire.

## Scénarios alternatifs

3. 1. L'utilisateur souhaite modifier son compte.
   2. Il édite les informations qu'il désire grâce à un formulaire.
   3. A la soumission, le système contrôle la validité des nouvelles données, les enregistre ou les refuse
   4. 1. Si l'opération échoue, il faudra afficher le formulaire avec les informations saisies et les champs erronés mis en évidence pour en faciliter la correction.
      2. Si l'opération est un succès, rediriger l'utilisateur vers la page de consultation.


3. 1. L'utilisateur souhaite supprimer son compte.
   2. Dans un formulaire dédié, il saisit deux fois son mot de passe et fournit une éventuelle explication.
   3. A la soumission, le système demande une dernière fois la validation de la suppression et l'opère si validée.

## Cas particuliers

1. L'utilisateur est un opérateur de commandes.

    __Point d'extension__ : créer ou modifier le compte d'un autre utilisateur.


1. L'utilisateur est un administrateur.

    __Point d'extension__ : créer, modifier ou supprimer n'importe quel compte utilisateur.
