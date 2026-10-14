# Problème rencontré 

Étape/version testée | Action | Résultat attendu | Résultat constaté
V0.1 | Modification de la couleur du fond et du texte | Changement des couleurs appliquées | Les couleurs ont bien changées

V0.2 | Pouvoir ajouter une confirmation | Ajout de la confirmation de la réservation | Confirmation ajouté mais pas visible car la couleur était confondu avec le fond

V0.3 | Amélioration | Rectifier les bugs | La confirmation est réapparue

V0.4 | Nom de l'activité | Ajouter le nom de l'activité réserver | Nom de l'activité ajoutée

V1 | Vérification | Tout doit fonctionner correctement | Tout fonctionne comme il faut 

Observations avant le hotfix:

Après la modification des couleurs, la confirmation de commande ne s'affiche plus car la couleur est confondu avec celle du fond.

Observations après le hotfix:
Une fois le hotfix réalisé, tout fonctionnait parfaitement. La confirmation est redevenu visible (git commit -m "Changement couleur confirmation reservation").

Base et branches : quel commit est le point de départ commun de A et B ? Donnez son identifiant et expliquez comment vous avez vérifié ce point de départ. Indiquez aussi les commits de main depuis lesquels hotfix et la quatrième branche ont été créées.

Fusion et fonctionnement : pourquoi une fusion Git réussie ne garantit-elle pas que le site fonctionne correctement ? Reliez votre réponse au problème de lisibilité rencontré ou anticipé.
Parce qu'il peut y avoir des conflits comme par exemple avec la couleur du texte

Commit et publication : après un commit local, qu'est-ce qui reste à faire pour que ce changement soit visible sur GitHub ? Donnez l'identifiant d'un de vos commits et indiquez où vous l'avez vérifié sur GitHub.

git push ("git commit -m "Changement couleur confirmation reservation"")