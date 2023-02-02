# Saisie de données et fomules

## Amélioration de la lisibilité

Le principal axe d'amélioration de la lisibilité pour ce fichier Excel est l'ajout d'un séparateur de miliers. Ajouter un séparateur de milliers, sans modifier un autre format (i.e sans centrer les données).

{% hint style="info" %}
Sélectionner la plage de cellules, clic droit, format de cellule, onglet nombren utiliser le séparateur de milliers.
{% endhint %}

Pour améliorer la lisibilité, il est également possible dans certains cas de supprimer ou masquer certaines lignes. Masquer, puis supprimer l'indicateur du nombre de vols et tentatives de vols de vélo. Annuler ensuite cette suppression.

{% hint style="info" %}
Clic gauche sur le numéro de ligne, clic droit : masquer/suppression. Pour afficher une ligne masquée, sélectionner les lignes adjacentes et cliquer sur afficher. Pour annuler une modification : CTRL + Z.
{% endhint %}

## Ajouter des informations

Le principal intérêt d'un fichier Excel est de pouvoir le modifier afin d'enrichir l'information disponible au sein de celui-ci. Créer une nouvelle colonne Total 2006-2021 pour obtenir le cumul des indicateurs sur cette période.

{% hint style="info" %}
Excel permet de calculer la valeur d'une cellule en fonction d'autres cellules. Pour cela, il est nécessaire de commencer la formule par le signe = puis de préciser les références des cellules à utiliser. Par exemple, pour que la cellule A1 soit égale à la somme de A2 et B3, il suffit de saisir en A1 : =A2+B3.

Pour réaliser une somme de plusieurs cellules, il est possible d'utiliser la fonction somme. Par exemple =somme(A2:A5) est égal à =A2+A3+A4+A5.
{% endhint %}
