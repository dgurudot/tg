# **Décalage de réentrée**

## Objectif :

- Ce paramètre vous permet d'ajuster le décalage par rapport au prix vendeur (à l'achat) ou à l'offre (à la vente).
- La transaction sera initialement placée au prix d'achat reçu dans le signal.
- Si l'ordre n'est pas exécuté dans les 5 secondes, la nouvelle tentative d'achat se fera au prix vendeur plus l'offset (valeur par défaut : 0,05).
- De même, si un signal de vente est reçu, la transaction sera placée au prix de vente reçu dans le signal. Si l'ordre n'est pas exécuté, la nouvelle tentative se fera au prix acheteur moins l'offset (valeur par défaut : 0,05).

## Exemple :

- Signal d'achat : 100 $ avec une offre à 99 $ et une demande à 101 $. Si l'ordre limite initial d'achat n'est pas exécuté à 100 $, la nouvelle tentative se fera à 101 $ + 0,05 = 101,05 $.

- Signal de vente : 200 $ avec une offre à 199 $ et une demande à 201 $. Si l'ordre limite initial de vente n'est pas exécuté à 200 $, une nouvelle tentative aura lieu à 199 $ - 0,05 = 198,95 $.