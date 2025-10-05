# **Offset Reintrare**

## Scop:

- Această setare vă permite să ajustați offset-ul față de prețul Cerere (în momentul Cumpărării) sau Ofertă (în momentul Vânzării).

- Tranzacția va fi plasată inițial la prețul de Cumpărare primit în semnal.

- Dacă nu este executată în 5 secunde, atunci încercarea de reluare va cumpăra la Cerere plus offset (implicit este 0,05).

- În mod similar, dacă este primit semnal de vânzare, atunci tranzacția va fi plasată la prețul de vânzare primit în semnal, dar dacă acesta nu este executat, atunci încercarea de reluare va fi la Ofertă minus offset (implicit este 0,05).

## Exemplu:

- Semnal de cumpărare 100 USD cu Ofertă la 99 USD și Ofertă la 101 USD. Dacă ordinul limită inițial pentru Cumpărare nu este executat la 100 USD, atunci încercarea de reluare va avea loc la 101 USD + 0,05 = 101,05 USD.

- Semnal de vânzare 200 USD cu Ofertă la 199 USD și Ofertă la 201 USD. Dacă ordinul limită inițial pentru Vânzare nu este executat la 200 USD, atunci se va relua încercarea la 199 USD - 0,05 = 198,95 USD.