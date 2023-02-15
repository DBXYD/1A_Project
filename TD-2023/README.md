# TD Conception de PCB

2 séances de 2

Objectifs pédagogiques :
* Lecture d'une datasheet
* Réalisation d'un schéma à partir de datasheets
* Ajouter les composants essentiels au bon fonctionnement des différents composants
* Associer chaque composant à la bonne empreinte
* Acquérir une technique de placement des composants sur le board
* Réaliser le routage de la carte en respectant des règles élémentaires (largeurs de pistes en fonction du courant, isolation des pistes, etc...)
* Export des gerbers

## Introduction 
* Microcontrôleur STM32L021K4T6,
* DAC MCP4801-E/SN,
* Régulateur linéaire BU33SD5WG-TR,
* 2 LED au format 0603,
* Connecteur de programmation FTSH-107-01-F-DV,
* Plusieurs composants passifs (résistances, condensateurs...) en 0603.

## Schematic

### Components

#### Microcontroleur sous KiCAD

##### Configuration du microcontroleur sous STM32CubeIDE
![cube01.png](./sources_fiack/sujet/figures/cube01.png)

##### Microcontroleur avec composants essentiels

Add a symbol

![kicad01.png](./sources_fiack/sujet/figures/kicad01.png)

Add a power port

![kicad02.png](./sources_fiack/sujet/figures/kicad02.png)

![kicad03.png](./sources_fiack/sujet/figures/kicad03.png)

![kicad04.png](./sources_fiack/sujet/figures/kicad04.png)

Add a global label

![kicad05.png](./sources_fiack/sujet/figures/kicad05.png)

Reset signal

![kicad06.png](./sources_fiack/sujet/figures/kicad06.png)

Power filter

![kicad07.png](./sources_fiack/sujet/figures/kicad07.png)

#### Power

![kicad08.png](./sources_fiack/sujet/figures/kicad08.png)

#### DAC

![kicad09.png](./sources_fiack/sujet/figures/kicad09.png)

#### Connecteurs

![kicad10.png](./sources_fiack/sujet/figures/kicad10.png)

#### Fixation

![kicad19.png](./sources_fiack/sujet/figures/kicad19.png)

### Numerotation

![kicad11.png](./sources_fiack/sujet/figures/kicad11.png)

### Electronic Rule Check

![kicad12.png](./sources_fiack/sujet/figures/kicad12.png)

![kicad13.png](./sources_fiack/sujet/figures/kicad13.png)

### Footprint assigment

![kicad14.png](./sources_fiack/sujet/figures/kicad14.png)

![kicad16.png](./sources_fiack/sujet/figures/kicad16.png)

![kicad15.png](./sources_fiack/sujet/figures/kicad15.png)

![kicad20.png](./sources_fiack/sujet/figures/kicad20.png)

## Board

![kicad17.png](./sources_fiack/sujet/figures/kicad17.png)

Rajout choix taille PCB

![kicad18.png](./sources_fiack/sujet/figures/kicad18.png)

![kicad21.png](./sources_fiack/sujet/figures/kicad21.png)

Dans quel ordre placer ses composants

![kicad22.png](./sources_fiack/sujet/figures/kicad22.png)

### 

![kicad24.png](./sources_fiack/sujet/figures/kicad24.png)

![kicad25.png](./sources_fiack/sujet/figures/kicad25.png)

![kicad26.png](./sources_fiack/sujet/figures/kicad26.png)

![kicad27.png](./sources_fiack/sujet/figures/kicad27.png)

![kicad28.png](./sources_fiack/sujet/figures/kicad28.png)

![kicad29.png](./sources_fiack/sujet/figures/kicad29.png)

![kicad30.png](./sources_fiack/sujet/figures/kicad30.png)

![kicad31.png](./sources_fiack/sujet/figures/kicad31.png)

![kicad32.png](./sources_fiack/sujet/figures/kicad32.png)


## Autres
![kicad23.png](./sources_fiack/sujet/figures/kicad23.png)

          
