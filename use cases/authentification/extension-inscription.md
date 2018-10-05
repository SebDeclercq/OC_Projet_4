# Extension : Inscription

Si l'**Utilisateur** n'a pas encore de compte, un formulaire d'inscription doit lui être proposé.

Après saisie des informations requises (type nom, prénom, email, mot de passe, etc.) et soumission du formulaire, le système vérifie d'abord que les données saisies sont correctes. Ensuite, il vérifie dans la base de données si l'adresse email n'est pas déjà employée par un autre compte.

Si l'identifiant n'existe pas encore, le système crée le compte utilisateur et émet un email d'activation contenant un lien. Lorsque l'**Utilisateur** clique sur cette URL, le compte est activé et l'**Utilisateur** connecté.

Si l'email est déjà employé pour un autre compte, le système redirige l'**Utilisateur** vers la page de type "mot de passe oublié" (**se référer à l'extension appropriée**).
