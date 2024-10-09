# Abaque de Smith

L'abaque de Smith est un outil qui permet d'avoir une représentation graphique de calcul qui sert à exprimer et résoudre des problèmes avec les lignes de transmission et notamment les problèmes d'adaptation d'impédance.
En effet, l'abaque permet de voir comment évolue
## Visualisation d'une abaque de Smith
![Abaque de Smith](https://upload.wikimedia.org/wikipedia/commons/7/74/Smith_chart3.svg "Abaque de Smith")

L'abaque de Smith fonctionne avec ce que l'on appelle une impédance réduite, permettant d'avoir une échelle constante et donc les mêmes points caractéristiques peut importe l'échelle de base.

La formule de l'impédance réduite est la suivante: $z_T = \cfrac{Z_T}{Z_0}$
Avec $Z_T$ l'impédance caractéristique (souvent 50 $\Omega$ ou 75 $\Omega$)

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
## Adapter un circuit en impédance

Pour adapter un circuit, on utilise un VNA ou analyseur de réseau (Vector Network Analyzer) qui permet d'afficher les différents paramètres-S  

# PIM (Passive Inter-Modulation)

Voir Manip avec Thibaut