# UC 01-03 : mot de passe oublié

Si l'utilisateur ne se souvient plus de ses identifiants, il lui est possible de se rendre sur une page de type "mot de passe oublié". L'utilisateur remplit le formulaire et reçoit après soumission un email contenant un lien permettant de réinitialiser son mot de passe si l'email renseigné existe dans la base de données. En cliquant sur cette URL et en changeant le mot de passe, l'utilisateur est connecté et son compte modifié.

__Point d'extension :__ si l'email n'existe pas dans la base de données, il est proposé à l'utilisateur de s'inscrire, se référer au cas spécifique.

Ce scénario étend les cas d'utilisation "connexion" et "inscription" en tant que point d'extension.
