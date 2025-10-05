# **Satın Alma Ofseti**

## Amaç:

- Bu ayar, satın alma fiyatını sabit bir ofsetle ayarlamanıza olanak tanır. Satın alma ofseti, seçilen satın alma fiyatına eklenir (Satış, Alış veya Mark olabilir. Varsayılan = Satış).

- İşlem, başlangıçta sinyalde alınan Satın Alma fiyatından yapılır. 5 saniye içinde gerçekleşmezse, tekrar deneme, satın alma fiyatından (Satış, Alış veya Mark olabilir. Varsayılan = Satış) ve ofsetten (varsayılan 0,05) satın alma işlemi gerçekleştirir.

## Örnek:

- Satın alma sinyali 100$, Alış fiyatı 99$ ve Satış fiyatı 101$. Satın alma için ilk limit emri 100$'dan gerçekleşmezse, tekrar deneme 101$ + 0,05 = 101,05$'dan gerçekleşir.