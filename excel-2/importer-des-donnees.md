# Importer des données

## Résoudre les problèmes d'encodage d'un fichier

À l'ouverture d'un fichier Excel présentant un problème d'encodage, les accents sont transformés en caractères spéciaux.

Pour tenter de résoudre un problème d'encodage, la première manipulation à réaliser est d'ouvrir le fichier en l'encodant en [UTF-8](https://fr.wikipedia.org/wiki/UTF-8)

1. Ouvrez Microsoft Excel et créez un nouveau classeur.
2. Cliquez sur l'onglet "Données" dans la barre de menu en haut de la fenêtre, puis sélectionnez "A partir du texte" dans le menu déroulant.
3. Dans la fenêtre qui s'ouvre, naviguez jusqu'au fichier CSV que vous souhaitez ouvrir et sélectionnez-le. Cliquez sur "Ouvrir".
4. Dans la fenêtre qui s'ouvre, sélectionnez l'option "Délimité" et dans la liste déroulante "Origine du fichier", sélectionnez "65001 : Unicode UTF8". Cliquez sur "Suivant".
5. Sur l'écran suivant, sélectionnez "Point-virgule" puis cliquez sur "Terminer". Le fichier CSV devrait maintenant être ouvert dans Excel et être correctement encodé en UTF-8.
