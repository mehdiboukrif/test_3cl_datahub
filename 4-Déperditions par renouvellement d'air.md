# 4-Déperditions par renouvellement d'air 

Données d'entrée :<br>Type de bâtiment<br>Surface des parois déperditives hors plancher bas<br>Surface habitable<br>Nombre de niveaux<br>Hauteur moyenne sous plafond<br>Type de ventilation<br>Année de construction ou de l'installation<br>Zone climatique

Les déperditions DR par renouvellement d'air par degré d'écart entre l'intérieur et l'extérieur (W/K) sont données par la formule suivante :

$$
D R=\text { Hvent }+ \text { Hperm }
$$

Avec :

- Hvent : déperdition thermique par renouvellement d'air due au système de ventilation par degré d'écart entre l'intérieur et l'extérieur ( $W / K$ ) :

$$
\text { Hvent }=0,34 * \text { Qvarep }{ }_{\text {conv }} * \text { Sh }
$$

- Qvarep $p_{\text {conv }}$ : débit d'air extrait conventionnel par unité de surface habitable $\left(\mathrm{m}^{3} /\left(\mathrm{h} . \mathrm{m}^{2}\right)\right)$ (voir tableau par type de ventilation ci-après)
- Sh : surface habitable $\left(m^{2}\right)$
- 0,34 : chaleur volumique de l'air $\left(\mathrm{Wh} /\left(\mathrm{m}^{3} . \mathrm{K}\right)\right)$

Hperm : déperdition thermique par renouvellement d'air due au vent par degré d'écart entre l'intérieur et l'extérieur (W/K) :

$$
\text { Hperm }=0,34 * \text { Qvinf }
$$

- Qvinf : débit d'air dû aux infiltrations liées au vent $\left(\mathrm{m}^{3} / \mathrm{h}\right)$ :

