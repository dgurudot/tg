# **Satış Ofseti**

## Amaç:

- Bu ayar, satış fiyatını sabit bir ofsetle ayarlamanıza olanak tanır.
- Satış ofseti, seçilen satış fiyatından (Satış, Alış veya Mark olabilir. Varsayılan = Alış) düşülecektir.

- İşlem, başlangıçta sinyalde alınan Satış fiyatından gerçekleştirilecektir.
- 5 saniye içinde gerçekleşmezse, tekrar deneme, ofset hariç satış fiyatından (Satış, Alış veya Mark olabilir. Varsayılan = Alış) satış yapacaktır (varsayılan değer 0,05'tir).

## Örnek:

- Satış sinyali 200$, Alış 199$ ve Satış 201$.
- Satış için ilk limit emri 200$'dan gerçekleşmezse, tekrar deneme 199$'dan gerçekleşecektir - 0,05 = 198,95$.
