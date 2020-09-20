# Electricité et Radioactivité

## Électrostatique \(intro\)

### Définition

{% hint style="info" %}
**Électrostatique :** études des charges électriques immobile \(attraction/répulsion\)

**Électrocinétique :** études des charges en mouvement \(ce cours\)
{% endhint %}

### Propriété en électrostatique

#### Champ et potentiel électrique

Une charge électrique Q crée en tout point  de l'espace un champ électrique $$\vec{E}$$**\(en V/m\)** et un potentiel électrique **V \(en V\)**

#### Force électrique

Une charge électrique q placée dans un champ $$\vec{E}$$subit une force électrique $$\vec{F}$$\(en N\) telle que : $$\vec{F}=q\times \vec{E}$$

![](../.gitbook/assets/unite_elec.jpg)

Charge électrique élémentaire, porté par des électrons \(-e\) et les protons \(+e\) du noyau de l'atome avec $$e=1,6x10^{-19}C$$en coulomb.

## Potentiel, tension et courant électrique

### Potentiel

Le potentiel électrique définit l’énergie potentielle électrique qu’aurait une charge **q** en ce point, telle que : $$E_{pe}=q\times V$$avec Epe en joule, q en Coulomb et V en volt

{% hint style="info" %}
**Potentiel :** Etat électrique d'un point dans l'espace

**Courant :** Différence de potentiel entre deux points

On appelle **d.d.p** ou **tension** : \(Va-Vb\), **si il y a tension il y a alors courant.**
{% endhint %}

**Propriété**

En électrocinétique, le potentiel électrique est constant le long des fils.On peut déplacer les points le long des fils : utile pour l’étude des circuits.

![](../.gitbook/assets/propriete_tension_elec.jpg)

* Si Va &gt; Vb : courant de A vers B
* Si Va &lt; Vb : courant de B vers A 
* Si Va = Vb : pas de courant

![](../.gitbook/assets/potentiel_elec.jpg)

### Tension \(Différence de potentiel\)

{% hint style="info" %}
La tension entre deux points d’un circuit représente la différence de potentiel entre ces deux points.
{% endhint %}

**Convention**  
Soient A et B deux points d’un circuit tels que :

![](../.gitbook/assets/convention_tension_elec.jpg)

* On a $$U_{AB}=-U_{BA}$$
* La tension **Uab** est représentée par une flèche qui **pointe vers la 1 ère lettre donc de B vers A**
* L’unité de la tension est le volt, de symbole V.
* Les valeurs standards vont de quelques mV à quelques dizaines de kV

#### Répartition des tensions

![](../.gitbook/assets/repartition_tension_elec.jpg)

### Courant électrique

{% hint style="info" %}
Le courant électrique correspond au déplacement des charges électriques dans un matériau conducteur sous l’effet du champ électrique induit par une différence de potentiel.  
L’intensité $$i(t)$$ du courant mesure le débit des charges électriques $$dq(t)$$qui traversent la section S d’un conducteur pendant un temps $$dt$$ :

$$i(t)=\frac{dq(t)}{dt}$$ 

Si le courant est continu \(indépendant du temps\), l’intensité I \(en majuscules\) s’écrit :

$$I=\frac{\Delta Q}{\Delta t}$$
{% endhint %}

**Unité**  
Le courant électrique est mesuré en ampère \(A\), 1A -&gt; 1C/s , l’intensité électrique est proportionnelle au nombre de charges électriques qui traversent le conducteur \(fil\) par seconde.  
**Ordre de grandeur  
-** Installation domestique : 20 A   
- TGV : 1000 A au démarrage   
- Foudre : 1 à 100 kA   
- Electronique : mA, μA, nA  
L’intensité est mesurée par un ampèremètre placé en série dans le circuit.

#### Convention

* Le courant positif circule dans le sens des potentiels décroissants.
* Avec Va &gt; Vb on a I1 &gt; 0 et I2 &lt; 0
* Un courant positif dans un sens correspond à un courant négatif en sens inverse
* La valeur absolue de ces deux courants est la même.

![](../.gitbook/assets/convention_courant_elec.jpg)

#### Répartition des courants

![](../.gitbook/assets/repartition_courant_elec.jpg)

## Circuits électriques

### Dipôle

Un dipôle AB est un élément d’un circuit électrique possédant deux bornes \(pôles\) placées en A et en B. Le dipôle peut être actif ou passif.  
La résistance est un dipôle passif. Chaque dipôle possède sa propre loi et ses propres conventions

### Branche \(de circuit\)

C’est une partie de circuit électrique situé entre 2 nœuds consécutifs. Le long d’une branche, tous les éléments sont en série  
**Propriété**  
Le courant traversant une branche de circuit est identique partout \(en tout point\) le long de cette branche.

