# **Décalage d'achat**

## Objectif :

- Ce paramètre vous permet d'ajuster le prix d'achat selon un décalage fixe. Le décalage d'achat sera ajouté au prix d'achat sélectionné (prix d'achat, prix d'offre ou prix de référence, par défaut : prix de vente).

- La transaction sera initialement placée au prix d'achat reçu dans le signal. Si elle n'est pas exécutée dans les 5 secondes, une nouvelle tentative d'achat sera effectuée au prix d'achat (prix d'achat, prix d'offre ou prix de référence, par défaut : prix de vente) plus le décalage (par défaut : 0,05).

## Exemple :

- Signal d'achat à 100 $ avec un prix d'offre à 99 $ et un prix de vente à 101 $. Si l'ordre limite initial d'achat n'est pas exécuté à 100 $, une nouvelle tentative sera effectuée à 101 $ + 0,05 = 101,05 $.