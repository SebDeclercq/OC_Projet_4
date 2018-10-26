# UC 03-03 : livraison

## Présentation du cas

Lorsque la commande est prête, le livreur doit l'acheminer chez le client.

## Prérequis / condition(s) initiale(s)

La commande est prête à être livrée.

## Objectif(s)

Clôturer la commande en effectuant la livraison et en percevant son paiement.

## Acteur(s) principal(aux)

Le livreur.

## Acteur(s) secondaire(s)

Le client.

## Événement déclencheur

La commande est prête.

## Étape par étape

1. Le livreur récupère la commande et change le statut de la commande à "livraison en cours".
2. Le livreur se rend chez le client et délivre la commande.
3. Le client signe dans l'application et le statut de la commande passe à "terminée".

## Scénario(s) alternatif(s)

2. 1. Si le client n'a pas payé en ligne.
   2. Le livreur encaisse le paiement (chèque ou espèce).
