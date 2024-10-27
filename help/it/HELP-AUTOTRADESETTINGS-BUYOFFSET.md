# **Buy Offset**

## Scopo: 

- Questa impostazione consente di regolare il prezzo di acquisto tramite offset fisso. L'offset di acquisto verrà aggiunto al prezzo di acquisto selezionato (potrebbe essere Ask, Bid o Mark. Default = Ask).

- La transazione verrà inizialmente piazzata al prezzo di acquisto ricevuto nel segnale. Se non viene eseguita entro 5 secondi, il nuovo tentativo di acquisto avverrà al prezzo di acquisto (potrebbe essere Ask, Bid o Mark. Default = Ask) più offset (il valore predefinito è 0,05). 

## Esempio:

- Segnale di acquisto $ 100 con Bid a $ 99 e Ask a $ 101. Se l'ordine limite iniziale per l'acquisto non viene eseguito a $ 100, il nuovo tentativo avverrà a $ 101 + 0,05 = $ 101,05.