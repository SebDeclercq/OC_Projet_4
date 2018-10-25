# UC 03-01 : création d'une commande

## Présentation du cas

Un client ou un futur client souhaite passer commande. Il doit pouvoir sélectionner les produits souhaités dans le catalogue proposé sur le site web et ensuite fournir toutes les informations requises (identité, adresse, paiement) pour permettre la validation de la commande. Après la validation de la commande, les stocks sont modifiés automatiquement, de même que le catalogue en ligne.

## Prérequis / condition(s) initiale(s)

N/A

## Objectif(s)

Commander des pizzas.

## Acteur(s) principal(aux)

Client ou client potentiel.

## Acteur(s) secondaire(s)

N/A

## Événement déclencheur

Un client ou un futur client souhaite passer commande.

## Étape par étape

1. Le client se constitue un panier grâce au catalogue.
2. Le client se connecte (__cas d'utilisation 01-01__) ou s'inscrit (__cas d'utilisation 01-02__), à moins qu'il ne soit déjà connecté.
3. Le client vérifie l'exactitude des informations (identité, adresse, etc.).
4. Le client choisit son mode de paiement et soumet sa commande.
5. La commande est validée. Les stocks sont modifiés automatiquement sur base de la commande, de même que le catalogue en ligne.

## Extension

3. 1. Les informations sont erronées.
   2. Le client les corrige et celles-ci sont mises à jour dans son compte utilisateur.

<!-- -->

4. 1. Le client choisit de payer en ligne.
   2. Il est redirigé vers un système de paiement en ligne externe et valide son paiement.
