# **Nombre de nouvelles tentatives**

## Objectif : 

- Ce paramètre vous permet d'ajuster le nombre de fois que nous réessayerions un ordre à cours limité avec un décalage avant de finalement placer un ordre au marché.

## Exemple :

- Si votre nombre de tentatives est de 1, le signal essaiera d'abord de remplir l'ordre au prix reçu dans le signal. 
- S'il n'est pas rempli, il n'y aura qu'une seule tentative (en fonction du paramètre de nombre de tentatives et peut être modifié) et il utilisera le signal Ask plus offset pour Buy ou Bid moins offset pour Sell. 
- Une fois les tentatives de nouvelle tentative épuisées, l'ordre au marché sera placé.
