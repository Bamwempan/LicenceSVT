# Optique

## Généralité optique géométrique

On distingue deux grande différence en optique, optique ondulatoire et géométrique.  
**Optique ondulatoire**  
- Phénomène des ondes  
- Diffraction et interférence  
**Optique géométrique**  
- Domaine du visible -&gt; Onde = Rayon lumineux, représenté par une droite  
3 lois fondamentales :  
- Propagation rectiline de la lumière dans un milieu homogène  
- Indépendance des rayons lumineux, constituant de base de la lumière, c'est le photon, il n'a pas de masse. Les rayons ne se voient pas et n'interagisse pas.

Vitesse de la lumière dans le vide : Célérité avec comme valeur $$C=3\times 10^{-8}m/s$$  
Dans un matériau d'indice n : $$V=\frac{C}{n}$$ avec C vitesse de la lumière en m/s et V vitesse de la lumière dans le milieu.

### Définition

* La lumière est fournie par une source lumineuse \(Soleil, Lampe, Laser, LED\)
* Un objet éclairé peut :
  * Stopper la lumière, l'objet est opaque \(Eclipse\)
  * Diffuser la lumière \(Brouillard\)
  * Absorber la lumière \(Filtre\)
  * Émettre de la lumière \(Luminescence, phosphorescence\)
* La lumière traverse le vide sans aucune modification
* Lorsque la source de lumière est infini, les rayons lumineux qui arrivent vers l'observateur sont parallèles
* Lorsque la source de lumière est à une distance fini et non collimée, les rayons vont diverger

### Principe fondamentaux de l'optique géométrique

{% hint style="warning" %}
* La propagation rectiligne de la lumière dans un milieu homogène \(-&gt; les propriétés de la lumière sont toutes identiques dans ce milieu\). Un milieu **homogène** est un milieu d**’indice de réfraction n constant**  Interface de séparation entre les deux milieux = dioptre plan n air = 1
{% endhint %}

3 principes :

* La propagation rectiligne de la lumière dans un milieu homogène
* L’indépendance des rayons lumineux \(On ne considère aucune interférence entre les rayons\)
* Le retour inverse de la lumière \(Le trajet lumineux de A vers B est identique au trajet de B vers A\)

### Réflexion et réfraction

![](../.gitbook/assets/rayon_optique.jpg)

**Rayon réfracté :** rayon qui subit un changement de direction en traversant l’interface \(= surface de séparation\) entre deux milieux transparents d’indices de réfraction $$n_1$$ et $$n_2$$ différents

## Lois de Descartes et dispersion

### Lois de Descartes

{% hint style="warning" %}
Quand la **lumière change de milieu, elle change de direction.**   
Phénomène régis par les lois de Descartes
{% endhint %}

#### 3 Lois

* Les rayons incident, réfléchis et réfractés sont dans 1 seul plan, le plan d'incident, qui est défini par deux droites
* L’angle de réflexion est égal et opposé à l’angle d’incidence
* Pour deux milieux transparents donnés, d’indices de réfraction $$n_1$$ et $$n_2$$ , séparés par une interface de type dioptre plan, le rapport du sinus de l’angle d’incidence $$i_1$$ au sinus de l’angle de réfraction $$i_2$$est constant

#### Deuxième loi de Descartes \(relative à la réflexion\)

![](../.gitbook/assets/loi_descartes_2.jpg)

