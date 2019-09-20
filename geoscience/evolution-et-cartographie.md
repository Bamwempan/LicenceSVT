---
description: Semestre Automne année 1
---

# Evolution et Cartographie

## Localisation sur une carte topographique

* [ ] Règle de trigonométrie

#### Objectifs

* Lecture de carte topographique
* Mesure fontes des glaciers
* Rapport entre la 2D et la 3D

### Définitions

{% hint style="info" %}
**Carte :** Image **réduite**, **plane** et **symbolique** d'une portion de données spatiales.7
{% endhint %}

### Notion d’échelle

{% hint style="warning" %}
L'échelle d'une carte est le rapport entre la longueur d'un objet sur la carte et sa longueur réelle.  
L'échelle s'exprime sous la forme d'une fraction simple.

Exemple : Une carte est dite "1/50 000" lorsque pour 1cm sur la carte correspond à 50 000cm, soit 500m.
{% endhint %}

$$1/25000$$ est considéré comme une petite échelle  
 $$1cm$$ sur la carte est égale à $$25000cm$$ en réelle soit $$250m$$ 

$$1/1\ 000\ 000$$ est considéré comme une grande échelle  
 $$1cm$$ sur la carte est égales à $$1\ 000\ 000cm$$ en réelle soit $$10km$$ 

### Système de projection

{% hint style="warning" %}
La carte, plane, représente une portion d'un objet "globalement" sphérique, la Terre.  
On assimilera la terre au "**Géoïde**" : surface du niveau moyen au niveau des océans, forme très proche d'un ellipsoïde de révolution.  
Les dimensions de **l'ellipsoïde WGS84** utilisé sur les cartes IGN sont les suivantes : 

_**Rayon équatorial**_ $$a = 6378,137\ km$$ 

_**Rayon polaire**_ $$b = 6356,752 \ km$$ 

_**Aplatissement**_ $$f=(a-b)/a =1/298,257$$ 
{% endhint %}

{% hint style="info" %}
**Géoïde :** Surface de référence qui tient compte de ses irrégularité plus précis qu'une sphère ou un ellipsoïde
{% endhint %}

Il existe plusieurs système de projection, ici on utilisera le système de projection **Universal Transverse Mercator \(UTM\) 31N.**   
Elle est **conforme**, les surfaces y gardent leur forme, mais pas leurs dimensions, et **cylindrique**.

{% hint style="success" %}
La France est dans 3 fuseaux, de 30 à 32.
{% endhint %}

### Méridien et Parallèle

{% hint style="info" %}
**Méridien :** Ligne d'intersection entre un plan qui passe par les pôles et le géoïde. On définit un méridien d'origine, passant par Greenwich à Londres, arc NAS.

**Parallèle :** Ligne marquant l'intersection entre un plan parallèle au plan équatorial et le géoïde. Ce parallèle sera celui du point P s'il passe par P.
{% endhint %}

![M&#xE9;ridien Parall&#xE8;le](../.gitbook/assets/meridien-parallele.jpeg)

Pour retrouver un point on chercher sa **longitude \(Angle AOB\)** et sa **latitude \(Angle BOP\)**.

{% hint style="info" %}
**Latitude - BOP :** de 0° à 90° en précisant Nord ou Sud. Parallèle 0 est l’équateur

**Longitude - AOB :** de 0° à 180° en précisant West ou Est. Méridien 0 est Greenwich
{% endhint %}

Les coordonnées géographiques sont traditionnellement exprimées dans le système sexagésimal, parfois noté « DMS » : degrés \( ° \) minutes \( ′ \) secondes \( ″ \). L'unité de base est le degré d'angle \(1 tour complet = 360°\), puis la minute d'angle \(1° = 60′\), puis la seconde d'angle \(1° = 3 600″\).  
Pour donner une comparaison approximative en distance de ces unités à la surface de la Terre, le périmètre de la Terre qui correspond à 360° est d'environ 40 000 km2. Plus précisément, il est de 40 075,017 km à l'équateur ; par conséquent :

* un degré représente environ 111,319 km \(à l'équateur\) 
* une minute représente environ 1,855 km \(à l'équateur\)
*  une seconde représente environ 30,92 m \(à l'équateur\).

### Coordonnée UTM d'un point

Les coordonnée UTM d'un point sont en Km, la projection UTM se traduit par un **quadrillage N-S et W-E** sur la cartes représentée par des **croix** dont les valeurs qui les sépare est toujours **1Km**. 

Pour trouver les coordonnées d'un point UTM il faut repérer les 4 croix qui entoure ce point et procéder à la récupération des coordonnées kilométrique du point grâce à un système d’abscisse et d’ordonnée \(X et Y\).

### Carte topographique 

Une carte topographique est une carte qui représente les **éléments naturels** \(Relier, cours d'eau, végétation...\) et **artificiels** \(Bâtiments, route...\), le tout est symbolisé par des signes conventionnels.

### Réponse TP

#### Question 1

Sur la carte, $$4cm$$ représente $$1km$$ soit $$1cm = 0.25km = 25\ 000cm$$ on peut donc dire que l'échelle de la carte est $$1/25000$$ 

#### Question 2

Latitudes ~= 45°52,8'N  
Longitude ~= 5°24,6'E

#### Question 3 

Les coordonnées UTM sont 687100 latitude en X et 5083600 longitude en Y.  
Pour se faire X 4mm -&gt; 0.004m x 25000 = 100m et Y 2.4cm -&gt; 0.024m x 25000 = 600m

#### Question 4

Pour localiser le point B de coordonnée UTM x = 686 307 et Y = 5 083 018 il faut repérer le quadrillage qui correspond à ce point et calculer les distance entre le début du quadrillage et le point, Soit  
X : 686 307 - 686 000 = 307m / 25000 = 0.012m = 1.2cm  
Y : 5 083 018 - 5 083 000 = 18m / 25000 = 0,00072m = 0.72mm  

## Ressources

### Tableau de conversion des mesures principales

![Conversion principales](../.gitbook/assets/capture-du-2019-09-20-16-48-41.png)

### Règle de trigonométrie

![R&#xE8;gle trigonom&#xE9;trie](../.gitbook/assets/exercice-trigonometrie.png)

