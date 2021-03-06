# Data Visualisation : Isochrone map

## Introduction
Une carte isochrone [1] est une carte qui montre des aires délimitées par des courbes isochones, qui relient des points où un évènement se produit en même temps.
## Description
Ce type de représentation est très couramment utilisée pour représenter un temps de transport. On se donne un point de départ ainsi qu'un ensemble de moyens de transport possibles. Une courbe isochrone représente un ensemble de destinations qui sont atteintes en un temps égal en partant du point de départ en utilisant les moyens de transport donnés. Par exemple dans le cas de la marche à pied et d'un terrain plat et dégagé, les courbes isochrones sont des cercles concentriques autours de l'origine. 

## Utilisation & Exemples


<table border="0">
  <tr>
    <td>
      <img src="http://data.blog.lemonde.fr/files/2015/05/paris_madrid_blogdata.png" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      Carte isochrone représentant la durée nécessaire pour aller de Paris à une déstination avec les moyens de transport ferrés plus de la marche à pied. Source [2]
    </td>
  </tr>
</table>



<table border="0">
  <tr>
    <td>
      <img src="2 minutes de voiture.PNG" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      Le site géoportail [3] permet de calculer des cartes isochrones. Voici la zone accessible (calculée) à moins de deux minutes de voiture de l'Ecole Centrale de Lyon
    </td>
  </tr>
</table>


## Critiques
### Les points positifs
* La carte isochrone représente à la fois les distances et les temps de parcours. Dans de nombreux cas, les deux informations sont nécessaires, par exemple pour choisir son lieu de résidence en fonction de son lieu de travail. 

### Les points négatifs
* La carte isochrone est calculée, et ne tiens pas compte de la fréquence et de la fiabilité du réseau de transport. 
* La couleur est un critère qui est moins lisible qu'une distance. Si seule la lecture du temps de parcours importe, il est préférable d'utiliser une carte par anamorphose, c'est à dire qui déforme les distances de manière à ce que deux trajets d'une même durée soient représentés par une même longueur sur la carte. 

## Sources
* [1] Page wikipedia "Carte isochrone" : https://fr.wikipedia.org/wiki/Carte_isochrone
http://data.blog.lemonde.fr/2015/05/29/data-veille-jusquou-peut-on-aller-en-train-en-moins-dune-journee/
* [2] Blog "Empty Pipes" (carte basée sur l'API des transports publics Suisses (http://transport.opendata.ch/)) : http://emptypipes.org/2015/05/20/europe-isochrone-map/
* [3] Site géoportail : https://www.geoportail.gouv.fr/
