# Pourcentage et dollar

## Calculs avancés

Saisir une formule permettant de calculer la part de chaque indicateur relatif à des vols dans l'ensemble des vols.

{% hint style="info" %}
On pourra utilement ajouter une ligne sous-total nombre de vols et cambriolage pour réaliser ce calcul.
{% endhint %}

Pour chaque indicateur, calculer leurs évolutions annuelles sur la période 2006-2021. Afficher ces évolutions sous la forme d'un pourcentage avec un chiffre après la virgule.

{% hint style="info" %}
L'évolution annuelle d'une variable peut se calculer de la manière suivante : (valeur en N/valeur en N-1) - 1
{% endhint %}

Pour chaque indicateur, calculer son poids dans l'ensemble des indicateurs en utilisant le signe dollar à la place appropriée.

{% hint style="info" %}
Lorsqu’une formule est copiée/collée vers une autre cellule, elle n’est pas copiée à l’identique. En effet, les références des cellules mentionnées dans la formule initiale sont décalées automatiquement. Par exemple, si A1 a pour formule = A2+A3, alors recopier cette formule en B11 donnera =B12+B13 (décalage d’une colonne vers la droite et de 10 lignes vers le bas).

Ce décalage est souhaitable dans certains cas. Dans d’autres, il ne l’est pas et on souhaite empêcher que la ligne et/ou la colonne d’une cellule référencée dans une formule soit modifiées lorsque la formule est recopiée.

L’usage du signe dollar $ dans une référence de cellule, avant la ligne (par ex A$2) ou avant la colonne (par ex $A2) ou avant la ligne et la colonne (par $A$2) permet ainsi de figer la ligne et/ou la colonne concernée lors de la recopie. Par exemple, si A1 a pour formule =A$2+$A3, cette formule recopiée en B11 donnerait =B$2+$A13.
{% endhint %}
