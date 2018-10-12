# UC : Consultation

Lorsqu'un **Utilisateur** se rend sur le site web, il doit pouvoir consulter différents contenus. Les droits de lecture sont étroitement liées aux autorisations d'accès, associées aux fonctions définies.

Ainsi, n'import quel **Utilisateur**, même non loggé, aura le droit de consulter les pages génériques (accueil, CGV, etc.) ainsi que le catalogue, son panier et la page de connexion/inscription.

Un moteur de recherche sera proposé dans les différentes pages, afin de fluidifier l'UX.

Si l'**Utilisateur** se logge, il aura accès aux sections du site attribuées à leur fonction, à savoir :

| Droits d'accès                        | Acteur(s) autorisé(s)                                |
|---------------------------------------|------------------------------------------------------|
| Consultation du catalogue             | **Utilisateur**                                      |
| Consultation du stock                 | *Gestionnaire* ; *pizzaiolo*                         |
| Consultation des recettes             | *Gestionnaire* ; *pizzaiolo*                         |
| Consultation des commandes            | **Passeur de commande** ; *Gestionnaire* ; *Livreur* |
| Consultation des comptes utilisateurs | *Client* ; **Utilisateur interne**                   |

Le contrôle des droits d'accès se fera dans table dédiée aux **Utilisateurs** dans la base de données du SI.

Si l'accès est refusé, il faudra alerter l'utilisateur avant de le rediriger vers la page d'accueil.

## Diagramme de cas

![diagramme du use case "Consultation"](../../diagrammes/use%20cases/consultation/uc-consultation.png)
