[Quiz](https://openclassrooms.com/en/courses/7542506-creez-des-sites-web-responsives-avec-bootstrap-5/exercises/4294)
# Ajouter de l'interactivité à votre site

## Question 1
**Quels sont les composants uniquement composés de CSS dans cette liste (plusieurs réponses possibles) ?**
- [x] Cards
- [x] Progress bar
- [ ] Offcanvas
- [ ] Carousel

_En effet, certains composants n’utilisent que du CSS, mais d’autres nécessitent du JS pour fonctionner correctement, tels que l’   offcanvas  et la   modal  ._

## Question 2
**À quoi sert l’attribut   data-*  ?**
- [ ] À utiliser une base de données
- [ ] À permettre au CSS et au HTML de s’échanger des données
- [ ] À associer des classes et des id
- [x] À permettre au JS et au HTML de s’échanger des données

_Les attributs   data-*  sont des attributs servant à échanger des données entre le HTML et le JS en passant par le DOM (l’ensemble des éléments d’une page HTML)._

## Question 3
**Les attributs   data-*  sont personnalisables par le développeur.**
- [x] Vrai
- [ ] Faux

_En effet, nous pouvons personnaliser ce qui vient derrière l’attribut   data-{personnalisable}  . Bootstrap a utilisé le sigle “bs” dans ses attributs   data-*  afin d’éviter d’identifier simplement ses propres attributs._

## Question 4
**Quelle classe doit être utilisée pour mettre en page un   input  type “text” dans Bootstrap 5 ?**
- [ ] form-select
- [ ] form-group
- [ ] form-input
- [x] form-control

_Il s’agit de la classe   form-control  ! Tous les   input  doivent être accompagnés de   label  qui prendront, dans le cas des types   text  , la classe   form-label  ._

## Question 5
**Quelles autres classes existent dans la mise en page de formulaire dans Bootstrap 5 ? (Plusieurs réponses possibles.)**
- [x] form-select
- [x] form-range
- [x] form-check-input
- [x] form-check-label

_En plus des classes   form-control  et   form-label  , nous avons toutes les classes citées ci-dessus._

## Question 6
**Les classes   .modal-header  ,   .modal-body  et   .modal-footer  sont indispensables au bon affichage d’une   modal  .**
- [ ] Vrai
- [x] Faux

_C’est faux. Ces classes servent à segmenter le contenu d’une   modal  , mais elles ne sont pas obligatoires pour lui permettre de s’afficher correctement._

## Question 7
**Les   tooltips  sont dépendants de la bibliothèque JS tierce Popper.js.**
- [x] Vrai
- [ ] Faux

_Vrai. Pour faire fonctionner les   tooltips  de Bootstrap, vous devez utiliser la bibliothèque Popper.js. De ce fait, il est obligatoire d’écrire un peu de JS personnalisé pour les initialiser._

## Question 8
**Comment est-ce que je peux associer du texte à un lien mis sur une icône ?**
- [x] En ajoutant un “tooltip”
- [x] En ajoutant un attribut “title”
- [ ] En ajoutant un “p” avec un attribut “for”
- [ ] Ce n’est pas possible

_L’attribut “title” natif du HTML sert entre autres à ça, et fonctionne sans Bootstrap. Cependant, les “tooltips” permettent d’améliorer les “titles” pour les rendre plus agréables pour l’utilisateur._