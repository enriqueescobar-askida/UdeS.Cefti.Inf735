# Inf735 TP1 - 10% de la Note Finale

Session.- AUT17

Professeur.- Robert J. Laurin

Remise.- Michel.Hebert3@USherbrooke.ca

## I.- L'enfant au tambour!

### A.- Modèle logique dimmensionnel

#### 1.- Dimensions

#### 2.- Faits

## II.- Maman Les petits bateaux Inc.

### A.- Modèle Merise

![IMG_Inf735-Tp01_Ex2_merise.png](Inf735-Tp01_Ex2_merise.png "Inf735-Tp01_Ex2_merise.png")

### B.- Modèle logique dimmensionnel

#### 1.- Dimensions

##### a.- Dimension Bateau

NoEnregistrement | NomBapteme | NoEmployeCapitaine
---------|----------|----------

##### b.- Dimension Voyage

NoVoyage | NoPortDepart | DateDepart | NoPortArrive | DateArrive | NoClient | NoConnaissement | PoidsConnaissement
---------|----------|----------|----------|----------|----------|----------|----------

#### 2.- Faits

##### a.- Fait Différents voyages selon différents critères

ClefDimVoyage | ClefDimDepart | ClefDimArrive | ClefDimClient | ClefDimConteneur | ClefDimBateau
---------|---------|----------|----------|----------|----------

##### b.- Fait Localisation (port/ ville) de conteneurs à différentes dates

ClefDimConteneur | ClefDimArriveDepart
---------|---------
