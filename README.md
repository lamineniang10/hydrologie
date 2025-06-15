# Modélisation du débordement dans le bassin du fleuve Gambie (stations de Kédougou et Mako) – Juillet 2024

Ce projet simule et analyse le débordement du fleuve Gambie entre les stations hydrologiques de Kédougou et Mako, en utilisant un modèle hydrodynamique spatial basé sur PCRaster.

## Objectifs
- Modéliser l’évolution du débit et du niveau d’eau du fleuve Gambie.
- Identifier les zones potentiellement saturées ou débordées.
- Estimer la hauteur de l'eau à Mako.

## Données & hypothèses
- MNT à 100 m de résolution spatiale.
- LDD (flow direction) dérivé pour simuler l’écoulement.
- Données de crue: https://mha.gouv.sn/la-situation-hydrologique-et-alerte-de-crue-sur-les-fleuves-senegal-et-gambie-du-11-octobre-2024/
- Coordonnées des stations Kédougou et Mako: HSM-SIEREM 2016
- Certaines données, comme la **capacité du lit du fleuve** et le **débit de base par cellule**, n’étant pas disponibles, ont été **reconstituées de manière fictive mais cohérente** pour assurer le bon fonctionnement du modèle.

## Outils
Python avec les bibliothèques:
- ``PCRaster`` (modèle spatio-temporel)
- ``GDAL`` (traitement de données raster)
- ``Numpy`` (calculs numériques)
- ``Matplotlib`` (visualisation)
- ``Jupyter Notebook`` (documentation complète du projet)

## Résultat
Simulation dynamique en pas de temps du débordement et du flux entre les stations, avec visualisation cartographique.  
➡️ Tous les détails sont disponibles dans le notebook `.ipynb`.

## Contact 
Email: sidiniang20@gmailcom
