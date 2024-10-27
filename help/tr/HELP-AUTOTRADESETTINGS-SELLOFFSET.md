# **Satış Ofseti**

## Amaç: 

- Bu ayar, satış fiyatını sabit ofsetle ayarlamanıza olanak tanır. 
- Satış ofseti, seçilen satış fiyatından çıkarılacaktır (Ask, Teklif veya Mark olabilir. Varsayılan = Teklif).

- İşlem, başlangıçta sinyalde alınan Satış fiyatından yapılacaktır. 
- 5 saniye içinde gerçekleştirilmezse, yeniden deneme girişimi satış fiyatından (Ask, Teklif veya Mark olabilir. Varsayılan = Teklif) ofset eksi satış fiyatından (varsayılan 0,05'tir) satış yapacaktır. 

## Örnek:

- Satış sinyali 200$, Teklif 199$ ve İstek 201$. 
- Satış için ilk limit emri 200$'dan doldurulmazsa, yeniden deneme girişimi 199$'dan gerçekleşecektir - 0,05 = 198,95$
