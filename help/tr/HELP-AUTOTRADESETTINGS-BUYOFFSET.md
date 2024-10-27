# **Satın Alma Ofseti**

## Amaç: 

- Bu ayar, satın alma fiyatını sabit ofsetle ayarlamanıza olanak tanır. Satın alma ofseti, seçilen satın alma fiyatına eklenecektir (Ask, Bid veya Mark olabilir. Varsayılan = Ask).

- İşlem, başlangıçta sinyalde alınan Satın Alma fiyatında gerçekleştirilecektir. 5 saniye içinde gerçekleştirilmezse, yeniden deneme girişimi satın alma fiyatından (Ask, Bid veya Mark olabilir. Varsayılan = Ask) artı ofset (varsayılan 0,05'tir) üzerinden satın alacaktır. 

## Örnek:

- Satın alma sinyali 100$, Teklif 99$ ve İstek 101$. Satın alma için ilk limit emri 100$'dan doldurulmazsa, yeniden deneme girişimi 101$ + 0,05 = 101,05$'dan gerçekleşecektir.