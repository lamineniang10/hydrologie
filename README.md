# Modélisation du débordement dans le bassin du fleuve Gambie (stations de Kédougou et Mako) – Juillet

Ce projet simule et analyse le débordement du fleuve Gambie entre les stations hydrologiques de Kédougou et Mako, en utilisant un modèle hydrodynamique spatial basé sur PCRaster.

## Objectifs
- Modéliser l’évolution du débit et du niveau d’eau dans un sous-bassin du fleuve Gambie.
- Identifier les zones potentiellement saturées ou débordées.
- Estimer le temps de propagation de l’eau entre Kédougou et Mako.

## Données & hypothèses
- MNT à 100 m de résolution spatiale.
- LDD (flow direction) dérivé pour simuler l’écoulement.
- Certaines données, comme la **capacité du lit du fleuve** et le **débit de base par cellule**, n’étant pas disponibles, ont été **reconstituées de manière fictive mais cohérente** pour assurer le bon fonctionnement du modèle.

## Outils
- PCRaster (modèle spatio-temporel)
- Python (prétraitement et visualisation)
- Jupyter Notebook (documentation complète du projet)

## Résultat
Simulation dynamique en pas de temps du débordement et du flux entre les stations, avec visualisation cartographique.  
➡️ Tous les détails sont disponibles dans le notebook `.ipynb`.
