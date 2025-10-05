# 🔑 Gestione API

La schermata **Gestione API** ti consente di gestire le tue chiavi API di TradeGrub, utilizzate per integrazioni sicure con servizi esterni come **TradingView** o **API REST personalizzate**.

---

## 📋 Tabella Chiavi API

Tutte le chiavi API esistenti vengono visualizzate in una tabella semplice e di facile lettura.

### Colonne della tabella
- **Nome** → L'etichetta assegnata durante la creazione della chiave.
- **Chiave** → L'identificatore univoco utilizzato per l'autenticazione.
- **Autorizzazioni** → Definisce a cosa può accedere la chiave (ad esempio, `TradingView`, `REST`).
- **Data di creazione** → La data in cui è stata generata la chiave.
- **Azioni** → Utilizza l'icona 🗑️ **Elimina** per rimuovere definitivamente la chiave API.

> ⚠️ **Importante:** L'eliminazione di una chiave API ne revoca immediatamente l'accesso.
> Tutti i servizi connessi (come i webhook di TradingView) che utilizzano quella chiave smetteranno di funzionare.

---

## ➕ Creazione di una nuova chiave API

Tocca il pulsante **"+" (Aggiungi)** nell'angolo in alto a destra per creare una nuova chiave.
Ti verrà chiesto di specificare:

| Campo | Descrizione |
|--------|----------|
| **Nome** | Un nome descrittivo per identificare questa chiave (ad esempio, *Segnali di TradingView*). |
| **Autorizzazioni** | Scegline una o entrambe: - **TradingView** → Necessaria per ricevere ed elaborare i segnali webhook di TradingView. - **REST** → Necessaria per accedere alle API REST di TradeGrub. |

Una volta creata, la nuova chiave API apparirà immediatamente nella tua vista tabella.

> 💡 Puoi creare più chiavi, ad esempio una per il tuo account personale di TradingView e un'altra per la tua integrazione REST automatizzata.

---

## 🔐 Visibilità del segreto API

Quando viene creata una nuova chiave API, viene generato un **segreto** che viene visualizzato **una sola volta** per motivi di sicurezza.
Avrai la possibilità di **copiarlo** durante la creazione: assicurati di conservarlo in modo sicuro.

> ⚠️ **Nota:**
> Il segreto **non può essere visualizzato di nuovo in seguito**.
> Devi salvarlo in modo sicuro, poiché sarà necessario quando utilizzi la chiave API nelle integrazioni di **TradingView** o **API REST**.

---

## ⚙️ Buone pratiche

- Mantieni le tue chiavi API **private e sicure**.
- Utilizza **chiavi separate** per integrazioni diverse.
- Revoca (elimina) immediatamente le chiavi non utilizzate o compromesse.
- Non condividere mai la tua chiave API pubblicamente o in screenshot.

---

## 🧩 Esempi di casi d'uso

| Scenario | Autorizzazione richiesta |
|--------------------------|---------------------|
| Invio di segnali di acquisto/vendita di TradingView | TradingView |
| Esecuzione di chiamate API REST a TradeGrub | REST |
| Configurazione combinata dell'automazione del trading | TradingView + REST |

---

## 🆘 Suggerimenti
- Tocca l'icona **info (ℹ️)** nell'angolo in alto a destra per un aiuto rapido.
- Puoi sempre ricreare una chiave se viene eliminata accidentalmente.
- Le azioni della chiave API vengono sincronizzate istantaneamente con il tuo account, senza dover riavviare l'app.