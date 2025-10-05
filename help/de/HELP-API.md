# 🔑 API-Verwaltung

Im Bildschirm **API-Verwaltung** können Sie Ihre TradeGrub-API-Schlüssel verwalten – für sichere Integrationen mit externen Diensten wie **TradingView** oder **benutzerdefinierten REST-APIs**.

---

## 📋 API-Schlüsseltabelle

Alle vorhandenen API-Schlüssel werden in einer einfachen, übersichtlichen Tabelle angezeigt.

### Tabellenspalten
- **Name** → Die Bezeichnung, die Sie beim Erstellen des Schlüssels vergeben.
- **Schlüssel** → Die eindeutige Kennung für die Authentifizierung.
- **Berechtigungen** → Definiert, worauf der Schlüssel zugreifen kann (z. B. „TradingView“, „REST“).
- **Erstellungsdatum** → Das Datum, an dem der Schlüssel generiert wurde.
- **Aktionen** → Verwenden Sie das 🗑️ **Löschen**-Symbol, um den API-Schlüssel dauerhaft zu entfernen.

> ⚠️ **Wichtig:** Das Löschen eines API-Schlüssels entzieht ihm sofort den Zugriff.
> Alle verbundenen Dienste (wie TradingView-Webhooks), die diesen Schlüssel verwenden, funktionieren nicht mehr.

---

## ➕ Neuen API-Schlüssel erstellen

Tippen Sie oben rechts auf die Schaltfläche **„+“ (Hinzufügen)**, um einen neuen Schlüssel zu erstellen.

Sie werden aufgefordert, Folgendes anzugeben:

| Feld | Beschreibung |
|--------|-----------|
| **Name** | Ein benutzerfreundlicher Name zur Identifizierung dieses Schlüssels (z. B. *TradingView-Signale*). |
| **Berechtigungen** | Wählen Sie eine oder beide Optionen: - **TradingView** → Erforderlich zum Empfangen und Verarbeiten von TradingView-Webhook-Signalen. - **REST** → Erforderlich für den Zugriff auf TradeGrub-REST-APIs. |

Nach der Erstellung wird der neue API-Schlüssel sofort in Ihrer Tabellenansicht angezeigt.

> 💡 Sie können mehrere Schlüssel erstellen – zum Beispiel einen für Ihr persönliches TradingView-Konto und einen weiteren für Ihre automatisierte REST-Integration.

---

## 🔐 Sichtbarkeit des API-Schlüssels

Wenn ein neuer API-Schlüssel erstellt wird, wird aus Sicherheitsgründen ein **Schlüssel** generiert und **nur einmal** angezeigt.

Sie haben die Möglichkeit, ihn während der Erstellung zu **kopieren** – bewahren Sie ihn bitte sicher auf.

> ⚠️ **Hinweis:**
> Der Schlüssel **kann später nicht mehr angezeigt werden**.
> Sie müssen ihn sicher speichern, da er für die Verwendung des API-Schlüssels in **TradingView**- oder **REST-API**-Integrationen benötigt wird.

---

## ⚙️ Best Practices

- Halten Sie Ihre API-Schlüssel **privat und sicher**.
- Verwenden Sie **separate Schlüssel** für verschiedene Integrationen.
- Löschen Sie nicht verwendete oder kompromittierte Schlüssel sofort.
- Geben Sie Ihren API-Schlüssel niemals öffentlich oder in Screenshots weiter.

---

## 🧩 Anwendungsbeispiele

| Szenario | Erforderliche Berechtigung |
|-----------|---------------------|
| TradingView Kauf-/Verkaufssignale senden | TradingView |
| REST-API-Aufrufe an TradeGrub durchführen | REST |
| Kombinierte Handelsautomatisierung einrichten | TradingView + REST |

---

## 🆘 Tipps
- Tippen Sie oben rechts auf das **Infosymbol (ℹ️)**, um schnelle Hilfe zu erhalten.
- Sie können einen Schlüssel jederzeit neu erstellen, falls er versehentlich gelöscht wurde.
- API-Schlüsselaktionen werden sofort mit Ihrem Konto synchronisiert – kein Neustart der App erforderlich.