![](https://cdn.mathpix.com/cropped/2024_07_18_97732d9d6048f6ca5301g-041.jpg?height=149&width=715&top_left_y=2010&top_left_x=676)

- Hsp : hauteur moyenne sous plafond (m)

$\square$ Sh : surface habitable $\left(\mathrm{m}^{2}\right)$

- Qvasouf conv : débit volumique conventionnel à souffler $\left(\mathrm{m}^{3} /\left(\mathrm{h} . \mathrm{m}^{2}\right)\right.$ ) (voir tableau par type de ventilation ci-après)

![](https://cdn.mathpix.com/cropped/2024_07_18_97732d9d6048f6ca5301g-041.jpg?height=49&width=1390&top_left_y=2420&top_left_x=413)
ventilation ci-après)
$\square \quad$ e et f sont des coefficients de protection prenant les valeurs tabulées ci-dessous :

| Coefficient | Plusieurs façades exposées | Une seule façade exposée |
| :---: | :---: | :---: |
| e | 0,07 | 0,02 |
| f | 15 | 20 |

Une façade exposée est une façade donnant sur l'extérieur.

$\square \quad \mathrm{n}_{50}$ : Renouvellement d'air sous 50 Pascals $\left(\mathrm{h}^{-1}\right)$ :

$$
n_{50}=\frac{Q_{4 p a}}{\left(\frac{4}{50}\right)^{\frac{2}{3}} * H s p * S h}
$$

- $\mathrm{Q}_{4 \mathrm{~Pa}}$ : perméabilité sous 4 Pa de la zone $\left(\mathrm{m}^{3} / \mathrm{h}\right)$ :

$$
Q_{4 P a}=Q_{4 P a e n v}+0,45 * S m e a_{c o n v} * S h
$$

- Smea conv : somme des modules d'entrée d'air sous 20 Pa par unité de surface habitable $\left(\mathrm{m}^{3} /\left(\right.\right.$ h.m $\left.{ }^{2}\right)$ ) (voir tableau par type de ventilation ci-après)
- $\mathrm{Q}_{4 \text { Paenv }}$ : perméabilité de l'enveloppe ( $\left.\mathrm{m}^{3} / \mathrm{h}\right)$ :

$$
Q_{4 \text { Paenv }}=Q_{4 \text { Paconv } / m^{2}} * \text { Sdep }
$$

$>$ Sdep : surface des parois déperditives hors plancher bas $\left(\mathrm{m}^{2}\right)$

$>\mathrm{Q}_{4 \text { Paconv } / \mathrm{m}^{2}}$ : valeur conventionnelle de la perméabilité sous $4 \mathrm{~Pa}\left(\mathrm{~m}^{3} /\left(\mathrm{h} . \mathrm{m}^{2}\right)\right)$ :

|  | Appartement/Immeuble |  |  |  | Maison |  |  |  |  |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|  | Avant <br> 1948 | $1948-$ <br> 1974 | $1975-$ <br> 2012 | $>2012$ | Avant <br> 1948 | $1948-$ <br> 1974 | $1975-$ <br> 2005 | $2006-$ <br> 2012 | $>2012$ |
| Q $_{4 \text { Paconv/m }}{ }^{2}$ | 4,6 | 2 | 1,5 | 1 | 3,3 | 2,2 | 1,9 | 1,3 | 0,6 |

Pour les bâtiments qui ont fait l'objet d'une mesure d'étanchéité à l'air moins de deux ans avant le diagnostic, la valeur mesurée de $Q_{4 P a c o n v / m^{2}}$ peut être saisie.

Pour les bâtiments ou logements construits avant 1948 avec une isolation des murs et/ou du plafond (isolation de plus de $50 \%$ des surfaces), $\mathrm{Q}_{4 \mathrm{Paconv} / \mathrm{m}^{2}}=2 \mathrm{~m}^{3} /\left(\right.$ h. $\mathrm{m}^{2}$ )

Pour les bâtiments ou logements construits entre 1948 et 1974 avec une isolation des murs et/ou du plafond (isolation

![](https://cdn.mathpix.com/cropped/2024_07_18_97732d9d6048f6ca5301g-042.jpg?height=46&width=734&top_left_y=2013&top_left_x=254)

Pour les bâtiments ou logements construits avant 1948 et dont les menuiseries possèdent des joints, $\mathrm{Q}_{4 \text { Paconv }} / \mathrm{m}^{2}=2,5$ $\mathrm{m}^{3} /($ h.m²). On considère cette condition respectée si les menuiseries représentant plus de $50 \%$ de la surface totale possèdent des joints.

| Type de ventilation | ![](https://cdn.mathpix.com/cropped/2024_07_18_97732d9d6048f6ca5301g-043.jpg?height=89&width=190&top_left_y=326&top_left_x=1078) | ![](https://cdn.mathpix.com/cropped/2024_07_18_97732d9d6048f6ca5301g-043.jpg?height=89&width=190&top_left_y=326&top_left_x=1338) | ![](https://cdn.mathpix.com/cropped/2024_07_18_97732d9d6048f6ca5301g-043.jpg?height=89&width=178&top_left_y=326&top_left_x=1586) |
| :---: | :---: | :---: | :---: |
| Ventilation par ouverture des fenêtres | 1,2 | 1,2 | 0 |
| Ventilation par entrées d'air hautes et basses | 2,23 | 0 | 4 |
| VMC SF Auto réglable $<1982$ | 1,97 | 0 | 2 |
| VMC SF Auto réglable de 1982 à 2000 | 1,65 | 0 | 2 |
| VMC SF Auto réglable de 2001 à 2012 | 1,50 | 0 | 2 |
| VMC SF Auto réglable après 2012 | 1,32 | 0 | 2 |
| VMC SF Hygro A < 2001 | 1,50 | 0 | 2 |
| VMC SF Hygro A de 2001 à 2012 | 1,44 | 0 | 2 |
| VMC SF Hygro A après 2012 | 1,16 | 0 | 2 |
| VMC SF Gaz < 2001 | 1,59 | 0 | 2 |
| VMC SF Gaz de 2001 à 2012 | 1,53 | 0 | 2 |
| VMC SF Gaz après 2012 | 1,22 | 0 | 2 |
| VMC SF Hygro B < 2001 | 1,36 | 0 | 1,5 |
| VMC SF Hygro B de 2001 à 2012 | 1,24 | 0 | 1,5 |
| VMC SF Hygro B après 2012 | 1,09 | 0 | 1,5 |
| VMC Basse pression Auto-réglable | 1,97 | 0 | 2 |
| VMC Basse pression Hygro A | 1,30 | 0 | 2 |
| VMC Basse pression Hygro B | 1,24 | 0 | 1,5 |
| VMC DF individuelle avec échangeur $\leq 2012$ | 0,60 | 0,6 | 0 |
| VMC DF individuelle avec échangeur après 2012 | 0,26 | 0,26 | 0 |
| VMC DF collective avec échangeur $\leq 2012$ | 0,75 | 0,75 | 0 |
| VMC DF collective avec échangeur après 2012 | 0,46 | 0,46 | 0 |
| VMC DF sans échangeur $\leq 2012$ | 1,65 | 1,65 | 0 |
| VMC DF sans échangeur après 2012 | 1,32 | 1,32 | 0 |
| Ventilation naturelle par conduit | 2,23 | 0 | 4 |
| Ventilation hybride $<2001$ | 1,52 | 0 | 3 |
| Ventilation hybride de 2001 à 2012 | 1,33 | 0 | 3 |
| Ventilation hybride après 2012 | 1,17 | 0 | 3 |
| Ventilation hybride avec entrées d'air hygro < 2001 | 1,52 | 0 | 2 |
| Ventilation hybride avec entrées d'air hygro de 2001 à | 1,33 | 0 | 2 |
| Ventilation hybride avec entrées d'air hygro après 2012 | 1,17 | 0 | 2 |
| Ventilation mécanique sur conduit existant $\leq 2012$ | 2,24 | 0 | 4 |
| Ventilation mécanique sur conduit existant après 2012 | 1,97 | 0 | 4 |
| Ventilation naturelle par conduit avec entrées d'air <br> hygro | 2,23 | 0 | 3 |
| Puits climatique sans échangeur $\leq 2012$ | 0,99 | 0,99 | 0 |
| Puits climatique sans échangeur après 2012 | 0,79 | 0,79 | 0 |
| Puits climatique avec échangeur $\leq 2012$ | 0,36 | 0,36 | 0 |
| Puits climatique avec échangeur après 2012 | 0,16 | 0,16 | 0 |

## Cas des VMC par insufflation :

Les VMC par insufflation sont traitées comme des VMC simple flux autoréglables et avec les mêmes caractéristiques selon les années d'installation.

Cas des puits climatiques (intégrés au tableau ci-dessus):

Le puits climatique est considéré comme une VMC double flux faisant rentrer dans le logement de l'air à une température proche de celle du sol.

Par hypothèse la température moyenne en sortie du puits canadien est de $12^{\circ} \mathrm{C}$. La température moyenne extérieure d'Octobre à Avril est de $8^{\circ} \mathrm{C}$.

La modélisation du puits climatique est donc comparable à une celle d'une VMC double flux avec une correction sur les températures $\rightarrow$ correction $=\frac{\text { Tint-12 }}{\text { Tint-8 }}=0,6$ appliquée pour obtenir les valeurs présentes dans le tableau.