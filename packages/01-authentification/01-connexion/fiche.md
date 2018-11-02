# UC 01-01 : connexion

## Présentation du package

Un utilisateur doit pouvoir se rendre sur une page d'authentification pour se connecter au site.

## Prérequis / condition(s) initiale(s)

N/A

## Objectif(s)

Permettre à un utilisateur d'accéder à plus de fonctions sur le site web.

## Acteur(s) principal(aux)

N'importe quel acteur enfant du rôle **Utilisateur**.

## Acteur(s) secondaire(s)

N/A

## Événement déclencheur

L'utilisateur veut se connecter au site web et se rend sur la page d'authentification.

## Étape par étape

1. L'utilisateur accède au site web.
2. L'utilisateur se rend sur la page de connexion.
3. L'utilisateur rentre ses identifiants.
4. Le système valide la connexion et l'utilisateur accède à son compte.

## Cas particuliers

3. L'utilisateur n'a pas encore de compte.

  __Point d'extension__ : s'inscrire (**UC 01-02**).


3. L'utilisateur a oublié ses identifiants.

   __Point d'extension__ : mot de passe oublié (**UC 01-03**).


4. 1. Les informations fournies sont erronées.
   2. Les identifiants renseignés ne sont pas acceptés par le système.
   3. La connexion échoue et affiche un message d'erreur.