Mais on ne tient pas compte du signe des angles donc on écrira : i = i  
Les angles se définissent toujours par rapport à la **normale N \(**Perpendiculaire à la surface de séparation de l'interface\)

#### Troisième loi de Descartes \(relative à la réfraction\)

{% hint style="warning" %}
Pour deux milieux transparents donnés, d’indices de réfraction $$n_1$$ et $$n_2$$ , séparés par une interface de type dioptre plan, le rapport du sinus de l’angle d’incidence $$i_1$$ au sinus de l’angle de réfraction $$i_2$$ est constant

$$n_1\times \sin1=n_2\times \sin2$$

**Les angles se définissent entre les rayons et la normale N et pas entre les rayons et la surface de séparation**
{% endhint %}

![](../.gitbook/assets/loi_descartes_3.jpg)

* Le rayon qui arrive perpendiculaire à l’interface ressort sans être dévié, pour $$i_1 = 0$$ et  $$i_2 = 0$$
* Pour $$i_1=90$$, incidence rasante, $$i_2$$est appelé **angle limite de réfraction**
* Angle limite $$i_l=\arcsin(\frac{n_-}{n_+})$$

![](../.gitbook/assets/loi_descartes_4.jpg)

{% hint style="warning" %}
Il y à **réflexion** que dans le milieu d'**incidence le plus grand**

L'angle est **toujours plus petit** dans le milieu d'**indice le plus grand**

L'**angle limite** est **toujours** dans le milieu d'**indice le plus grand**
{% endhint %}

### **Prisme**

**Définition**

{% hint style="info" %}
Milieu homogène et transparent d'indice n qui est limité par 2 dioptres plans qui sont non parallèle + une base \(triangle\) avec un angle A \(angle au sommet, arrête du prisme\)  
Objectif :  étaler les couleurs et dévier la lumière
{% endhint %}

![](../.gitbook/assets/prisme.jpg)

Dans le prisme l'angle **A = r + r'**

Si on prolonge le rayon incident vers l’avant et le rayon émergent vers l’arrière par rapport au sens de propagation de la lumière, les deux rayons se coupent au point K et définissent l’angle de déviation D.  
**D est l’angle de déviation du rayon incident après sa traversée du prisme**

![](../.gitbook/assets/angle_deviation.jpg)

$$
D=i+i'-A
$$

## Système optique : généralité

### Stigmatisme et conditions de GAUSS

{% hint style="info" %}
Un système optique est dit **stigmatique** pour deux points si l'ensemble des rayons lumineux issus d'un des points et traversant le système forment d'autres rayons lumineux dont les supports passent par le second point.

On parle de stigmatisme rigoureux quand tous les rayons issus d'un point objet A passent par un unique point A' après avoir traversé un système optique \(S.O\)
{% endhint %}

**Remarque :** Le seul système optique rigoureusement stigmate est le miroir plan.Mais le stigmatisme rigoureux n’est pas nécessaire pour la formation d’images.

![](../.gitbook/assets/stigmatisme_approche.png)

**Condition de GAUSS**  
- Les objets doivent être de faibles étendues \(petit\) et situé au voisinage de l'axe optique  
- Les faisceaux doivent traversés le système optique au voisinage du centre otpique  
- Les rayons sont faiblement inclinés par rapport à l'axe optique, donc les angles entres les rayons et l'axe optique sont petits =&gt; On peut donc utiliser les approximation de GAUSS vu ci dessus.

### Axe optique

{% hint style="warning" %}
Par convention l'axe optique est **orienté positivement** dans le **sens** de **propagation de la lumière.** Cet axe optique est **toujours** centré au **milieu du système optique**.   
Perpendiculairement à l'axe optique le **sens positif** est **toujours orienté vers le haut**.
{% endhint %}

### Points conjugués

Un système optique donne d'un point objet A un point image A'. On dit que A et A' sont conjugués pour le système optique, **1A -&gt; 1A'.**  
Image A' est conjugué de l'objet A pour le système optique.

![](../.gitbook/assets/points_conjugues.png)

{% hint style="success" %}
Relation de conjugaison : Soit un objet étendu AB et son image A'B' au travers d'un système optique tels que A-&gt;A' et B-&gt;B'. **L'objet étendu AB** et **son image A'B'** sont **toujours** représenté **perpendiculairement à l'axe optique** et **A et A' sont toujours positionné sur l'axe.**
{% endhint %}

### **Grandissement transversale**

Le grandissement noté $$\gamma$$est la grandeur algébrique et sans dimension qui relie la taille et le sens d'un objet AB et de son image A'B' soit

$$
\gamma = \frac{\overline{A'B'}}{\overline{AB}}
$$

### Faisceaux lumineux

![](../.gitbook/assets/faisceaux_lumineux.png)

### Objet vs Image

{% hint style="warning" %}
* L'objet se trouve au croisement des rayons incident sur le système optique
* L'image se trouve toujours au croisement des rayons émergent du système optique
{% endhint %}

![](../.gitbook/assets/objet_vs_image_incident_emergent.png)

#### Espace objet ou image, réelle ou virtuelle \(nature objet image\)

![](../.gitbook/assets/espace_objet_vs_espace_image_relle_virtuelle.png)

Une **image réelle** peut **toujours** être **projeté sur un écran** \(vidéoProj\)  
Une **image virtuelle** ne peut pas être projeté sur un écran, **il faut toujours la regarder au travers du système optique** \(loupe, aquarium\)

### Foyer d'un système optique

Le système optique à deux foyer, le foyer image et le foyer objet

#### Foyer image

Des rayons provenant de l'infini devant le système optique arrivant parallèlement à l'axe optique vont converger après avoir traversé le système optique en un point sur **l'axe optique** appelée foyer image F'

![](../.gitbook/assets/640px-construction_foyer_image.png)

#### Foyer objet

Des rayons issus du points foyer objet F sur l'axe optique ressortiront parallèlement entre eux et par rapport à l'axe optique après traversé du système optique pour aller à l'infini \(image à l'infini\)

![](../.gitbook/assets/640px-construction_foyer_objet.png)

