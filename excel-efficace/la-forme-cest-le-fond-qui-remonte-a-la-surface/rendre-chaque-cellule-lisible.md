# Rendre chaque cellule lisible

## Rendre chaque cellule lisible

### Types de contenus pour une cellule Excel

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><mark style="color:green;">Nombre</mark></td><td>Repérables grâce à la fonction ESTNUM</td><td></td></tr><tr><td><mark style="color:green;">Formules</mark></td><td>Repérables grâce à la fonction ESTFORMULE</td><td></td></tr><tr><td><mark style="color:green;">Textes</mark></td><td>Repérables grâce à la fonction ESTTEXTE</td><td></td></tr><tr><td><mark style="color:green;">Booléens</mark></td><td>VRAI ou FAUX</td><td></td></tr></tbody></table>

{% hint style="warning" %}
Ne **jamais** mélanger formules et nombres dans une seule et même case (risque d'erreur majeur et nuit fortement à la clarté du fichier pour les relecteurs).
{% endhint %}

Les différents types de formats pour un nombre sont accessibles avec le raccourci ALT + L + OO :

* La rubrique "personnalisée" dans le menu déroulant est très pratique, elle permet de composer son propre type de format.
* Exemple : repérer les "vrais" et les "faux" zéros. Certains cases affichent parfois le nombre "0" alors que la valeur contenue n'est en réalité pas nulle. Une manière de repérer de telles situations est d'utiliser un format personnalisé construit sur le modèle "0,0 ;-0,0 ;-s".

### Fusionner des cellules

* Fusionner en utilisant la fonction prévue par Excel (ALT + L + UU) est déconseillé car cela perturbe la circulation dans le feuillet et empêche de créer ou supprimer des lignes et colonnes directement au clavier
* Pour éviter ces difficultés il faut utiliser la fonctionnalité « centrer sur plusieurs colonnes » accessible avec le chemin ALT + L + N, puis sélectionner « centré sur plusieurs colonnes » dans le menu déroulant

{% hint style="warning" %}
Cette méthode ne s'applique qu'aux colonnes et pas aux lignes.
{% endhint %}
