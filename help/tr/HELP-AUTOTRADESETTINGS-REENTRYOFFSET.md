# **Yeniden Giriş Ofseti**

## Amaç: 

- Bu ayar, ofseti Satış fiyatından (Satın Alma anında) veya Teklif fiyatından (Satış anında) ayarlamanıza olanak tanır. 
- İşlem, başlangıçta sinyalde alınan Satın Alma fiyatında gerçekleştirilecektir. 
- 5 saniye içinde gerçekleştirilmezse, yeniden deneme girişimi Teklif artı ofset üzerinden satın alacaktır (varsayılan değer 0,05'tir). 
- Benzer şekilde, satış sinyali alınırsa, işlem sinyalde alınan satış fiyatında gerçekleştirilecektir, ancak bu gerçekleştirilmezse, yeniden deneme girişimi Teklif eksi ofset üzerinden olacaktır (varsayılan değer 0,05'tir).

## Örnek:

- 99$'lık Teklif ve 101$'lık Teklif ile 100$'lık Satın Alma sinyali. Satın Alma için ilk limit emri 100$'dan doldurulmazsa, yeniden deneme girişimi 101$ + 0,05 = 101,05$'da gerçekleşecektir.

- 200$'lık satış sinyali, 199$'lık teklif ve 201$'lık talep. Satış için ilk limit emri 200$'da doldurulmazsa, o zaman yeniden deneme girişimi 199$'da gerçekleşecek - 0,05 = 198,95$

