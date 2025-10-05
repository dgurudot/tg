# 🔑 API Yönetimi

**API Yönetimi** ekranı, **TradingView** veya **özel REST API'leri** gibi harici servislerle güvenli entegrasyonlar için kullanılan TradeGrub API anahtarlarınızı yönetmenize olanak tanır.

---

## 📋 API Anahtarları Tablosu

Mevcut tüm API anahtarları basit ve okunması kolay bir tabloda görüntülenir.

### Tablo Sütunları
- **Ad** → Anahtarı oluştururken atadığınız etiket.
- **Anahtar** → Kimlik doğrulama için kullanılan benzersiz tanımlayıcı.
- **İzinler** → Anahtarın erişebileceği öğeleri tanımlar (örneğin, `TradingView`, `REST`).
- **Oluşturulma Tarihi** → Anahtarın oluşturulduğu tarih.
- **Eylemler** → API anahtarını kalıcı olarak kaldırmak için 🗑️ **Sil** simgesini kullanın.

> ⚠️ **Önemli:** Bir API anahtarını silmek, erişimini anında iptal eder.

> Bu anahtarı kullanan tüm bağlı hizmetler (TradingView webhook'ları gibi) çalışmayı durduracaktır.

---

## ➕ Yeni Bir API Anahtarı Oluşturma

Yeni bir anahtar oluşturmak için sağ üst köşedeki **“+” (Ekle)** düğmesine dokunun.
Şunları belirtmeniz istenecektir:

| Alan | Açıklama |
|--------|--------------|
| **Ad** | Bu anahtarı tanımlamak için kolay bir ad (örneğin, *TradingView Sinyalleri*). |
| **İzinler** | Birini veya her ikisini seçin: - **TradingView** → TradingView webhook sinyallerini almak ve işlemek için gereklidir. - **REST** → TradeGrub REST API'lerine erişmek için gereklidir. |

Yeni API anahtarı oluşturulduktan sonra, tablo görünümünüzde anında görünecektir.

> 💡 Birden fazla anahtar oluşturabilirsiniz; örneğin, kişisel TradingView hesabınız için bir anahtar ve otomatik REST entegrasyonunuz için bir anahtar.

---

## 🔐 API Gizli Bilgisi Görünürlüğü

Yeni bir API anahtarı oluşturulduğunda, güvenlik nedeniyle bir **gizli bilgi** oluşturulur ve **yalnızca bir kez** görüntülenir.

Oluşturma sırasında **kopyalama** seçeneğiniz olacak; güvenli bir yerde sakladığınızdan emin olun.

> ⚠️ **Not:** 
> Gizli bilgi **daha sonra tekrar görüntülenemez**.
> **TradingView** veya **REST API** entegrasyonlarında API anahtarını kullanırken gerekli olacağından, güvenli bir şekilde kaydetmelisiniz.

---

## ⚙️ En İyi Uygulamalar

- API anahtarlarınızı **gizli ve güvenli** tutun.
- Farklı entegrasyonlar için **ayrı anahtarlar** kullanın.
- Kullanılmayan veya güvenliği ihlal edilmiş anahtarları hemen iptal edin (silin). - API anahtarınızı asla herkese açık olarak veya ekran görüntülerinde paylaşmayın.

---

## 🧩 Örnek Kullanım Örnekleri

| Senaryo | Gerekli İzinler |
|-----------|----------------------|
| TradingView alım/satım sinyalleri gönderme | TradingView |
| TradeGrub'a REST API çağrıları yapma | REST |
| Birleşik işlem otomasyonu kurulumu | TradingView + REST |

---

## 🆘 İpuçları
- Hızlı yardım için sağ üst köşedeki **bilgi (ℹ️)** simgesine dokunun.
- Yanlışlıkla silinen bir anahtarı istediğiniz zaman yeniden oluşturabilirsiniz.
- API anahtarı işlemleri hesabınızla anında senkronize edilir; uygulamayı yeniden başlatmanız gerekmez.