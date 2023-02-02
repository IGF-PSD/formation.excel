# Préparer et représenter des données

## Nettoyer une base de données

Suggestions de vérifications avant d'utiiliser une base de données :

* sélectionner une plage de données chiffrées permet d'obtenir directement leur moyenne, nombre et somme et bas à droite de la feuille de calcul ;
* s'assurer qu'il n'y a pas de "trous" dasn la base de données en se déplaçant avec les touches CTRL + flèches.

Quelques fonctions utiles pour nettoyer une base :

* Les fonctions texte :

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><mark style="color:green;">Gauche/Droite</mark></td><td>Permet d'extraire un nombre donné de caractères d'une cellule contenant du texte.</td><td></td></tr><tr><td><mark style="color:green;">Opérateur &#x26;</mark></td><td>Permet de concaténer le contenu de cellules.</td><td></td></tr><tr><td><mark style="color:green;">Guillemets</mark></td><td>Permet d'inclure des séquences de texte "en dur".</td><td></td></tr></tbody></table>

* Les fonctions date :
  * la fonction ANNEE permet de créer une date à partir d'une année, un mois et un jour ;
  * trouver le nombre de jours entre deux dates se fait en soustrayant les deux cellules.
* La fonction "SI", le coureau suisse d'Excel.

## Filtrer, trier, calculer

* Pour importer des données, utiliser la fonction "convertir" (chemin : ALT + É + O).
* Organiser une base de données :
  * Trier :
    * Chemin : ALT + É + T ;
    * utile pour transformer de petites quantités de données rapidement.
  * Filtrer :
    * ALT+ É + T ;
    * utile pour opérer des transformations complexes sur des tableaux de grande taille, en particulier pour afficher seulement certaines sections ;
    * en revanche il est vivement déconseillé de faire des calculs directement sur un tableau filtré car la prise en compte des lignes masquées est imprévisible, mieux vaut le coller en valeur ailleurs avant.
* Réaliser des calculs conditionnels :
  * fonctions SOMME.SI, MOYENNE.SI pour des calculs avec un seul critère ;
  * fonctions SOMME.SI.ENS, MOYENNE.SI.ENS pour des calculs à plusieurs critères.
