# **Offset di vendita**

## Scopo:

- Questa impostazione consente di regolare il prezzo di vendita in base a un offset fisso.
- L'offset di vendita verrà sottratto dal prezzo di vendita selezionato (può essere Ask, Bid o Mark. Predefinito = Bid).

- L'operazione verrà inizialmente piazzata al prezzo di vendita ricevuto nel segnale.
- Se non viene eseguita entro 5 secondi, il nuovo tentativo di vendita verrà effettuato al prezzo di vendita (può essere Ask, Bid o Mark. Predefinito = Bid) meno l'offset (il valore predefinito è 0,05).

## Esempio:

- Segnale di vendita $200 con Bid a $199 e Ask a $201.
- Se l'ordine limite iniziale per la vendita non viene eseguito a $200, il nuovo tentativo avverrà a $199 - 0,05 = $198,95