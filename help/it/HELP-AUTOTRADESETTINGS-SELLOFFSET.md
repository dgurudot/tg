# **Offset di vendita**

## Scopo: 

- Questa impostazione consente di regolare il prezzo di vendita tramite offset fisso. 
- L'offset di vendita verrà sottratto dal prezzo di vendita selezionato (potrebbe essere Ask, Bid o Mark. Default = Bid).

- La transazione verrà inizialmente piazzata al prezzo di vendita ricevuto nel segnale. 
- Se non viene eseguita entro 5 secondi, il nuovo tentativo di vendita verrà effettuato al prezzo di vendita (potrebbe essere Ask, Bid o Mark. Default = Bid) meno l'offset (il valore predefinito è 0,05). 

## Esempio:

- Segnale di vendita $200 con Bid a $199 e Ask a $201. 
- Se l'ordine limite iniziale per la vendita non viene eseguito a $200, il nuovo tentativo avverrà a $199 - 0,05 = $198,95
