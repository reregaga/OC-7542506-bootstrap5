[Quiz](https://openclassrooms.com/en/courses/7542506-creez-des-sites-web-responsives-avec-bootstrap-5/exercises/4293)
# Afficher du contenu avec les composants d'interface utilisateur

## Question 1
**Quels sont les bons réflexes à avoir lorsque vous voulez intégrer un composant Bootstrap 5 sur votre site ?**
- [x] Aller voir un tuto sur YouTube
- [x] Consulter la documentation Bootstrap 5 du composant en question
- [ ] Aller chercher des exemples d'utilisation du composant sur internet
- [ ] Le coder tout de suite en faisant des tests réguliers pour vérifier le rendu

_Le premier réflexe à avoir, que ce soit pour Bootstrap ou autre chose, c’est de commencer par se renseigner sur ce que l’on souhaite faire avant de commencer à le faire._

## Question 2
**Comment rendre une barre de navigation responsive sur les écrans en dessous de la taille moyenne ?**
- [ ] &lt;nav class="navbar navbar-expand-md"&gt;
   &lt;a class="navbar-brand" href="&num;"&gt;Navbar&lt;/a&gt;
       &lt;ul class="navbar-nav"&gt;
           &lt;li class="nav-item"&gt;
               &lt;a href="&num;" class="nav-link"&gt;&lt;/a&gt;
           &lt;/li&gt;
       &lt;/ul&gt;
     &lt;button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="&num;navbarMobile"&gt;
       &lt;span class="navbar-toggler-icon"&gt;&lt;/span&gt;
   &lt;/button&gt;
   &lt;div class="collapse navbar-collapse" id="navbarMobile"&gt;
       &lt;ul class="navbar-mobile"&gt;
           &lt;li class="nav-item"&gt;
               &lt;a href="&num;" class="nav-link"&gt;&lt;/a&gt;
           &lt;/li&gt;
       &lt;/ul&gt;
   &lt;/div&gt;
&lt;/nav&gt;
- [ ] &lt;nav class="navbar navbar-mobile-xs navbar-expand-md"&gt;
   &lt;a class="navbar-brand" href="&num;"&gt;Navbar&lt;/a&gt;
       &lt;ul class="navbar-nav"&gt;
           &lt;li class="nav-item"&gt;
               &lt;a href="&num;" class="nav-link"&gt;&lt;/a&gt;
           &lt;/li&gt;
       &lt;/ul&gt;
&lt;/nav&gt;
- [ ] &lt;nav class="navbar"&gt;
   &lt;a class="navbar-brand" href="&num;"&gt;Navbar&lt;/a&gt;
       &lt;ul class="navbar-nav"&gt;
           &lt;li class="nav-item"&gt;
               &lt;a href="&num;" class="nav-link"&gt;&lt;/a&gt;
           &lt;/li&gt;
       &lt;/ul&gt;
&lt;/nav&gt;
&lt;nav class="navbar-mobile"&gt;
   &lt;a class="navbar-brand" href="&num;"&gt;Navbar&lt;/a&gt;
&lt;button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="&num;navbarMobile"&gt;
       &lt;span class="navbar-toggler-icon"&gt;&lt;/span&gt;
   &lt;/button&gt;
   &lt;div class="collapse navbar-collapse" id="navbarMobile"&gt;
       &lt;ul class="navbar-nav"&gt;
           &lt;li class="nav-item"&gt;
               &lt;a href="&num;" class="nav-link"&gt;&lt;/a&gt;
           &lt;/li&gt;
       &lt;/ul&gt;
   &lt;/div&gt;
&lt;/nav&gt;
- [x] &lt;nav class="navbar navbar-expand-md"&gt;
   &lt;a class="navbar-brand" href="&num;"&gt;Navbar&lt;/a&gt;
   &lt;button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="&num;navbarMobile"&gt;
       &lt;span class="navbar-toggler-icon"&gt;&lt;/span&gt;
   &lt;/button&gt;
   &lt;div class="collapse navbar-collapse" id="navbarMobile"&gt;
       &lt;ul class="navbar-nav"&gt;
           &lt;li class="nav-item"&gt;
               &lt;a href="&num;" class="nav-link"&gt;&lt;/a&gt;
           &lt;/li&gt;
       &lt;/ul&gt;
   &lt;/div&gt;
&lt;/nav&gt;

_En ajoutant la classe  navbar-expand-md  et en utilisant le composant “collapse” sur notre liste de liens, on permet à la barre de navigation d’être cachée sur les petits et très petits écrans, et d’afficher un bouton permettant de l’afficher au clic de l’utilisateur._

## Question 3
**Que font les classes   .navbar-light  et   .navbar-dark  ?**
- [ ] Elles ajustent la couleur de l'arrière-plan du composant barre de navigation
- [x] Elles ajustent la couleur des éléments dans le composant barre de navigation
- [ ] Elles ajustent la couleur de l'arrière-plan et de l'élément du composant barre de navigation
- [ ] Elles permettent d’ajouter une option de changement de thème dans la barre de navigation

_Les classes   .navbar-light  et   .navbar-dark  ajustent la couleur des éléments dans la barre de navigation, tels que du texte à l’intérieur de la classe   .navbar-brand  ou les liens de navigation, pour offrir un contraste marquant avec l'arrière-plan choisi. Les classes   bg-*  sont celles qui peuvent ajuster l'arrière-plan du composant._

## Question 4
**Laquelle des propositions suivantes permet d’aligner le texte à droite pour les petits et très petits écrans, de le centrer pour les écrans moyens et de le remettre à droite pour le reste ?**
- [ ] &lt;p class="text-right text-md-center text-lg-right"&gt;...text..&lt;/p&gt;
- [ ] &lt;p class="text-xs-right text-md-center text-right"&gt;...text..&lt;/p&gt;
- [x] &lt;p class="text-end text-md-center text-lg-end"&gt;...text..&lt;/p&gt;
- [ ] &lt;p class="text-end text-md-center"&gt;...text..&lt;/p&gt;

_Depuis Bootstrap 5, le sens de lecture prend une place plus importante dans la logique de développement du framework ; c’est pourquoi les dénominateurs “left” et “right” ont été remplacés par “start” et “end”._

## Question 5
**Quelle logique Bootstrap 5 utilise pour construire le nom des classes utilitaires (la plupart du temps) ?**
- [ ] Il n’y a pas vraiment de logique, c’est du par cœur
- [ ] Elles prennent les initiales du nom, ou le nom complet de la propriété, collé(es) à sa valeur
- [ ] Elles prennent le nom du composant auquel elles sont liées
- [x] Elles prennent les initiales ou le nom complet de la propriété, séparé(es) de sa valeur par un tiret

_Pour la grande majorité des classes utilitaires elle porte le nom de la propriété qu’elles appliquent. De ce fait, il n’est pas bien compliqué de retenir ou deviner le nom des classes utilitaires de Bootstrap 5._

## Question 6
**Il est possible de combiner les classes utilitaires et les composants Bootstrap 5.**
- [x] Vrai
- [ ] Faux

_Tout à fait, et c’est même en faisant ça que l’on découvre toute la puissance de Bootstrap 5._

## Question 7
**Il existe souvent plusieurs variantes des composants Bootstrap 5.**
- [x] Vrai
- [ ] Faux

_L’avantage des frameworks aussi complets que Bootstrap 5, c’est la diversité des composants mis à la disposition des développeurs. Il est toujours bénéfique de parcourir toute la documentation d’un composant pour voir toutes les possibilités de personnalisation de ce dernier._

## Question 8
**Les composants Bootstrap 5 sont flexibles sur l’architecture des éléments qui les composent.**
- [ ] Vrai
- [x] Faux

_Faux ! Les composants Bootstrap 5 ont une architecture spécifique à respecter pour qu’ils fonctionnent. Cependant, il existe souvent plusieurs variantes d’un même composant, permettant ainsi une certaine flexibilité dans les usages qu’on peut en faire._
