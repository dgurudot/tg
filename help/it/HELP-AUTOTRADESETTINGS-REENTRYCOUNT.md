# **Conteggio reentry**

## Scopo: 

- Questa impostazione consente di regolare il numero di volte in cui si ritenterà l'ordine limite con offset prima di piazzare definitivamente l'ordine di mercato.

## Esempio:

- Se il conteggio dei nuovi tentativi è 1, il segnale proverà prima a riempire l'ordine al prezzo ricevuto nel segnale. 
- Se non viene riempito, ci sarà solo 1 nuovo tentativo (in base all'impostazione del conteggio dei nuovi tentativi e può essere modificato) e utilizzerà il segnale Ask più offset per Buy o Bid meno offset per Sell. 
- Una volta esauriti i nuovi tentativi, verrà piazzato l'ordine di mercato.