### Noeud \(de circuit\)

C’est un point de connexion entre au moins deux branches d’un circuit.  
**Propriété**  
Loi des nœuds : la somme des courants qui arrivent en 1 nœud est égale à la somme des courants qui sortent de ce nœud.  
$$\sum{I_{entrant}}=\sum{I_{sortant}}$$

### Maille \(de circuit\)

 Une maille est un chemin fermé sur le circuit électrique. La maille peut être composée de plusieurs branches. Dans ce cas, le chemin fermé ne doit jamais passer deux fois au même endroit.  
**Propriété**  
Loi des mailles : à voir au chapitre lois de Kirchhoff

#### Exemple

![](../.gitbook/assets/exemple_elec_circuit_elec.jpg)

## Résistivité, résistance et loi d’Ohm

### Résistivité

{% hint style="info" %}
La résistivité $$\rho$$ d’un matériau représente sa capacité à s’opposer à la circulation d’un courant. Unité : ohm.mètre \($$\Omega$$.m\)  
On définit aussi la conductivité $$\sigma$$, qui est l’inverse de la résistivité, $$\sigma = \frac{1}{\rho}$$ en \($$\Omega^{-1}$$ .m -1 \)  
  
Pour un matériau conducteur, la résistivité $$\rho$$ est très faible \(ex : $$\rho$$Ag ~ $$16\times 10^{-9}\Omega.m$$\) Pour un matériau isolant, la résistivité $$\rho$$ est très élevée \(ex : $$\rho$$verre ~ $$10^{17}\Omega .m$$\)
{% endhint %}

![](../.gitbook/assets/resistivite_elec.jpg)

### Résistance

{% hint style="info" %}
Dipôle électrique qui s’oppose au passage du courant. Unité : Ohm \($$\Omega$$\)   
La résistance est **responsable d’une dissipation d’énergie sous forme de chaleur \(effet Joule\)**.
{% endhint %}

**Association de résistances – Résistance équivalente**  
Dans un circuit électrique comprenant plusieurs résistances, les résistances pourront être associées entre elles pour simplifier des montages complexes et déterminer simplement des grandeurs physiques \(par exemple déterminer le courant qui traverse une association de résistances: voir exo E1.3\)   
Les résistances associées seront remplacées dans le circuit par une résistance équivalente Req

![](../.gitbook/assets/resistance_placement_elec.jpg)

#### Loi d'Ohm

En valeur absolue, la tension U aux bornes d’une résistance R est égale au produit de l’intensité I du courant qui la traverse par la valeur de la résistance.  
Convention \(très important\): le signe du produit R.I dépend des sens choisis pour U AB et I

![](../.gitbook/assets/loi_ohm_elec.jpg)

## Générateur et moteur

### Générateur idéale \(parfait\) sans résistance interne

#### Définition

{% hint style="info" %}
**Dipôle** capable de délivrer une **tension constante** quelque soit la charge reliée à ses bornes
{% endhint %}

#### Représentation et convention

Le générateur est caractérisé par une force électromotrice \(f.e.m.\) dont l’unité est le volt. C’est une tension \(donc une flèche sur le circuit\). La f.e.m. est une tension orientée **de la borne moins \(petite barre\) vers la borne plus \(grande barre\)**. Fem = tension constante = ddp  
Si dans un circuit on voit une f.e.m., on met directement une flèche dans le sens de la convention et cette **tension** est directement égale à **e**.   
Le générateur donne le sens du courant I si il n’y a qu’un seul générateur dans le circuit.

![](../.gitbook/assets/generateur_ideale.jpg)

$$U_{BA}=e$$, donc $$U_{BA} = V_B-V_A>0$$et $$V_B>V_A$$

### Générateur réelle

{% hint style="info" %}
Dipôle composé d'un générateur idéale F.e.m et d'une résistance interne r
{% endhint %}

#### Représentation

Pour un générateur réel, **la tension n’est pas constante** quelle que soit la charge \(la pente de la droite vaut –r\)  
**Loi de Pouillet :** $$U_{BA}=e-r\times I$$

![](../.gitbook/assets/generateur.png)

### Moteur

#### Définition

{% hint style="info" %}
Le moteur transforme l'énergie électrique en énergie mécanique. Il est caractérisé par sa force contre électromotrice e' \(F.c.e.m\), en Volts \(V\) et avec une résistance interne r'.
{% endhint %}

#### Représentation et convention

La f.c.e.m. e’ est une tension orientée de la borne moins \(petite barre\) vers la borne plus \(grande barre\). Même convention et représentation que pour le générateur. **Attention : la f.c.e.m. ne donne pas le sens du courant.**  
$$U_{BA}=e'+r'\times I$$

![](../.gitbook/assets/moteur_convetniob.png)

