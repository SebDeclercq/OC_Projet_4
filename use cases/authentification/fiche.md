# UC : Authentification

## Présentation du package

Un utilisateur (rôle **Utilisateur**) doit pouvoir se rendre sur une page d'authentification et soit se connecter s'il a déjà un compte pour le site, soit s'inscrire.

## Prérequis / condition(s) initiale(s)

N/A

## Objectif(s)

Permettre à un **Utilisateur** d'accéder à plus de fonctions sur le site web.

## Acteur(s) principal(aux)

N'importe quel acteur enfant du rôle **Utilisateur**.

## Acteur(s) secondaire(s)

N/A

## Événement déclencheur

L'**Utilisateur** veut se connecter au site web et se rend sur la page d'authentification.

## Étape par étape

1. L'**Utilisateur** accède au site web
2. L'**Utilisateur** se rend sur la page de connexion
3. L'**Utilisateur** rentre ses identifiants
4. Le système valide la connexion et l'**Utilisateur** accède à son compte

## Cas particuliers

#### Si l'**Utilisateur** n'a pas encore de compte
3. 1. L'**Utilisateur** remplit le formulaire d'inscription et le soumet
   2. 1. Le système enregistre le compte et émet un email d'activation
      2. A moins qu'un compte existe déjà, auquel cas le système redirige vers la page "mot de passe oublié" (se référer à l'extension suivante)
   3. L'**Utilisateur** active son compte

#### Si l'**Utilisateur** a oublié ses identifiants
3. 1. L'**Utilisateur** remplit le formulaire "mot de passe oublié"
   2. Le système retourne un email permettant la modification des identifiants
   3. L'**Utilisateur** les modifie

#### Si les informations fournies sont erronées
4. 1. Les identifiants renseignés ne sont pas acceptés par le système
   2. La connexion échoue et affiche un message d'erreur
