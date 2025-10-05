# 🔔 Uyarı Ayarla

**Uyarı Ayarla** özelliği, gerçek zamanlı piyasa koşullarına göre uyarılar veya otomatik emir tetikleyicileri oluşturmanıza olanak tanır.

---

## 🧭 Genel Bakış

Herhangi bir işlem sembolü (örneğin, **BTC/USDT**) için uyarılar yapılandırabilir ve **Uyarı** veya **Emir Ver** eylemini tetikleyecek **fiyat**, **hacim** veya **piyasa** değeri gibi koşullar tanımlayabilirsiniz.

---

## ⚙️ Alanlar Açıklama

| **Alan** | **Açıklama** |
|------------|-----------------|
| **Sembol** | Uyarı ayarlamak istediğiniz enstrüman veya işlem çifti (örneğin, BTC/USDT). |
| **Uyarı** | İzlenecek metriği seçin — seçenekler arasında **İŞARET**, **TEKLİF**, **SATIŞ** veya **HACİM** bulunur. |
| **Tetikleyici** | Tetikleyici koşulunu seçin — genellikle `>=`, `<=`, `==` vb. Uyarının ne zaman etkinleşeceğini belirler. |
| **Eşik** | Ulaşıldığında veya aşıldığında uyarıyı tetikleyecek sayısal değeri tanımlayın. Eşiği kademeli olarak ayarlamak için **+** veya **–** kullanın. |
| **Eylem** | Tetikleyici koşulu karşılandığında ne olacağını seçin:<br> - **Uyarı** – Uygulama içi bildirim alın.<br> - **Emir Ver** – Bir alış veya satış emrini otomatik olarak gerçekleştirin. |
| **Yan** *(Yalnızca Emir Ver için görünür)* | İşlem yönünü tanımlamak için **Alış** veya **Satış** öğesini seçin. |
| **Değer** *(Yalnızca Emir Ver için görünür)* | İşlem hacmi. Seçilen türe bağlı olarak **birim** veya **tutar** olarak temsil edilebilir. |
| **Tür** *(Yalnızca Emir Ver için görünür)* | **Birim** (hisse veya coin sayısı) veya **Tutar** (toplam para birimi değeri) arasından seçim yapın. |

---

## 🧩 İşlemler

- **Oluştur** – Uyarıyı kaydeder ve etkinleştirir.
- **İptal** – Mevcut yapılandırmayı iptal eder.

---

## 💡 İpuçları

- Üstte görüntülenen **PİYASA**, **TEKLİF**, **SATIM** ve **HACİM** değerleri, eşiğinizi hassas bir şekilde ayarlamanıza yardımcı olmak için gerçek zamanlı olarak güncellenir.
- Uyarılar, manuel olarak silinene veya tetiklenene kadar (yapılandırmanıza bağlı olarak) etkin kalır.
- Bir **Emir Ver** uyarısı ayarlarken, yeterli bakiyeniz ve işlem izinlerinizin etkin olduğundan emin olun.

---

## 🛡️ Örnek Kullanım Örnekleri

1. **Fiyat Uyarısı:**
BTC/USDT **MARK ≥ 125.000** olduğunda bir uyarı tetikleyin.

2. **Otomatik Emir:**
BTC/USDT **MARK ≤ 120.000** olduğunda, **0,5 Birim** miktarında bir **Satış Emri** verin.

---

## 🧭 Yardıma Erişim

Uygulama içi hızlı rehberlik için ekranın sağ üst köşesindeki **ℹ️ (bilgi)** simgesine dokunun.