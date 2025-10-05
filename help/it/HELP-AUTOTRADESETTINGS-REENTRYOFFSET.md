# **Offset di Rientro**

## Scopo:

- Questa impostazione consente di regolare l'offset tra il prezzo Ask (al momento dell'acquisto) o Bid (al momento della vendita).
- L'operazione verrà inizialmente piazzata al prezzo di acquisto ricevuto nel segnale.
- Se non viene eseguita entro 5 secondi, il nuovo tentativo di acquisto avverrà al prezzo Ask più l'offset (il valore predefinito è 0,05).
- Analogamente, se viene ricevuto un segnale di vendita, l'operazione verrà piazzata al prezzo di vendita ricevuto nel segnale, ma se questo non viene eseguito, il nuovo tentativo avverrà al prezzo Bid meno l'offset (il valore predefinito è 0,05).

## Esempio:

- Segnale di acquisto a 100 $ con Bid a 99 $ e Ask a 101 $. Se l'ordine limite iniziale per l'acquisto non viene eseguito a 100 $, il nuovo tentativo avverrà a 101 $ + 0,05 = 101,05 $.

- Segnale di vendita a 200 $ con Bid a 199 $ e Ask a 201 $. Se l'ordine limite iniziale di vendita non viene eseguito a $ 200, il nuovo tentativo verrà effettuato a $ 199 - 0,05 = $ 198,95

