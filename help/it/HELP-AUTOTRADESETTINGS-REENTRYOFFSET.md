# **ReEntry Offset**

## Scopo: 

- Questa impostazione consente di regolare l'offset dal prezzo Ask (al momento dell'acquisto) o Bid (al momento della vendita). 
- La transazione verrà inizialmente piazzata al prezzo Buy ricevuto nel segnale. 
- Se non viene eseguita entro 5 secondi, il nuovo tentativo di acquisto avverrà al prezzo Ask più offset (il valore predefinito è 0,05). 
- Allo stesso modo, se viene ricevuto un segnale di vendita, la transazione verrà piazzata al prezzo Sell ricevuto nel segnale, ma se questo non viene eseguito, il nuovo tentativo avverrà al prezzo Bid meno offset (il valore predefinito è 0,05).

## Esempio:

- Segnale Buy $100 con Bid a $99 e Ask a $101. Se l'ordine limite iniziale per Buy non viene eseguito a $100, il nuovo tentativo avverrà a $101 + 0,05 = $101,05.

- Segnale Sell $200 con Bid a $199 e Ask a $201. Se l'ordine limite iniziale per la vendita non viene eseguito a $ 200, il nuovo tentativo avverrà a $ 199 - 0,05 = $ 198,95

