# **Décalage de réentrée**

## Objectif : 

- Ce paramètre vous permet d'ajuster le décalage par rapport au prix Ask (au moment de l'achat) ou Bid (au moment de la vente). 
- La transaction sera initialement placée au prix d'achat reçu dans le signal. 
- Si elle n'est pas exécutée dans les 5 secondes, la nouvelle tentative d'achat se fera au prix Ask plus le décalage (la valeur par défaut est de 0,05). 
- De même, si un signal de vente est reçu, la transaction sera placée au prix de vente reçu dans le signal, mais si cela n'est pas exécuté, la nouvelle tentative se fera au prix Bid moins le décalage (la valeur par défaut est de 0,05). 

## Exemple :

- Signal d'achat 100 $ avec Bid à 99 $ et Ask à 101 $. Si l'ordre limite initial d'achat n'est pas exécuté à 100 $, la nouvelle tentative se produira à 101 $ + 0,05 = 101,05 $. 

- Signal de vente 200 $ avec Bid à 199 $ et Ask à 201 $. Si l'ordre limite initial de vente n'est pas exécuté à 200 $, une nouvelle tentative aura lieu à 199 $ - 0,05 = 198,95 $