**Remarque :** Le dioptre plan n'a pas de foyer, des rayons parallèle entre eux qui arrivent sur le système optique émergent du dioptre plan en allant à l'infini, **le dioptre plan est afocale.**

## **Dioptre plan**

**Définition**

{% hint style="info" %}
Le dioptre plan \(D.P\) est une interface plane qui sépare 2 milieux transparents d'indice optique n et n'
{% endhint %}

Trajet optique : Objet A dans n qui donne A' dans n'

![](../.gitbook/assets/dioptre_plan_schema.png)

{% hint style="warning" %}
Nature objet image, toujours opposé dans un dioptre plan et l'axe optique. L'image fait la même taille que objet
{% endhint %}

### Relation conjugaison du dioptre plan :

![](../.gitbook/assets/relation_conjugaison_dioptre_plan.png)

Il y a donc **l'image et l'objet du même coté du dioptre plan** donc **nature de l'image** et de l**'objet** sont **toujours opposé**; si l'un est réel l'autre est virtuel. Dans le dioptre plan uniquement

#### Grandissement du dioptre plan :

Dans un dioptre plan, uniquement !

$$
\gamma = \frac{\overline{A'B'}}{\overline{AB}}=1
$$

## Dioptre sphérique

#### Définition

{% hint style="info" %}
Un dioptre sphérique est une interface sphérique qui sépare 2 milieux transparent d'indice différent n et n'
{% endhint %}

#### Généralité

{% hint style="warning" %}
Des rayons parallèles arrivant sur un système optique sont considérés comme issus d’un point objet situé à l’infini.

Des rayons parallèles sortant d’un système optique sont considérés comme donnant un point image situé à l’infini.

En particulier, tous les rayons parallèles à l’axe optique peuvent être considérés comme provenant d’un point objet situé à l’infini sur l’axe optique.
{% endhint %}

Les points important dans le dioptre sphérique sont le centre C, son sommet S. La valeur absolue de SC est appelée le rayon de courbure du dioptre.

![](../.gitbook/assets/dioptre_convexe_concave.png)

{% hint style="warning" %}
* La valeur absolue SC est appelée rayon de **courbure R du dioptre** : **ce nombre est positif.** 
* Toutes les distances seront données en mesures algébriques avec l’origine au **sommet S**. 
* Les termes **« concave » et « convexe »** sont utilisés seulement par rapport au signe de **SC.** 
* On a vu que le DS n’est pas rigoureusement stigmatique. En pratique, on se place dans les conditions de Gauss pour avoir un stigmatisme approché.
{% endhint %}

#### Représentation schématique

![](../.gitbook/assets/representation_graphique_ds.png)

Les rayons qui arrivent sur l’interface en passant par le centre de la sphère ne seront pas déviés par le DS =&gt; **Tout rayon passant par le centre optique C est non dévié !**

### **Relation de conjugaison du dioptre sphérique**

Pour un objet AB associé à un milieu incident d’indice $$n_1$$et donnant par un DS de sommet S et de centre C une image A′B′ associée à un milieu émergent d’indice $$n_2$$ on écrit :

![](../.gitbook/assets/relation_conjugaison_dioptre_spherique.png)

{% hint style="warning" %}
* à bien associer la position de l’image SA′ avec $$n_2$$ 
* à bien associer la position de l’objet SA avec $$n_1$$
* à l’ordre des indices de réfraction entre les deux membres de l’égalité suivant l’égalité choisie
* Toute reltion pour le D.S seront exprimé par rapport à son sommet S
{% endhint %}

#### Distances focales objet et image du DS – DS convergence ou divergent

![](../.gitbook/assets/distance_focale_image_objet.png)

#### Relations remarquables du DS

La position respective des 4 points : **S, C, F et F′** n’est pas quelconque.

![](../.gitbook/assets/relation_remarquable_dioptre_spherique.png)

{% hint style="warning" %}
Les foyers objet et image sont toujours symétriques par rapport au milieu du segment SC Cette propriété est à utiliser pour la cohérence du tracé des images.
{% endhint %}

#### Grandissement du dioptre sphérique

Pour le dioptre sphérique, le grandissement se calcule comme le rapport de la position de l’image à celle de l’objet, multiplié par le rapport des indices. Attention à l’ordre

![](../.gitbook/assets/relation_grandissement_ds.png)

### Construction de l’image d’un objet AB perpendiculaire à l’axe optique et grandissement

#### Dioptre sphérique convergent

![](../.gitbook/assets/schema_exemple_convergent.png)

#### Dioptre sphérique divergent

![](../.gitbook/assets/schema_exemple_divergent.png)

## Lentille mince

