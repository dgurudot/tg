# 🔑 Gestionare API

Ecranul **Gestionare API** vă permite să gestionați cheile API TradeGrub — utilizate pentru integrări securizate cu servicii externe precum **TradingView** sau **API-uri REST personalizate**.

---

## 📋 Tabel Chei API

Toate cheile API existente sunt afișate într-un tabel simplu și ușor de citit.

### Coloane din tabel
- **Nume** → Eticheta pe care o atribuiți la crearea cheii.
- **Cheie** → Identificatorul unic utilizat pentru autentificare.
- **Permisiuni** → Definește ce poate accesa cheia (de exemplu, `TradingView`, `REST`).
- **Data creării** → Data la care a fost generată cheia.
- **Acțiuni** → Utilizați pictograma 🗑️ **Ștergere** pentru a elimina definitiv cheia API.

> ⚠️ **Important:** Ștergerea unei chei API revocă imediat accesul acesteia.

> Orice servicii conectate (cum ar fi webhook-urile TradingView) care utilizează acea cheie vor înceta să funcționeze.

---

## ➕ Crearea unei noi chei API

Atingeți butonul **„+” (Adăugare)** din colțul din dreapta sus pentru a crea o cheie nouă.
Vi se va solicita să specificați:

| Câmp | Descriere |
|--------|-------------|
| **Nume** | Un nume prietenos pentru a identifica această cheie (de exemplu, *Semnale TradingView*). |
| **Permisiuni** | Alegeți una sau ambele: - **TradingView** → Necesar pentru a primi și procesa semnalele webhook TradingView. - **REST** → Necesar pentru accesarea API-urilor REST TradeGrub. |

Odată creată, noua cheie API va apărea instantaneu în vizualizarea tabelului.

> 💡 Puteți crea mai multe chei - de exemplu, una pentru contul dvs. personal TradingView și alta pentru integrarea dvs. REST automată.

---

## 🔐 Vizibilitatea secretului API

Când este creată o nouă cheie API, un **secret** este generat și afișat **o singură dată** din motive de securitate.

Veți avea opțiunea de a-l **copia** în timpul creării — asigurați-vă că îl stocați în siguranță.

> ⚠️ **Notă:** 
> Secretul **nu poate fi vizualizat din nou ulterior**.
> Trebuie să îl salvați în siguranță, deoarece va fi necesar atunci când utilizați cheia API în integrări **TradingView** sau **REST API**.

---

## ⚙️ Cele mai bune practici

- Păstrați cheile API **private și securizate**.
- Utilizați **chei separate** pentru diferite integrări.
- Revocați (ștergeți) imediat cheile neutilizate sau compromise.
- Nu partajați niciodată cheia API public sau în capturi de ecran.

---

## 🧩 Exemple de cazuri de utilizare

| Scenariu | Permisiuni necesare |
|-----------|---------------------|
| Trimiterea semnalelor de cumpărare/vânzare TradingView | TradingView |
| Efectuarea apelurilor API REST către TradeGrub | REST |
| Configurarea automatizării tranzacționării combinate | TradingView + REST |

---

## 🆘 Sfaturi
- Atingeți pictograma **info (ℹ️)** din colțul din dreapta sus pentru ajutor rapid.
- Puteți oricând recrea o cheie dacă este ștearsă accidental.
- Acțiunile cheii API sunt sincronizate instantaneu cu contul dvs. — nu este necesară repornirea aplicației.
