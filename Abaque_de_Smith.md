# Abaque de Smith

L'abaque de Smith est un outil qui permet d'avoir une représentation graphique de calcul qui sert à exprimer et résoudre des problèmes avec les lignes de transmission et notamment les problèmes d'adaptation d'impédance.

En effet, l'abaque permet de voir comment évolue les coefficients de réflexion sur une grande bande de fréquence et permet donc d'adapter un circuit.

## Visualisation d'une abaque de Smith
![Abaque de Smith](https://upload.wikimedia.org/wikipedia/commons/7/74/Smith_chart3.svg "Abaque de Smith")

L'abaque de Smith fonctionne avec ce que l'on appelle une impédance réduite, permettant d'avoir une échelle constante et donc les mêmes points caractéristiques peut importe l'échelle de base.

Pour décaler les points sur une abaque il faut se placer sur le bon plan par rapport à la distance où nous sommes dans notre circuit (se déplacer sur un circuit reviens à faire tourner l'abaque, avec $\cfrac{\lambda}{8}$ un retournement de l'abaque, cf cercle des admittances)

La formule de l'impédance réduite est la suivante: $z_T = \cfrac{Z_T}{Z_0}$
Avec $Z_T$ l'impédance caractéristique (souvent 50 $\Omega$ ou 75 $\Omega$ pour une ligne coaxiale)

## Manipulation d'une abaque de Smith

L'abaque de Smith permet de placer un point ayant une impédance de la forme $z_T = R + jX$, où :

$R$ est la partie réelle dite résistive et $X$ est la partie imaginaire dite réactive ou réactance.

Une réactance positive sera qualifiée d'inductive, alors qu'une réactance négative sera qualifiée de capacitive.
Comme la partie imaginaire dépend de la fréquence, l'abaque permet de suivre l'adaptation d'une plage de fréquencel

### Résistance idéale
L'impédance d'une résistance idéale $R$ est égale à $R$ : $Z_{R}=R\,$.
C'est le seul composant à avoir une impédance purement réelle.

### Bobine idéale
L'impédance d'une bobine d'inductance $L$ est :

${\underline {Z}}_{L}=j\omega L=L\omega e^{j{\frac {\pi }{2}}}$

où ${\omega }$ est la pulsation du signal. Contrairement au cas précédent, cette impédance est purement imaginaire et dépend de la fréquence du signal.

### Condensateur idéal
L'impédance d'un condensateur idéal de capacité  $C$ est:

 ${\underline {Z}}_{C}={1 \over j\omega C}={1 \over C\omega }e^{-j{\frac {\pi }{2}}}$

# VNA

Un VNA ou analyseur de réseau (Vector Network Analyzer) est un appareil de mesure qui permet de récupérer les paramètres-S d'un circuit. Il permet notamment d'afficher ceux-ci comme une abaque de Smith permettant d'avoir une représentation graphique de l'adaptation afin de l'améliorer
## Adapter un circuit en impédance

Pour adapter un circuit, on utilise un  qui permet d'afficher les différents paramètres-S  
# PIM (Passive Inter-Modulation)

Voir Manip avec Thibaut


# Rappels

$\omega = 2{\pi}f$

## Longueur électrique: 

Somme des longueurs dans les différents milieux selon leur permittivité 
Exemple pour un élément constitué d'air ($\epsilon_r = 1$) et de teflon ($\epsilon_r = 2,1$) avec pour longueurs respectives $x,y$ :

$l_{elec} = x + \cfrac{y}{\sqrt{2,1}}$

## Effet de Peau



## Compatibilité électromagnétique (CEM) 


## Électronique
Base de l'électricité et des éléments constituant un circuit électronique

### Dipôle

Un dipôle est un composant ou un circuit ayant deux bornes ou deux pôles. Les dipôles peuvent être actifs ou passifs et sont les éléments de base des circuits électriques.

#### Types de Dipôles

1) Dipôles Passifs : Ces dipôles ne fournissent pas d'énergie au circuit:
    - Résistance (R) : Limite le courant dans un circuit.
    - Condensateur (C) : Stocke de l'énergie sous forme de champ électrique.
    - Inducteur (L) : Stocke de l'énergie sous forme de champ magnétique.

2) Dipôles Actifs : Ces dipôles peuvent fournir de l'énergie au circuit:
    - Source de Tension : Fournit une tension constante ou variable.
    - Source de Courant : Fournit un courant constant ou variable.
    
### Condensateur

### Oscillateur 

### Oscillateur local (OL)

