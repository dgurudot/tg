# **Offset de vente**

## Objectif :

- Ce paramètre vous permet d'ajuster le prix de vente selon un décalage fixe.
- L'offset de vente sera soustrait du prix de vente sélectionné (prix de vente : demande, offre ou prix de référence. Par défaut : offre).

- La transaction sera initialement placée au prix de vente reçu dans le signal.
- Si l'ordre n'est pas exécuté dans les 5 secondes, une nouvelle tentative de vente sera effectuée au prix de vente (prix de vente : demande, offre ou prix de référence. Par défaut : offre) moins l'offset (valeur par défaut : 0,05).

## Exemple :

- Signal de vente : 200 $ avec offre à 199 $ et demande à 201 $.
- Si l'ordre limite initial de vente n'est pas exécuté à 200 $, une nouvelle tentative aura lieu à 199 $ - 0,05 = 198,95 $.