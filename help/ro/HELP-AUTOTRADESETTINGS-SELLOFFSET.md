# **Compensație Vânzare**

## Scop:

- Această setare vă permite să ajustați prețul de vânzare printr-o compensație fixă.
- Compensația vânzării va fi scăzută din prețul de vânzare selectat (poate fi Ask, Bid sau Mark. Implicit = Bid).

- Tranzacția va fi plasată inițial la prețul de vânzare primit în semnal.

- Dacă nu este executată în 5 secunde, atunci o nouă încercare va vinde la prețul de vânzare (poate fi Ask, Bid sau Mark. Implicit = Bid) minus compensația (implicit este 0,05).

## Exemplu:

- Semnal de vânzare 200 USD cu Bid la 199 USD și Ask la 201 USD.

- Dacă ordinul limită inițial pentru Vânzare nu este executat la 200 USD, atunci o nouă încercare va avea loc la 199 USD - 0,05 = 198,95 USD