{% hint style="info" %}
Une lentille mince est un système optique \(dioptrique\) centrée constitué d'un milieu transparent homogène et isotrope d'indice n et délimité par deux dioptre dont au moins 1 est sphérique.
{% endhint %}

#### Schéma principe

![](../.gitbook/assets/schema_principe.png)

#### Point remarquable des lentilles

* Centre O sur l'axe optique
* Foyer objet F
* Foyer objet F'

$$\overline{OF'}=-\overline{OF}$$, les foyers F et F' sont symétrique par rapport au centre O

#### Nature d'une lentille

{% hint style="warning" %}
$$\overline{OF'}>0$$alors présence d'une lentille convergente

$$\overline{OF'}<0$$alors présence d'une lentille divergente
{% endhint %}

#### Relation de conjugaison d'une lentille

$$\frac{1}{\overline{OA'}}-\frac{1}{\overline{OA}}=\frac{1}{\overline{OF'}}$$

#### Vergence d'une lentille

$$V=\frac{1}{\overline{OF'}}$$Si V&gt;0 alors la lentille est convergente. Si V&lt;0 alors lentille divergent.  
Unité de base en **mètre** 

#### Grandissement lentille

$$\gamma = \frac{\overline{A'B'}}{AB} = \frac{OA'}{OA}$$

{% hint style="warning" %}
$$\gamma$$&gt;1 image est plus grande que l'objet  
$$\gamma$$&lt; 1 image est plus petite que l'objet  
$$\gamma$$ &gt; image droite par rapport à l'objet  
$$\gamma$$ &lt; image renverser par rapport à l'objet
{% endhint %}

#### Lentille accolées

La lentille équivalente à un ensemble de lentilles minces accolées de même centre optique O est la somme des vergences individuelles.

$$Veq=\sum V_i$$et $$\frac{1}{\overline{OF'_{eq}}} = \sum \frac{1}{\overline{OF'_i}}$$unité en **mètre**

#### **Tracé de rayon**

-Le rayon qui passe par le centre O du système optique n'est pas dévier  
-Le rayon incident parallèle à l'axe optique qui passe par B, il passe par le foyer image F' après traversé de la lentille  
-Le rayon passant par B et le foyer objet F, il sort de la lentille parallèle à l'axe optique est vers l'infini

## Loupe

### Grandeur caractéristique

Puissance P en δ dioptrie $$m^{-1}$$

![](../.gitbook/assets/puissance_loupe.png)

Le grossissement G sans unité

![](../.gitbook/assets/grossissement_loupe.png)

![](../.gitbook/assets/grandeurs.png)

### Définition

{% hint style="info" %}
La loupe est une **lentille convergente** avec en distance focale entre 2 et 20 cm
{% endhint %}

#### Propriété de la loupe

L'objet AB doit être situé entre le centre optique O de la lentille et le foyer objet F =&gt; Forme une image virtuelle

![](../.gitbook/assets/schema_associe_loupe.png)

### Latitude de mise au point

{% hint style="info" %}
La latitude de mise au point \(ou profondeur de champ\) est la distance $$\overline{A_R A_P}$$ entre les positions extrêmes des objets qui donnent des images observables nettes par l’oeil, donc des images situées entre R et P de l’œil.
{% endhint %}

![](../.gitbook/assets/lattitude_def.png)

$$\frac{1}{\overline{OR}} - \frac{1}{\overline{OA_R}} = \frac{1}{\overline{OF'}}$$=&gt; $$l=\overline{A_R A_P}$$

Latitude de mise au point pour l'oeil normal  
P = 25 cm   
R = infini  
Sommet de l'oeil = $$\Omega$$  
$$\overline{\Omega P} = -25 cm$$  
$$\overline{\Omega R} = - \infty$$

### Puissance et grossissement d'une loupe

{% hint style="info" %}
La puissance de la loupe dépend :   
- Sa distance focale  
- La position de l'objet AB  
- La position de l'oeil $$\Omega$$par rapport à la loupe
{% endhint %}

Deux cas particulier : Objet au foyer objet F \(A'B' est à l'infini\) et oeil en F'

![](../.gitbook/assets/objet_ab_f.png)

Oeil en F'

![](../.gitbook/assets/particulier_oeil_f_image.png)

#### Puissance intrinsèque de la loupe

{% hint style="info" %}
Pour les deux cas particulier, objet en F et Oeil en F', la puissance de la loupe ne dépend que de la distance focale
{% endhint %}

$$P_i = \frac{1}{OF'}$$

Pour une loupe de focale entre 2 cm et 20 cm =&gt; 5δ &lt; $$P_i$$&lt; 50δ

### Grossissement

$$G=\frac{\alpha '}{\alpha}$$ avec $$\alpha$$angle sous lequel l'objet est vu à l'oeil nu =&gt; Objet est au proximum de l'oeil.

![](../.gitbook/assets/puissance_condition_goss.png)

#### Grossissement commercial

Si l’observation se fait dans un des 2 cas particuliers, objet en F de la loupe ou œil au foyer image F′ de la loupe, on utilise la puissance intrinsèque : $$P_i= \frac{1}{OF'}$$

Le grossissement devient alors $$G=\frac{d}{OF'}$$  
Si de plus l’œil est normal \(emmétrope\) alors la distance minimale de vision distincte est d = 25 cm = 0,25 m   
On définit alors le grossissement commercial G C comme la puissance intrinsèque divisée par 4, avec P \) en d et G + sans unité.

![](../.gitbook/assets/grossissement_commercial.png)

### Pouvoir séparateur du système \(Oeil + Loupe\)

![](../.gitbook/assets/pouvoir_separataeur.png)

## Généralité sur l’œil

L'oeil est un globe d'environ 25mm

### Principe de fonctionnement

- Les rayons incidents sont réfractés par la cornée, membrane transparente, avec une forte courbure, puis traversent sans être déviés cavité sphérique remplie d’un liquide \(n ≈ n eau \), l’humeur aqueuse.   
- On trouve ensuite une une ouverture contrôlant le flux de lumière entrant \(iris/pupille\).  
- Une 2 ème déviation se produit à la traversée du cristallin, lentille de distance focale variable, d’indice n ≈ 1,42, qui permet à l’œil d’accommoder.  
- La lumière se propage dans un autre liquide d’indice n ≈ 1,33 \(corps vitré/humeur vitrée\)  
- La lumière finit sa course sur la rétine qui tapisse le fond de l’œil

### Définition et modélisation

{% hint style="info" %}
**Accommodation :** Capacité que possède le cristallin à modifier sa convergence par une variation de courbure

**Rétine :** membrane formée de cellules nerveuses \(cônes et bâtonnets\) sensibles à la lumière, qui se comporte comme un écran relié au cerveau sur lequel se forment les images

**Punctum remotum R :** Point de l’axe optique le plus éloigné que l’œil voit nettement sur sa rétine sans accommoder \(œil au repos\). Distance \(R − œil\) = distance maximale de vision distincte

**Punctum proximum P :** Point de l’axe optique le plus proche que l’œil voit nettement sur sa rétine en accommodant au maximum \(grâce au cristallin qui fournit une vergence supplémentaire\). Distance \(P − œil\) = distance minimale de vision distincte
{% endhint %}

Pour un œil sans défaut de vision, on parle d’un œil normal ou emmétrope et on a :   
- le punctum remotum R situé à l'infini devant l’oeil  
- le punctum proximum P est situé 25 cm devant l’oeil

{% hint style="warning" %}
L'oeil humain réduit équivaut à un dioptre sphérique
{% endhint %}

![](../.gitbook/assets/schema_oeil.png)

### Construction de l’image d’un objet AB

{% hint style="warning" %}
Pour qu’un objet AB soit vu nettement par l’œil, il faut :   
**Attention : l’image sur la rétine est toujours renversée.**

* qu’il se trouve entre R et P 
* que son image A'B′ se forme sur la rétine E
{% endhint %}

![](../.gitbook/assets/trace_optique_oeil.png)

### Principe de l’accommodation

**Sans accommodation \(œil au repos\)**  
⇒ l’œil a une vision nette sur sa rétine du punctum remotum R   
⇒ le cristallin est au repos : la convergence est définie  
Au repos, le cristallin est aplati pour permettre la vision éloignée : F′ = E  
**Lorsque le cristallin est sollicité il y a a accommodation**  
⇒ la convergence augmente et la distance focale diminue   
⇒ permet la vision nette d’objets plus proches   
Au maximum d’accommodation, l’œil a une vision nette sur sa rétine du punctum proximum P  
Le cristallin se bombe pour permettre la vision de près donc F′ avant E

### Amplitude dioptrique d’accommodation

#### Les extrêmes pour l’oeil

![](../.gitbook/assets/schema_extrem_oeil.png)

{% hint style="warning" %}
C’est en modifiant son rayon de courbure que l’œil peut voir net sur sa rétine les images des objets placés entre les points R et P
{% endhint %}

#### Amplitude dioptrique d’accommodation de l’oeil

L’amplitude dioptrique d’accommodation A est donnée en fonction des distances maximale et minimale de vision distincte par la formule

![](../.gitbook/assets/amplitude_dioptirque.png)

* S est le sommet de la cornée = sommet de l’œil réduit
* Les distances s’expriment en m -&gt; A est en dioptries.

Pour un œil normal \(emmétrope\) on a :

![](../.gitbook/assets/formule_amplitude_dioptrique.png)

{% hint style="warning" %}
L’amplitude dioptrique d’accommodation d’un œil normal est une constante qui vaut **A = 4δ**
{% endhint %}

### Pouvoir séparateur et limite de résolution

#### **Pouvoir séparateur de l'oeil**

{% hint style="info" %}
On appelle pouvoir séparateur l’angle limite ε sous lequel deux points lumineux peuvent être vus séparément par l’œil.
{% endhint %}

Le pouvoir séparateur de l’œil ε est donc la valeur minimale $$α_{min}$$ de l’angle α, en radians, D défini par $$tan \alpha = \frac{D}{d}$$. Ici D est la distance entre 2 points extrêmes d’un objet et d est la distance d’observation de cet objet. Dans ces conditions α min correspond à D min , la distance minimale entre 2 points de l’objet que l’œil est capable de discerner : $$ε = α_{min} = arctan (\frac{D_{min}}{d})$$

**Le pouvoir séparateur définit la limite de résolution de l’œil.**  
Si les images A′ et B′ excitent des cellules différentes de la rétine \(cônes ou bâtonnets\), alors les deux extrémités de l’objet A et B sont distingués par l’œil.  
**Ce qui compte c’est l’angle α sous lequel est vu l’objet AB**

![](../.gitbook/assets/pouvoir_separateur_oeil.png)

#### Limite de résolution de l’œil

Connaissant le pouvoir séparateur de l’œil, on cherche la taille minimale d’un objet AB visible par l’œil, donc placé au punctum proximum P et vu sous l’angle limite ε ?   
****Pour un œil normal, la distance minimale de vision distincte vaut 0,25 m

![](../.gitbook/assets/limite_resolution_oeil.png)

## Association de système optique

#### Principe

On considère deux systèmes optiques S1 et S2. On cherche l’image finale \(ou définitive\) A'B' d’un objet initial AB , donnée par le système global \(S1 , S2 \).

1 - On considère d’abord l’image intermédiaire A1 B1 de l’objet initial AB donnée par S1  
2 - Ensuite, on oublie le système S1 , et on considère A1 B1 comme un objet intermédiaire pour le système S2  
3 - Enfin, on détermine l’image finale A'B' de l’objet intermédiaire A1B1 donnée par S2

![](../.gitbook/assets/association_lentille.png)

#### Notion de grandissement total

On peut travailler sur chacun des systèmes indépendamment. On applique les formules de conjugaison à chacun des systèmes l’un après l’autre

* on déduit les positions de l’image intermédiaire puis de l’image finale
* on déduit le grandissement de chaque système

Pour un système global comprenant N systèmes optiques, le grandissement s’écrit comme le produit des grandissements de chaque système optique

![](../.gitbook/assets/grandissement_totale.png)

Pour un système global comprenant seulement deux systèmes optiques S1 et S2 , le grandissement du système \(S1 , S2 \) s’écrit

![](../.gitbook/assets/grandissement_totale_deux_systeme.png)

#### Exemple d'utilisation

* Principe d’une lentille liquide : association d’un dioptre sphérique et de deux dioptres plans
*  Microscope, lunette astronomique, lunette de Galilée, association d’au moins deux lentilles minces, convergentes ou divergentes
* Correction des défauts de l’œil par lentille correctrice, association d’une lentille mince \(lunettes ou lentilles correctrices\) et d’un dioptre sphérique \(modèle de l’œil\)

### Application au microscope

#### Principe 

Permet l’observation d’objets très petits  
Dans un microscope, on examine avec un oculaire l’image agrandie d’un objet fournie par un objectif  
Oculaire : correspond à l’endroit où on place l'œil donc on veut créer une image finale à l'infini par le microscope, qui sera considérée comme un objet à l’infini pour l’œil.

{% hint style="info" %}
**objectif :** système très convergent. Distance focale de quelques mm. Assimilé à une lentille mince L 1 .  
**oculaire :** loupe formée de 2 lentilles non accolées. Distance focale de 2 cm environ. Assimilé ici à une lentille mince L 2 .
{% endhint %}

Le microscope = Objectif L1 + Oculaire L2  
- L'objectif L1 crée une **image réelle** A1B1 d'un objet AB  
- L'image réelle A1B1 est examinée comme un **objet intermédiaire réel** A1B1 par une loupe \(l'oculaire\) crée une **image final A'B' virtuelle**  
- Enfin l’œil regarde cette image virtuelle A'B' à travers l'oculaire

![](../.gitbook/assets/association_so_exemple.png)

#### Intervalle optique Δ

![](../.gitbook/assets/schema_association_so.png)

{% hint style="warning" %}
L’intervalle optique D est la distance entre le foyer image de l’objectif et le foyer objet de l’oculaire.
{% endhint %}

![](../.gitbook/assets/intervalle_optique.png)

#### Construction de l’image d’un objet AB

![](../.gitbook/assets/schema_microscope.png)

L’objectif L1 donne d'un objet réel AB, une image réelle A1B1 renversée plus grande que l’objet AB. L’oculaire L2 est une loupe qui examine cette image réelle A1B1 \(qui joue pour elle le rôle d’objet réel\) et en donne une image virtuelle A′B′ observable par l’œil à travers l’instrument

**Propriété**  
Noter la position de l’objet AB, devant l’objectif et très proche de L1   
Noter la position de l’image intermédiaire A1B1 par rapport à l’oculaire L2 : elle est située entre F2 et O2 afin d’obtenir une image finale virtuelle A′B′  
Noter que A1B1 est réelle, renversée par rapport à AB  
Noter que A′B′ est virtuelle, droite par rapport à A1B1

{% hint style="warning" %}
**Cas particulier**   
Si l’image intermédiaire A1B1 est située au foyer objet F2 de l’oculaire L2 alors l’image finale virtuelle A′B′ est à l’infini.   
Dans ce cas, un œil normal \(ou avec défaut mais corrigé\) pourra observer A′B′ à l’infini sans accommoder \(œil au repos\) : c’est la position idéale d’observation pour un œil, sans fatigue oculaire.
{% endhint %}

#### Cercle oculaire

Le cercle oculaire est l’image C'D' de la lentille d’entrée \(objectif L1 \), donc objet CD, donnée par l’oculaire L2 . Tous les rayons émis par l’objet et collectés par l’objectif passent par le cercle oculaire.

![](../.gitbook/assets/cercle-oculaire.png)

{% hint style="warning" %}
Une observation confortable suppose la coïncidence de la pupille de l’œil et du cercle oculaire.
{% endhint %}

#### Latitude de mise au point

Comme pour la loupe, on définit la latitude de mise au point ou profondeur de champ, qui est toujours la distance $$\overline{A_R A_P}$$ entre les positions extrêmes des objets qui donnent des images observables nettes par l’oeil, donc des images situées entre R et P de l’œil.

![](../.gitbook/assets/latitude_mise_point.png)

{% hint style="warning" %}
La latitude de mise au point du microscope, aussi appelée profondeur de champ, est $$ l = \overline{A_R A_P}$$ et vaut de l’ordre du millimètre.
{% endhint %}

#### Puissance de grossissement

**Puissance P \(en δ\)**  
Expression générale \(voir la loupe\) : $$P=\frac{\alpha '}{AB}$$  
Avec α′ l’angle sous lequel l’œil voit l’image A′B′ à travers l’instrument, en radians, et AB la dimension de l’objet, en mètres

![](../.gitbook/assets/puissance_microscope.png)

{% hint style="warning" %}
C’est aussi une expression générale : la puissance du microscope est égale au produit de la puissance de l’oculaire par la valeur absolue du grandissement de l’objectif.
{% endhint %}

On peut aussi définir la puissance intrinsèque P \( , pour une vision à l’infini \(image donnée par le microscope à l’infini et qui sera vue par l’œil emmétrope \(ou à défaut mais corrigé\) au repos \(sans accommodation\).

#### Puissance intrinsèque Pi

![](../.gitbook/assets/puissance_intrinseque.png)

#### Puissance intrinsèque du microscope

![](../.gitbook/assets/puissance_intrinseque_microscope.png)

Pi puissance intrinsèque ou nominale, ne dépend que de l’instrument, avec les longueur en mètres et Pi en dioptries. Typiquement 100 ≤ Pi ≤ 10000 δ

#### Grossissement du microscope

$$
G= \frac{\alpha '}{\alpha}
$$

Avec α′ l’angle sous lequel l’œil voit l’image A′B′ à travers l’instrument, en radians, et α l’angle sous lequel est vu l’objet à l’œil nu à la distance minimale de vision distincte de l’œil, en radians.

![](../.gitbook/assets/grossissement_microscope.png)

On définit le grossissement commercial Gc pour un œil normal qui observe un objet à l’infini à travers le microscope, donc pour d = 0, 25 m et P = Pi

![](../.gitbook/assets/grossissement_commercial%20%281%29.png)

#### Pouvoir séparateur du microscope

On considère deux cas limites :  
- Pour un microscope de puissance moyenne \(P i ≈ 1000 δ\) alors la limite de résolution est imposée par l’œil, avec $$ε = 3 × 10^{-4} $$ rad le pouvoir séparateur de l’œil seul \(sans instrument\)  
- Pour un microscope de puissance élevée \(P i &gt; 10000 δ\) alors la limite de résolution est imposée par les caractéristiques de la lumière   
→ le pouvoir séparateur est limité par le phénomène de diffraction

![](../.gitbook/assets/exemple_pouvoir_separateur_microscope.png)

### Application au correction des défauts de l’œil

#### Défaut de l’œil

Un œil avec des défauts est appelé amétrope  
Les défaut sont :   
- La myopie, si l’œil est trop convergent L'image se forme en avant de la rétine : vision de loin floue  
- L’hypermétropie, si l’œil n’est pas assez convergent L'image se forme en arrière de la rétine : vision de près floue, vision de loin impossible sans accommoder  
- L’astigmatie, qui est un défaut dans la courbure du cristallin ou de la cornée \(La cornée d’un oeil astigmate est légèrement ovale, les rayons lumineux qui arrivent sur l'oeil se focalisent en des points différents en arrière et en avant de la rétine ce qui provoque une déformation de l'image.

#### Correction de la myopie

**Définition**  
- L’œil myope est trop convergent   
- Le foyer image du DS est situé avant la rétine   
- Le punctum remotum R n’est pas à l’infini : on a SR &lt; 6 m.   
- Au repos, l’œil voit nettement des objets en R mais il ne peut pas voir des objets plus éloignés  
- Pour un œil myope le punctum proximum est en général plus proche de l’œil \(&lt; 25 cm\)  
**Correction**  
But : permettre à l’œil d’observer un objet à l’infini sans accommoder \(au repos\)

![](../.gitbook/assets/principe_correction_myopie.png)

Il faut positionner le foyer image F \# L des verres correcteurs au punctum remotum R de l’œil myope  
$$\overline{OF'_L} = \overline{OR} < 0$$  
Correction de la **myopie** par **lentilles minces divergentes** $$R=F'_L$$\*\*\*\*

![](../.gitbook/assets/schema_correction_lentille.png)

Correction par lentille divergente =&gt; lentille à bords épais  
$$\overline{OF'L} = \overline{OS} + \overline{SF'_L}=\overline{OS} + \overline{SR} <0$$  
Avec $$\overline{OS} $$ = distance de cornée &gt; 0  
$$\overline{OF'_L} = \overline{SR}$$

#### Correction de l’hypermétropie

**Définition  
-** L’œil n’est pas assez convergent  
- L’œil forme d’un objet à l’infini une image située derrière la rétine, donc il voit flou.   
- Le punctum remotum R n’est pas à l’infini : il est virtuel et situé derrière la rétine donc SR &gt; 0  
- Mais l’œil a la faculté d’accommoder -&gt; un œil hypermétrope non corrigé accommode en permanence \(fatigue visuelle\)  
**Correction**  
But : permettre à l’œil d’observer un objet à l’infini sans accommoder \(au repos\)

![](../.gitbook/assets/principe_correction_hypermetropie.png)

Il faut positionner le foyer image $$F'_L$$ des verres correcteurs au punctum remotum R de l’œil hypermétrope =&gt; $$\overline{OF'_L} = \overline{OR} > 0$$  
Correction de **l’hypermétropie** par **lentilles minces convergentes** $$R=F'_L$$

![](../.gitbook/assets/correction_hypermetropie_schema.png)

#### Correction de la presbytie

**Définition**  
La presbytie est la réduction du pouvoir d’accommodation.   
L’amplitude dioptrique d’accommodation A diminue \(à peu près linéairement avec l’âge\) donc l’œil, même en accommodant au maximum, n’est plus assez convergent. Le punctum proximum P s’éloigne avec l’âge.  
- à 10 ans : P.P. à 7 ou 8 cm → A ≈ 14 δ  
- à 20 ans : P.P. à 25 cm →A≈4δ  
- à 70 ans : P.P. &gt; 1 m →A&lt;1δ  
**Correction**  
On utilise des lentilles minces correctrices \(L\) afin d’observer, en accommodant au maximum, un objet AB situé à 0,25 m de l’œil \(donc A en P de l’œil normal = $$P_N$$\). L’image de cet objet par la lentille correctrice doit se former en P de l’œil presbyte non corrigé \(= $$P_P$$\) pour donner image nette sur la rétine de l’œil E par le dioptre \(DS\).

![](../.gitbook/assets/correction_presbitye.png)

#### Chirurgie ophtalmique pour corriger la myopie

* La photokératectomie réfractive
  * Au laser Excimer \(faisceau ultra-violet\)
  * Consiste à enlever une couche de l’épithélium de la cornée
  * Efficace pour les myopies entre −1 δ et −7δ
  * Cicatrisation difficile
* Le LASIK \(Laser In-situ Karatomilleusis\)
  * On soulève l’épithélium 
  * On modifie la courbure de la cornée 
  * On replace l’épithélium 
  * Efficace pour les myopies entre −1 δ et − 20 δ
  * Guérison plus rapide qu’avec la photokératectomie réfractive

