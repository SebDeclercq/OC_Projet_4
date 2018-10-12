# UC 01-03 : mot de passe oublié

## Présentation du cas

L'utilisateur a oublié ses identifiants.

## Prérequis / condition(s) initiale(s)

L'utilisateur possède un compte sur le site web.

## Objectif(s)

Réinitialiser le mot de passe afin d'autoriser la connexion au site.

## Acteur(s) principal(aux)

*Client* ; **Utilisateur interne**

## Acteur(s) secondaire(s)

N/A

## Événement déclencheur

L'utilisateur a oublié ses identifiants.

## Étape par étape

1. L'utilisateur remplit le formulaire "mot de passe oublié".
2. Le système retourne un email permettant la modification des identifiants.
3. L'utilisateur les modifie et se retrouve connecté si les nouvelles valeurs sont correctes.

## Cas particuliers

2. L'email n'existe pas dans la base de données.

   __Point d'extension__ : s'inscrire.
