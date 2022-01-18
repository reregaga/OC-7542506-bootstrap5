[Quiz](https://openclassrooms.com/en/courses/7542506-creez-des-sites-web-responsives-avec-bootstrap-5/exercises/4292)
# Créer des mises en page responsives

## Question 1
**Que crée le fait d’envelopper le contenu de votre page dans une div avec la classe  .container-fluid  ?**
- [ ] Un conteneur centré qui s'adapte à la largeur de son contenu
- [ ] Un conteneur centré qui s'adapte à la largeur de la zone de visualisation
- [x] Un conteneur qui occupe 100 % de la largeur de la zone de visualisation

_Envelopper votre contenu dans un élément div avec la classe  .container-fluid  crée un conteneur qui occupe 100 % de la largeur de la zone de visualisation. D'autre part, l'envelopper dans un div avec une classe  .container  permet de s'adapter à la largeur de la zone de visualisation et de fournir un remplissage horizontal pour ses contenus, afin qu'ils soient éloignés des bordures._

## Question 2
**Quelle est la hiérarchie basique des classes utilisées pour créer une grille Bootstrap ?**
- [ ] Conteneur &gt; colonne &gt; ligne
- [ ] Ligne &gt; colonne &gt; conteneur
- [x] Conteneur &gt; ligne &gt; colonne
- [ ] Colonne &gt; conteneur &gt; ligne

_La hiérarchie basique de la grille de Bootstrap est celle d'un conteneur qui contient des lignes, qui à leur tour contiennent des colonnes._

## Question 3
**Combien de breakpoints (points d'arrêt) existe-t-il dans Bootstrap ?**
- [ ] 5
- [x] 6
- [ ] 4
- [ ] 7

_En effet, il existe bien 6 breakpoints dans Bootstrap mais seulement 5 modificateurs de classe  "-sm" "-md" "-lg" "-xl" "-xxl"  , car les écrans de très petite taille n'ont pas besoin de modificateur de classe._

## Question 4
**Combien de colonnes chacun des divs avec la classe .col dans cet extrait de code occupera-t-il ?
&lt;div class="row"&gt;
   &lt;div class="col"&gt;
   ...
   &lt;/div&gt;
   &lt;div class="col"&gt;
   ...
   &lt;/div&gt;
   &lt;div class="col"&gt;
   ...
   &lt;/div&gt;
&lt;/div&gt;**
- [ ] 6
- [ ] 3
- [x] 4
- [ ] 2

_La grille de Bootstrap par défaut est basée sur une structure à 12 colonnes. Cela implique que l'utilisation de la classe  .col  sans modificateur de classe divisera la grille de manière égale dans toutes les zones de visualisation entre les divs dans une ligne. Dans ce cas, les 12 colonnes seront divisées de manière égale entre les 3 divs, ce qui donne à chacun une largeur de 4 colonnes._

## Question 5
**Laquelle de ces propositions créera une ligne qui contient deux  &lt;div&gt;  , la première occupant ¼ de la largeur et la seconde occupant ¾ de la largeur ?**
- [x] &lt;div class="row"&gt;
   &lt;div class="col-3"&gt;...&lt;/div&gt;
   &lt;div class=”col-9"&gt;...&lt;/div&gt;
&lt;/div&gt;
- [ ] &lt;div class="row"&gt;
   &lt;div class="col-1”&gt;...&lt;/div&gt;
   &lt;div class=”col-3"&gt;...&lt;/div&gt;
&lt;/div&gt;
- [ ] &lt;div class="row"&gt;
   &lt;div class="col-1”&gt;...&lt;/div&gt;
   &lt;div class=”col-3"&gt;...&lt;/div&gt;
&lt;/div&gt;
- [ ] &lt;div class="row"&gt;
   &lt;div class="col-4”&gt;...&lt;/div&gt;
   &lt;div class=”col-8"&gt;...&lt;/div&gt;
&lt;/div&gt;

_Étant donné que Bootstrap est basé sur une grille à 12 colonnes, une  &lt;div&gt;  qui occupe ¼ de la largeur recouvre 3 colonnes et a donc une classe de  .col-3  . Tandis que la seconde  &lt;div&gt; recouvre 9 colonnes et a une classe de  .col-9  ._

## Question 6
**Dans le contexte de conception et de développement frontend, qu’est-ce qu’un breakpoint (point d'arrêt) ?**
- [ ] Une taille en pixels, définie par le développeur (ou le framework CSS), à partir de laquelle le site ne doit plus s’afficher pour l’utilisateur.
- [ ] Une taille en pixels, définie par le navigateur, à partir de laquelle la mise en page du site change automatiquement.
- [x] Une taille en pixels, définie par le développeur (ou le framework CSS), à partir de laquelle la mise en page du site Internet est susceptible de changer.
- [x] Une taille en pixels, définie par le navigateur, à partir de laquelle la mise en page du site Internet est susceptible de changer.

_Dans le contexte de conception et de développement front-end, un point d'arrêt est un point auquel la mise en page peut changer. Il est généralement exprimé sous la forme d'un nombre correspondant au nombre de pixels qui représente la largeur de la zone de visualisation à laquelle le “breakpoint” a lieu._

## Question 7
**Selon le code suivant, quelles tailles d’écran aura chaque  &lt;div&gt;  des colonnes occupant la moitié de la largeur de la ligne ?
&lt;div class="row"&gt;
   &lt;div class="col-6 col-md-4”&gt;...&lt;/div&gt;
   &lt;div class=”col-6 col-md-8"&gt;...&lt;/div&gt;
&lt;/div&gt;**
- [x] Très petite
- [x] Petite
- [ ] Moyenne
- [ ] Grande
- [ ] Très grande

_La classe  .col-6  ne comporte aucun modificateur de classe relatif à la taille. Elle ne s'applique donc qu'aux zones de visualisation très petites minimum. En revanche, les classes  .col-md-*  s'appliquent aux zones de visualisation moyennes minimum, remplaçant ainsi la classe antérieure de ces zones de visualisation. La  .col-6  , qui recouvre la moitié de la grille à 12 colonnes, ne s'appliquera qu'aux zones de visualisation très petites et petites._

## Question 8
**Laquelle des structures de grille suivantes aura le comportement responsive suivant : la moitié de la largeur sur des écrans petits et très petits ; ⅓ de la largeur sur des écrans moyens et ¼ de la largeur à partir des grands écrans ?**
- [ ] &lt;div class="row"&gt;
   &lt;div class="col-6 col-md-3 col-lg-4"&gt;
   …
   &lt;/div&gt;
   …
&lt;/div&gt;
- [ ] &lt;div class="row"&gt;
   &lt;div class="col-2 col-md-3 col-lg-4"&gt;  
   …
   &lt;/div&gt;
   …
&lt;/div&gt;
- [x] &lt;div class="row"&gt;
   &lt;div class="col-6 col-md-4 col-lg-3"&gt;
   …
   &lt;/div&gt;
   …
&lt;/div&gt;
- [ ] &lt;div class="row"&gt;
   &lt;div class="col-sm-6 col-md-4 col-lg-3"&gt;
   …
   &lt;/div&gt;
   …
&lt;/div&gt;

_Étant donné que les zones de visualisation très petites et petites doivent recouvrir la moitié de la largeur de la grille, la classe  .col-6  s'applique aux zones de visualisation très petites minimum. L'ajout de la classe  .col-md-4  remplace celle pour les zones moyennes minimum. Ainsi, la  &lt;div&gt;  recouvre 4 colonnes sur 12 (c'est-à-dire ⅓). Enfin, l'ajout de la classe  .col-lg-3  remplace les classes précédentes pour les grandes zones de visualisation minimum. Ainsi, la  &lt;div&gt;  recouvre 3 colonnes sur 12 (c'est-à-dire ¼)._