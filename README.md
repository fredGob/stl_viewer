# Exhibit HTML — visualiseur 3D

Clone léger de l'application GNOME **Exhibit**, sous forme d'un fichier HTML
unique. Aucune installation, aucun serveur, aucune connexion réseau.

## Utilisation

1. Ouvrir `exhibit.html` dans un navigateur (double-clic, ou glisser-déposer
   le fichier dans une fenêtre du navigateur).
2. Charger un modèle : bouton **Ouvrir**, ou glisser-déposer le fichier
   directement dans la fenêtre.

Formats supportés : STL, OBJ, VTK legacy (`.vtk`), VTU (`.vtu`).

Le dossier `testdata/` contient des fichiers d'exemple dans ces formats, si
présent.

## Fonctionnalités

- Rotation / zoom / panoramique à la souris ou au tactile
- Thème clair / sombre
- Grille, arêtes, matériau, fond, éclairage réglables
- Colormap sur les champs du maillage (viridis, cool-warm), légende
- Déformée (warp) selon un champ vecteur
- Coupe par plan (X/Y/Z)
- Vues axiales, repère d'orientation
- Export de la vue en PNG

## Navigateur recommandé

Firefox est le plus complet (utilise un Web Worker pour parser les gros
fichiers sans bloquer l'interface). Chrome fonctionne aussi mais peut basculer
sur un traitement synchrone selon le fichier ouvert.

Aucun compte, aucune donnée envoyée où que ce soit : tout se passe en local
dans l'onglet du navigateur.
