# **Nombre de nouvelles tentatives**

## Objectif :

- Ce paramètre vous permet de définir le nombre de tentatives de réexécution d'un ordre à cours limité avec décalage avant de placer définitivement un ordre au marché.

## Exemple :

- Si le nombre de tentatives est de 1, le signal tentera d'abord d'exécuter l'ordre au prix reçu.
- En cas d'échec, une seule tentative sera effectuée (selon le nombre de tentatives défini et modifiable) et le signal utilisera le prix Ask plus le décalage pour l'achat ou le prix Bid moins le décalage pour la vente.
- Une fois le nombre de tentatives épuisé, l'ordre au marché sera placé.