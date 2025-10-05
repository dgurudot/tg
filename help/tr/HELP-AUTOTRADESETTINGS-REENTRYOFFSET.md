# **Yeniden Giriş Ofseti**

## Amaç:

- Bu ayar, Satış Fiyatı (Alış anında) veya Alış (Satış anında) arasındaki farkı ayarlamanıza olanak tanır.
- İşlem, başlangıçta sinyalde alınan Alış fiyatından gerçekleştirilecektir.
- 5 saniye içinde gerçekleşmezse, tekrar deneme, Satış fiyatı artı ofset üzerinden alış yapacaktır (varsayılan değer 0,05'tir).
- Benzer şekilde, satış sinyali alınırsa, işlem, sinyalde alınan satış fiyatından gerçekleştirilecektir, ancak bu gerçekleşmezse, tekrar deneme, Teklif eksi ofset üzerinden yapılacaktır (varsayılan değer 0,05'tir).

## Örnek:

- Alış sinyali 100$, Alış fiyatı 99$ ve Satış fiyatı 101$. Alış için ilk limit emri 100$'dan gerçekleştirilmezse, tekrar deneme 101$ + 0,05 = 101,05$'dan gerçekleşecektir.

- Satış sinyali 200$, Alış 199$ ve Satış 201$. Satış için ilk limit emri 200$'dan doldurulmazsa, 199$ - 0,05 = 198,95$'dan tekrar deneme yapılacaktır.

