# **Conteggio Rientri**

## Scopo:

- Questa impostazione consente di regolare il numero di volte in cui si ripete l'ordine limite con offset prima di piazzare definitivamente l'ordine a mercato.

## Esempio:

- Se il conteggio dei tentativi è 1, il segnale tenterà prima di eseguire l'ordine al prezzo ricevuto nel segnale.
- Se l'ordine non viene eseguito, ci sarà un solo tentativo (in base all'impostazione del conteggio dei tentativi, modificabile) e utilizzerà il prezzo Ask più offset per il segnale di Acquisto o il prezzo Bid meno offset per il segnale di Vendita.
- Una volta esauriti i tentativi, verrà piazzato l'ordine a mercato.