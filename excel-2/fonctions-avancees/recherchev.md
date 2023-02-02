# RechercheV

La fonction RECHERCHEV d'Excel permet de faire exécuter au tableur une recherche dans la première colonne (ou ligne avec rechercheH) d’un tableau de valeurs et de renvoyer la valeur trouvée dans une cellule déterminée à l'avance.

Enrichir les données en ajoutant la population de chaque département dans un nouvel onglet

Ajouter dans l'onglet principal des informations sur la population du département concerné.

{% hint style="info" %}
Syntaxe : RECHERCHEV(identifiant, tableau où chercher de l’information, rang de la colonne-cible, 0). Attention à ne pas oublier les $ lors de la sélection du tableau.

Si la valeur à rechercher n‘est pas trouvée, revoie #N/A, pour améliorer l’affichage : SIERREUR(formule ; valeur à afficher si la formule génère une erreur)
{% endhint %}
