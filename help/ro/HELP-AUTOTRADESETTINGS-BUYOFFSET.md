# **Compensare Cumpărare**

## Scop:

- Această setare vă permite să ajustați prețul de cumpărare printr-o compensare fixă. Compensarea cumpărării va fi adăugată la prețul de cumpărare selectat (poate fi Cerere, Ofertă sau Preț. Implicit = Cerere).

- Tranzacția va fi plasată inițial la prețul de cumpărare primit în semnal. Dacă nu este executată în 5 secunde, atunci o nouă încercare va cumpăra la prețul de cumpărare (poate fi Cerere, Ofertă sau Preț. Implicit = Cerere) plus compensarea (implicit este 0,05).

## Exemplu:

- Semnal de cumpărare 100 USD cu Ofertă la 99 USD și Cerere la 101 USD. Dacă ordinul limită inițial pentru Cumpărare nu este executat la 100 USD, atunci o nouă încercare va avea loc la 101 USD + 0,05 = 101,05 USD.

