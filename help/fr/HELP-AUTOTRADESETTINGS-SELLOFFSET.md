# **Offset de vente**

## Objectif : 

- Ce paramètre vous permet d'ajuster le prix de vente par un décalage fixe. 
- L'offset de vente sera soustrait du prix de vente sélectionné (peut être Ask, Bid ou Mark. Par défaut = Bid).

- La transaction sera initialement placée au prix de vente reçu dans le signal. 
- Si elle n'est pas exécutée dans les 5 secondes, la nouvelle tentative de vente se fera au prix de vente (peut être Ask, Bid ou Mark. Par défaut = Bid) moins l'offset (la valeur par défaut est de 0,05). 

## Exemple :

- Signal de vente 200 $ avec Bid à 199 $ et Ask à 201 $. 
- Si l'ordre limite initial de vente n'est pas exécuté à 200 $, la nouvelle tentative se produira à 199 $ - 0,05 = 198,95 $
