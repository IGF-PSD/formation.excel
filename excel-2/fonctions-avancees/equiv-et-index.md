# EQUIV et INDEX

## Description des fonctions

{% hint style="info" %}
La description infra a été générée par [ChatGPT](https://chat.openai.com)
{% endhint %}

Les fonctions EQUIV et INDEX d'Excel permettent de faire exécuter au tableur une recherche dans un tableau, dans le même esprit que la fonction RechercheV.

La fonction INDEX dans Excel permet de renvoyer une valeur ou une plage de cellules à partir d'une plage de cellules ou d'un tableau. Vous pouvez utiliser la fonction INDEX pour renvoyer une valeur d'une cellule spécifique dans une plage de cellules ou pour renvoyer une plage de cellules sélectionnée à partir d'une plage de cellules plus grande.

La syntaxe de la fonction INDEX est la suivante :

INDEX(plage, ligne, colonne)

* `plage` est la plage de cellules dans laquelle vous souhaitez rechercher une valeur.
* `ligne` est l'indice de la ligne de la cellule que vous souhaitez renvoyer. Si vous spécifiez 0 (zéro), INDEX renverra la valeur de la ligne en entier.
* `colonne` est l'indice de la colonne de la cellule que vous souhaitez renvoyer. Si vous spécifiez 0 (zéro), INDEX renverra la valeur de la colonne en entier.

Exemple :

Supposons que vous avez une table de données qui contient les noms et les salaires de plusieurs employés dans une feuille de calcul Excel, comme suit :

<table><thead><tr><th>Nom</th><th>Salaire</th><th data-hidden></th></tr></thead><tbody><tr><td>John</td><td>1000</td><td></td></tr><tr><td>Jane</td><td>1200</td><td></td></tr><tr><td>Mike</td><td>1500</td><td></td></tr></tbody></table>

Pour renvoyer le salaire de l'employé "Jane", vous pouvez utiliser la formule suivante :

\=INDEX(B2:B4, 2, 1)

Cette formule renverra 1200, qui est la valeur de la cellule B3.

La fonction EQUIV dans Excel est utilisée pour renvoyer l'indice de la cellule d'une plage de cellules spécifiée. Elle peut être utilisée avec la fonction INDEX pour renvoyer une valeur d'une plage de cellules en spécifiant un nom de colonne et un nom de ligne.

La syntaxe de la fonction EQUIV est la suivante :

EQUIV(nom de colonne, nom de ligne, plage de cellules)

* `nom de colonne` est le nom de la colonne de la cellule que vous souhaitez renvoyer.
* `nom de ligne` est le nom de la ligne de la cellule que vous souhaitez renvoyer.
* `plage de cellules` est la plage de cellules dans laquelle vous souhaitez rechercher une valeur.

Exemple :

Supposons que vous avez une table de données qui contient les noms et les salaires de plusieurs employés dans une feuille de calcul Excel, et que vous avez nommé les colonnes "Nom" et "Salaire"

<table><thead><tr><th>Nom</th><th>Salaire</th><th data-hidden></th></tr></thead><tbody><tr><td>John</td><td>1000</td><td></td></tr><tr><td>Jane</td><td>1200</td><td></td></tr><tr><td>Mike</td><td>1500</td><td></td></tr></tbody></table>

Pour renvoyer le salaire de l'employé "Jane" en utilisant les noms de colonne et de ligne, vous pouvez utiliser la formule suivante :

\=INDEX(B2:B4, EQUIV("Nom", "Jane", A2:A4), EQUIV("Salaire", "Salaire", A1:B1))

Cette formule utilise la fonction EQUIV pour trouver l'indice de la ligne et de la colonne "Jane" et "Salaire", respectivement, et la fonction INDEX pour renvoyer la valeur de la cellule située à l'intersection de ces deux indices dans la plage de cellules B2:B4. La formule renverra 1200, qui est la valeur de la cellule B3.

## Différences entre RECHERCHEV et EQUIV/INDEX

La fonction RECHERCHEV est utile lorsque vous souhaitez rechercher un texte spécifique dans une plage de cellules et renvoyer une valeur associée à cette valeur dans la même ligne. Cependant, la fonction RECHERCHEV a un certain nombre de limitations :

* La fonction RECHERCHEV ne peut pas être utilisée pour renvoyer une valeur d'une colonne ou d'une ligne autre que celle du texte recherché. Par exemple, si vous souhaitez renvoyer la valeur d'une cellule située deux colonnes à droite du texte recherché, vous ne pouvez pas utiliser RECHERCHEV.
* La fonction RECHERCHEV ne peut pas être utilisée pour renvoyer une plage de cellules. Vous ne pouvez renvoyer qu'une seule valeur à la fois avec RECHERCHEV.
* La fonction RECHERCHEV n'est pas très pratique lorsque vous avez beaucoup de données et que vous souhaitez effectuer des calculs sur plusieurs cellules. Par exemple, si vous souhaitez effectuer une somme sur plusieurs colonnes de données, vous devez utiliser une autre fonction, telle que SOMME.

Au contraire, la fonction INDEX est plus flexible et plus puissante que RECHERCHEV dans de nombreux cas. Voici quelques avantages de l'utilisation de INDEX et EQUIV plutôt que RECHERCHEV :

* La fonction INDEX vous permet de renvoyer une valeur d'une cellule spécifique dans une plage de cellules, même si cette cellule n'est pas située sur la même ligne que le texte recherché. Vous pouvez utiliser la fonction INDEX pour renvoyer une valeur de n'importe quelle ligne ou colonne dans une plage de cellules.
* La fonction INDEX vous permet de renvoyer une plage de cellules sélectionnée à partir d'une plage de cellules plus grande. Cela vous permet de travailler avec des données de manière plus souple et de faire des calculs sur plusieurs cellules en une seule formule.
* La fonction EQUIV vous permet de renvoyer l'indice de la cellule d'une plage de cellules spécifiée en utilisant des noms de colonne et de ligne plutôt que des numéros de ligne et de colonne. Cela peut rendre vos formules plus lisibles et plus faciles à comprendre.

En résumé, la fonction INDEX est généralement plus flexible et plus puissante que RECHERCHEV, surtout lorsque vous avez besoin de renvoyer des valeurs de cellules spécifiques ou de travailler avec des données sur plusieurs lignes ou colonnes. La fonction EQUIV peut être utilisée avec INDEX pour rendre vos formules plus lisibles et plus faciles à comprendre en utilisant des noms de colonne et de ligne plutôt que des numéros de ligne et de colonne. Cependant, il est important de noter que RECHERCHEV peut être plus rapide à exécuter que INDEX et EQUIV dans certains cas, car il effectue une recherche à partir du début de la plage de cellules jusqu'à ce qu'il trouve une correspondance. Si vous avez des données volumineuses et que vous devez effectuer des recherches fréquentes, RECHERCHEV peut être une meilleure option.

Objectif :

* Indiquer dans la base initiale la population par département en utilisant cette fois les fonctions EQUIV et INDEX.
