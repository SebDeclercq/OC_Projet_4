# UC 01-02 : inscription

## Présentation du cas

Si l'utilisateur n'a pas encore de compte, un formulaire d'inscription doit lui être proposé.

## Prérequis / condition(s) initiale(s)

N/A

## Objectif(s)

Permettre à un utilisateur de se créer un compte pour le site web, afin de pouvoir s'en servir pleinement.

## Acteur(s) principal(aux)

*Client potentiel*

## Acteur(s) secondaire(s)

N/A

## Événement déclencheur

L'utilisateur veut s'inscrire.

## Étape par étape

1. L'utilisateur remplit le formulaire d'inscription et le soumet.
2. Le système enregistre le compte et émet un email d'activation.
3. L'utilisateur active son compte.

## Cas particulier

2. Un compte associé à l'email existe déjà.

   __Point d'extension__ : mot de passe oublié (**UC 01-03**).


2. 1. Le formulaire soumis est indûment complété
   2. Le système retourne à la page d'inscription en y réinsérant les valeurs saisies, en prenant soin de signaler en rouge le(s) champ(s) erroné(s).
