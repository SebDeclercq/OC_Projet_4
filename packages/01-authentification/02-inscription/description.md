# UC 01-02 : inscription

Si l'utilisateur n'a pas encore de compte, un formulaire d'inscription doit lui être proposé.

Après saisie des informations requises (type nom, prénom, email, mot de passe, etc.) et soumission du formulaire, le système vérifie d'abord que les données saisies sont correctes. Ensuite, il vérifie dans la base de données si l'adresse email n'est pas déjà employée par un autre compte.

Si l'identifiant n'existe pas encore et que le formulaire est dûment renseigné, le système crée le compte utilisateur et émet un email d'activation contenant un lien. Lorsque l'utilisateur clique sur cette URL, le compte est activé et l'utilisateur connecté.

Si le formulaire est mal renseigné, le système retourne à la page d'inscription en y réinsérant les valeurs saisies, en prenant soin de signaler en rouge le(s) champ(s) erroné(s) et une éventuelle indication de correction.

__Point d'extension :__ si l'email est déjà employé pour un autre compte, le système redirige l'utilisateur vers la page de type "mot de passe oublié", se référer au cas spécifique.

Ce scénario étend les cas d'utilisation "connexion" et "inscription" en tant que point d'extension.
