# ENSEA - Projet de 1ere année

## Déroulé du cours

L'objectif de ce cours est de présenter la méthode de conception d'un système électronique.
La conception sera réalisé depuis l'idée du produit que l'on veut développer jusqu'à sa réalisation.
L'ensemble de cette méthode sera appliqué sur exemple de drone.

### Etablissement du cahier des charges, 4 parties toujours présentes :
* Alimentation,
* Capteurs (ex : boutons utilisateurs, gyroscope, pression, micro, etc...)
* Actionneurs (ex : led, moteur)
* Unité de traitement (micro-controleur, fpga, etc...)

### Choix des composants
* Etablissement des besoins des données à collecter
* Etablissement des besoins des actionneurs 
* Recherche des composants chez les fournisseurs référencés :
  * Farnell, electronique, très rapide,
  * RS, électronique et mécanique, très rapide,
  * Mouser, beaucoup plus complet que Farnell et RS, très gros stock, un peu plus lent,
  * Gotronic, beaucoup de platines d'évaluation, de composant pour hobbyiste,
  * Conrad, comme Gotronic,
  * Miniplanes, orienté drone, avion, voiture RC, batterie LiPo, Li-Ion, etc...
* Lecture des datasheets

### Réalisation d'un diagramme d'architecture
* Par où commencer ?
* Quels sont les protocoles de communication dont on a besoin ?
* Comment choisir le micro-processeur associé ? 

### Transposition dans un logiciel de création de PCB (schematic) :
* Présentation des empreintes standard (footprint) :
* CMS/SMD vs THT
* Différences entre les technologie (espace, prix, dissipation thermiques, etc...)
* Types de condensateurs : céramique, électrolytique, tantale,
* Liste des packages : 
 * Résistances / condensateurs : 0201, 0402, 0603, 0805, etc...
 * Formats : DIP, BGA, QFN, SO, HSOP, HTSSOP, QSOP, SOIC, SOP, SSO, SSOP, TSOP, TSSOP
 * Connecteurs : Pin header/socket, JST-XH, Molex, etc...
* Association des empreintes à chaque schéma :
 * Téléchargement des empreintes (snapeda)
 * Réalisation des empreintes introuvables
 
  



