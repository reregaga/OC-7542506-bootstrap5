[Quiz](https://openclassrooms.com/en/courses/7542506-creez-des-sites-web-responsives-avec-bootstrap-5/exercises/4295)
# Créer des fonctionnalités et des thèmes personnalisés

## Question 1
**La personnalisation de Bootstrap 5 se fait en Sass, dans un dossier  .scss.**
- [x] Vrai
- [ ] Faux

_Vrai ! Il faut installer Bootstrap 5 en local via npm par exemple afin d'accéder aux fichiers sources   .scss  de Bootstrap, et en modifier le fichier   _variables.scss  ou en créer un nouveau pour le remplacer (ex. :   _variables_override.scss  )._

## Question 2
**Quels enchaînements de lignes de commandes permettent l’installation de Bootstrap via npm ?**
- [x] cd dossierDeMonProjetnpm initnpm install bootstrap
- [ ] npm install bootstrap
- [ ] cd dossierDeMonProjetnpm install bootstrap
- [ ] npm initnpm install bootstrap

_Il faut bien penser à positionner son terminal de commande dans le bon dossier, ensuite il faut initialiser npm s’il n’est pas déjà utilisé et enfin installer Bootstrap._

## Question 3
**Quelle proposition permet de modifier les variables Sass de Bootstrap depuis le fichier _variables_overrides.scss ?**
- [ ] @import “./node_modules/bootstrap/sass/bootstrap.scss”
@import “./sass/_variables_overrides.scss”
@import “./node_modules/bootstrap/sass/_variables.scss”
- [ ] @import “./node_modules/bootstrap/sass/bootstrap.scss”
@import “./node_modules/bootstrap/sass/_variables.scss”
@import “./sass/_variables_overrides.scss”
- [ ] @import “./node_modules/bootstrap/sass/bootstrap.scss”
@import “./sass/_variables_overrides.scss”
- [x] @import “./sass/_variables_overrides.scss”
@import “./node_modules/bootstrap/sass/bootstrap.scss”

_Le fichier   ./sass/_variables_overrides.scss  dans lequel vous allez déclarer vos nouvelles variables doit se placer avant le fichier   ./node_modules/bootstrap/sass/bootstrap.scss  , car la lecture du Sass se fait de haut en bas._

## Question 4
**Que se passe-t-il si vous passez à   false  l’option   enable-shadow  dans votre fichier   ./sass/_variables_overrides.scss  ?**
- [ ] Les classes utilitaires liées aux   box-shadow  ne sont plus générées
- [ ] Seuls les boutons n’ont plus de   box-shadow
- [x] Plus aucun élément graphique n’utilise de   box-shadow
- [ ] Les classes utilitaires liées aux   box-shadow  ne sont plus générées, et plus aucun élément graphique n’utilise de   box-shadow

_Bootstrap 5 met à disposition plusieurs options modifiables sous forme de   true  ou   false  qui permettent la modification générale de tous les composants du framework, telles que   enable-shadow  qui, en étant égale à   false  , fait en sorte qu’aucun élément graphique n’utilise de   box-shadow  ._

## Question 5
**Pour fonctionner correctement, le Sass n’a pas besoin d’être compilé en CSS.**
- [ ] Vrai
- [x] Faux

_Le langage Sass n’est pas interprété par les navigateurs, il a besoin d’être compilé en CSS pour être lu par ces derniers. Dans ce cours, vous avez vu la méthode avec npm et Sass (  sass --watch scss:css  ), mais il existe d’autres méthodes, comme le logiciel Koala ou encore le plugin VS Code Live Sass._

## Question 6
**Comment est-ce que je peux générer la classe utilitaire personnalisée   z-xs-10  équivalant à   z-index: 10  pour les écrans de petite taille ?**
- [ ] $utilities: map-merge(
    $utilities,(
        “z-index” : (
            property: z-index,
            class: z,
            values: (
                0: 0,
                10: 10,
                20: 20,
                30: 30,
                40: 40,
                50: 50
            ),
        )
    )
)
- [x] $utilities: map-merge(
    $utilities,(
        “z-index” : (
            property: z-index,
            class: z,
            responsive: true,
            values: (
                10: 10,
            ),
        )
    )
)
- [ ] $utilities: map-merge(
    $utilities,(
        “z-index” : (
            property: z-index,
            responsive: true,
            values: (
                10: 10,
                50: 50,
                100: 100,
            ),
        )
    )
)
- [x] $utilities: map-merge(
    $utilities,(
        “z-index” : (
            property: z-index,
            class: z,
            responsive: true,
            values: (
                0: 0,
                10: 10,
                20: 20,
                30: 30,
                40: 40,
                50: 50
            ),
        )
    )
)

_Pour que l’API utilitaire de Bootstrap 5 génère des classes en responsive, il faut lui donner l’option   responsive: true  et lui attribuer les valeurs que nous recherchons. Dans ce cas précis, il faut également penser à l’option   class: z  car nous souhaitons la structure   z-xs-10  et non   z-index-xs-10  ._

## Question 7
**Dans quel ordre devez-vous importer vos fichiers Sass pour pouvoir utiliser l’API utilitaire dans le fichier ./sass/_utilities_custom.scss ?**
- [x] @import “./sass/_variables_overrides.scss”
@import “./sass/_utilities_custom.scss”
@import “./node_modules/bootstrap/sass/bootstrap.scss”
- [ ] @import “./node_modules/bootstrap/sass/bootstrap.scss”
@import “./sass/_utilities_custom.scss”
@import “./sass/_variables_overrides.scss”
- [x] @import “./sass/_utilities_custom.scss”
@import “./node_modules/bootstrap/sass/bootstrap.scss”
@import “./sass/_variables_overrides.scss”
- [ ] @import “./sass/_variables_overrides.scss”
@import “./node_modules/bootstrap/sass/bootstrap.scss”
@import “./sass/_utilities_custom.scss”

_Pour pouvoir utiliser l’API utilitaire de Bootstrap 5, il faut que le fichier  @import “./sass/_utilities_custom.scss”   soit importé avant @import “./node_modules/bootstrap/sass/bootstrap.scss”  .Dans la réponse 3, l’API fonctionnera dans   ./sass/_utilities_custom.scss  , mais les   ./sass/_variables_overrides.scss  ne seront pas utilisées car elles sont chargées après._

## Question 8
**En personnalisant les fichiers Sass de Bootstrap 5, il est possible de :**
- [x] Modifier les valeurs des breakpoints
- [x] Modifier les couleurs utilisées par les composants Bootstrap
- [x] Modifier la taille et la police des textes (titres, paragraphes, liens, etc.)
- [x] Modifier et ajouter des classes utilitaires

_La personnalisation du fichier Sass de Bootstrap 5 est extrêmement puissante, elle permet de donner un tout autre visage à son Bootstrap tout en bénéficiant de tous ses composants déjà codés. La liste de réponses ci-dessus n’est pas exhaustive de tout ce que Bootstrap nous permet de personnaliser._
