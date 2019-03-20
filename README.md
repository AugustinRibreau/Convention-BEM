# Convention BEM
👋 Bienvenue sur la convention BEM. <br>
### Contexte
Les conventions de nommage sont très importantes pour collaborer à plusieurs sur de gros projets. <br>
Plusieurs impacts :
- Logique commune
- Scope : éviter les surcharges indésirables et se faire surprendre par la cascade CSS
- Lisibilité du code
<br><br>
Les CSS modules et POST-CSS permettent de facilement contrer le scope. 
Cependant pour la lisibilité du code il reste important de garder une convention commune entre développeurs.

### BEM

BEM est une convention de nommage afin de fournir une logique et une rigueur au noms des classes CSS.<br>
BEM -> Block Element Modifier (exemple: .block__element--modifier)

- `.avatar` représente le block
- `.avatar__img` représente un élément du block
- `.avatar__img--rounded` représente une modification de l'élément

## Aller plus loin
#### BEM + ITCSS = BEMIT
Si l'on utilise l'architecture ITCSS, il est intéressant de pousser un peu plus loin la convention BEM en tirant parti de préfixes qui feront office de namespaces. Le nommage des classes devient donc quelque chose de la forme prefix-block__element--modifier où prefixe n'est autre que la première lettre de la nature de la classe :

- `.o-block__element--modifier` pour les objets
- `.c-block__element--modifier` pour les composants
- `.u-block__element--modifier` pour les utilitaires

## Auteur
- Augustin Ribreau - <i>Developpeur</i> - <a href="https://augustin.ribreau.co/" target="_blank">augustin.ribreau.co</a>

Voir aussi la liste des <a href="https://github.com/AugustinRibreau/Convention-BEM/blob/master/source.txt" target="_blank">sources</a> ayant été utilisé.
