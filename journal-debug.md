# Journal de débogage
Nom : chaoub imane

| N° | Action pour reproduire | Résultat attendu / obtenu | Hypothèse et cause identifiée | Correction | Test après correction |
| --- | --- | --- | --- | --- | --- |
| 1 | appel de l'id | appel correct de lemplacement de liste | l'id de lemplacement est incorrect | l'ajout de s a la fin de l'id | appel correct de l'id|
| 2 | validation des champs | le nom et la quantite non vide |  et (&&) a la place de ou (||) | changer et par ou | afficher le message d'error |
| 3 | ajouter la quantiter sous forme de string | l'ajout de numbers sous forme de strings | manque de la Number() | ajout de Number() | le total s'affiche correctement |
| 4 | affichage apres l'ajout | la liste des produits ne update pas | la fonction afficher manquante dans l'event du button | ajouter la fonction afficher | mise a jour auto|
| 5 |Saisir du texte dans la barre de recherche. | les résultats changent à chaque caractère saisi. Obtenu : la recherche se mettait à jour seulement après avoir quitté le champ. | J’avais utilisé l’événement change au lieu de input. | Remplacer l’événement change par input. |Les résultats de recherche se mettent à jour pendant la saisie. |

Bilan : quelle méthode réutiliserai-je sur mon prochain brief ?
