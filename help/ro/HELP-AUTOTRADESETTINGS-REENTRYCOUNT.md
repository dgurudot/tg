# **Număr de reintrări**

## Scop:

- Această setare vă permite să ajustați numărul de reîncercări ale ordinului limită cu offset înainte de a plasa în final ordinul la piață.

## Exemplu:

- Dacă numărul de reîncercări este 1, atunci semnalul va încerca mai întâi să execute ordinul la prețul primit în semnal.

- Dacă nu este executat, atunci va exista o singură reîncercare (pe baza setării numărului de reîncercări și poate fi modificată) și va utiliza Ask plus offset pentru Cumpărare sau Bid minus offset pentru semnalul de Vânzare.

- Odată ce încercările de reîncercare sunt epuizate, atunci ordinul la piață va fi plasat.
