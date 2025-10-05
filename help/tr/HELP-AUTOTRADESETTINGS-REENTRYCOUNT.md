# **Yeniden Giriş Sayısı**

## Amaç:

- Bu ayar, piyasa emri vermeden önce ofsetle limit emrini kaç kez tekrar deneyeceğimizi ayarlamanıza olanak tanır.

## Örnek:

- Tekrar deneme sayınız 1 ise, sinyal önce sinyalde alınan fiyattan emri doldurmaya çalışır.
- Doldurulmazsa, yalnızca 1 tekrar deneme olur (tekrar deneme sayısı ayarına bağlıdır ve değiştirilebilir) ve Alış sinyali için Teklif artı ofset veya Satış sinyali için Teklif eksi ofset kullanılır.
- Tekrar deneme denemeleri tükendiğinde, piyasa emri verilir.