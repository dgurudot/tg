# 🔑 Gestion des API

L'écran **Gestion des API** vous permet de gérer vos clés API TradeGrub, utilisées pour des intégrations sécurisées avec des services externes comme **TradingView** ou des **API REST personnalisées**.

---
## 📋 Tableau des clés API

Toutes les clés API existantes sont affichées dans un tableau simple et lisible.

### Colonnes du tableau
- **Nom** → Le libellé que vous attribuez à la clé lors de sa création.
- **Clé** → L'identifiant unique utilisé pour l'authentification.
- **Autorisations** → Définit les droits d'accès de la clé (par exemple, `TradingView`, `REST`).
- **Date de création** → Date de génération de la clé.
- **Actions** → Utilisez l'icône 🗑️ **Supprimer** pour supprimer définitivement la clé API.

> ⚠️ **Important :** La suppression d’une clé API révoque immédiatement son accès.
> Tous les services connectés (comme les webhooks TradingView) utilisant cette clé cesseront de fonctionner.

---

## ➕ Créer une nouvelle clé API

Appuyez sur le bouton **« + » (Ajouter)** en haut à droite pour créer une nouvelle clé.
Vous serez invité à préciser :

| Champ | Description |
|--------|--------------|
| **Nom** | Un nom convivial pour identifier cette clé (par exemple, *Signaux TradingView*). |
| **Autorisations** | Choisissez l’une ou les deux : - **TradingView** → Requis pour recevoir et traiter les signaux webhook TradingView. - **REST** → Requis pour accéder aux API REST de TradeGrub. |

Une fois créée, la nouvelle clé API apparaîtra instantanément dans votre tableau.

> 💡 Vous pouvez créer plusieurs clés, par exemple une pour votre compte TradingView personnel et une autre pour votre intégration REST automatisée.

---

## 🔐 Visibilité du secret API

Lors de la création d'une nouvelle clé API, un **secret** est généré et affiché **une seule fois** pour des raisons de sécurité.

Vous aurez la possibilité de le **copier** lors de sa création ; veillez à le conserver en lieu sûr.

> ⚠️ **Remarque** :

> Le secret **ne peut pas être consulté ultérieurement**.
> Vous devez l'enregistrer de manière sécurisée, car il sera requis lors de l'utilisation de la clé API dans les intégrations **TradingView** ou **API REST**.

---

## ⚙️ Bonnes pratiques

- Gardez vos clés API **privées et sécurisées**.
- Utilisez des **clés distinctes** pour chaque intégration.
- Révoquez (supprimez) immédiatement les clés inutilisées ou compromises.
- Ne partagez jamais votre clé API publiquement ni dans des captures d'écran.

---

## 🧩 Exemples de cas d'utilisation

| Scénario | Autorisation requise |
|-----------|---------------------|
| Envoi de signaux d'achat/vente TradingView | TradingView |
| Appels d'API REST vers TradeGrub | REST |
| Configuration d'automatisation de trading combinée | TradingView + REST |

---

## 🆘 Conseils
- Appuyez sur l'icône **info (ℹ️)** en haut à droite pour obtenir une aide rapide.
- Vous pouvez toujours recréer une clé si elle a été supprimée accidentellement.
- Les actions de la clé API sont synchronisées instantanément avec votre compte ; aucun redémarrage de l'application n'est nécessaire.
