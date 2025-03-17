# Utilisation de NLP pour Nettoyage et Analyse de Texte Arabe Basant sur les chaînes de Markov

## Description
Ce projet permet de nettoyer et de traiter un texte en arabe en supprimant les caractères indésirables, en appliquant des corrections spécifiques (ex. gestion de la chadda), et en effectuant une analyse statistique via une matrice de transition et des probabilités de transition entre les caractères.

## Fonctionnalités
- **Nettoyage du texte** : Suppression des caractères non désirés (ponctuation, chiffres, symboles, etc.).
- **Traitement des diacritiques** : Suppression des caractères après une chadda et ajout d'un sukun aux lettres sans diacritiques.
- **Analyse statistique** : Création d'une matrice de transition représentant les enchaînements de lettres et diacritiques.
- **Calcul des probabilités de transition** : Normalisation de la matrice de transition en probabilités.
- **Exportation des résultats** : Sauvegarde de la matrice sous forme de fichier CSV pour une analyse facile.

## Exemple de sortie
Après traitement, le texte nettoyé est stocké dans `fichier_sortie.txt`, et la matrice de transition est enregistrée dans `matrice.csv` sous forme tabulaire."# Nettoyage-et-Traitement-du-Texte-Arabe-pour-le-NLP" 
