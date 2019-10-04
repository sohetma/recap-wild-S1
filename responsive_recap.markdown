# **Responsive Web Design**

## 1. Qu'est-ce que c'est ? 

Réorganisation des éléments sur une page de navigateur ou sur une app en fonction du changement de taille de l'écran en vue de développer une seule interface auto-adaptable.

- Changement de taille d'élements
- Changement de position d'élements
- Disparition d'éléments
- Optimisation d'images

![Alt Text](https://www.vervesearch.com/wp-content/uploads/2014/10/blog-01-01.jpg)

## 2. Comment ça se passe ?

Les développeurs ont plusieurs méthodes lorsqu'ils souhaitent travailler sur le Responsive, celles que nous avons vues cette semaine sont :

### Media Queries :

Variation des propriétés CSS en fonction de conditions particulières :

-	Type d’affichage : écran, impression, braille…
-  Largeur de l’écran (définition de points de rupture)
-  Orientation de l'écran

Exemple : 
```diff
- @media only screen and (max-width: 600px) {...}
```

### FlexBox :

Méthode de mise en page permettant de disposer des éléments en lignes ou en colonnes, en s’adaptant automatiquement à l’espace disponible et en facilitant les réagencements au moyen de **"containers"**. Pleins d'astuces sur le site [CSS tricks](https://css-tricks.com/).

![Flexbox](/flex.png)

```diff
- .container {
   /* Create a flex container */
   display: flex;
   /* Items direction (here in row, from left to right) */
   flex-direction: row;
   /* Behaviour when items overflow the parent container (here, items go to a new line automatically if needed) */
   flex-wrap: wrap;
   /* Item distribution within the remaining space (here, similar spacing between and around items) */
   justify-content: space-around;
   /* Items alignment along the cross-axis */
   align-items: flex-start;
   }
```

## 3 Conclusion :

Plus de la moitié du traffic internet se fait aujourd'hui à l'aide de téléphones portables et de tablettes, il est donc important de penser au responsive design dès le début de la conception d'un site ou d'une application. 



