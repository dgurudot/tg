# **Buy Offset**

## Objectif : 

- Ce paramètre vous permet d'ajuster le prix d'achat par un décalage fixe. Le décalage d'achat sera ajouté au prix d'achat sélectionné (peut être Ask, Bid ou Mark. Par défaut = Ask).

- La transaction sera initialement placée au prix d'achat reçu dans le signal. Si elle n'est pas exécutée dans les 5 secondes, la nouvelle tentative d'achat aura lieu au prix d'achat (peut être Ask, Bid ou Mark. Par défaut = Ask) plus le décalage (la valeur par défaut est de 0,05). 

## Exemple :

- Signal d'achat 100 $ avec Bid à 99 $ et Ask à 101 $. Si l'ordre limite initial pour l'achat n'est pas exécuté à 100 $, la nouvelle tentative aura lieu à 101 $ + 0,05 = 101,05 $.
