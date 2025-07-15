# Gizlilik Politikası  
_Son güncelleme: 16 Temmuz 2025_

Bu belge, **Satırım Bilirsin** adlı Chrome uzantısının (bundan sonra **“Uzantı”** olarak anılacaktır) kullanıcı verilerini nasıl işlediğini açıklar. Uzantı yalnızca satış takibi ve ödeme hatırlatma işlevlerini yerine getirmek amacıyla tasarlanmıştır.

---

## 1. Toplanan ve İşlenen Veriler

Uzantı, satış işlemi sırasında tarayıcı sekmesinde görüntülenen şu bilgileri **yalnızca yerel olarak** depolar:

| Veri | Amaç |
| ---- | ---- |
| Müşteri adı & soyadı | Satış kaydının görüntülenmesi |
| Telefon numarası | Hızlı arama ve hatırlatma bildirimlerinde gösterim |
| Satış tutarı | Raporlama ve toplam tutar hesaplama |
| Rezervasyon bağlantısı | Kayıtlara tekrar erişim |
| Ödeme durumu, hatırlatma zamanı | Tahsilat takibi |

Bu veriler **tarayıcı dışına aktarılmaz**, geliştiriciye veya üçüncü taraflara gönderilmez.

---

## 2. İzinlerin Kullanımı

| Chrome İzni | Neden Gereklidir? |
|-------------|-------------------|
| `activeTab` | Açık sekmedeki satış bilgilerinin okunabilmesi |
| `storage` | Kayıtların ve kullanıcı ayarlarının tarayıcıda saklanması |
| `alarms` | Ödemesiz satışlar için zamanlı hatırlatma kurma |
| `notifications` | Hatırlatma süresi dolduğunda masaüstü bildirimi gösterme |
| Alan izni (yasak olmayan belirli admin URL’leri) | Uzantının yalnızca ilgili yönetim sayfalarında çalışmasını sağlama |

Uzantı başka hiçbir izin talep etmez ve reklam göstermez.

---

## 3. Veri Paylaşımı / Üçüncü Taraflar

– Geliştirici, toplanan verileri satmaz, kiralamaz ve üçüncü taraflarla paylaşmaz.  
– Uzantı, haricî sunucularla iletişim kurmaz ve uzaktan kod çalıştırmaz.

---

## 4. Veri Saklama ve Silme

1. **Manuel Silme**  
   • Uzantı popup’ındaki **“Temizle”** düğmesi, tüm satış kayıtlarını anında siler.  
2. **Uzantıyı Kaldırma**  
   • Uzantıyı Chrome’dan kaldırdığınızda tüm yerel veriler otomatik olarak silinir.  
3. **Tarayıcı Verilerini Temizleme**  
   • Chrome’un “Tarama verilerini temizle” seçeneğiyle yerel verileri silebilirsiniz.

---

## 5. Güvenlik

Veriler, Google Chrome’un sağladığı `chrome.storage.local` alanında saklanır ve tarayıcı dışından erişilemez. Geliştirici, uzantıyı düzenli olarak gözden geçirerek güvenlik güncellemeleri uygular.

---

## 6. Politika Değişiklikleri

Bu gizlilik politikasında yapılacak önemli değişiklikler, belge başındaki “Son güncelleme” tarihinin değiştirilmesiyle duyurulur. Uzantıyı kullanmaya devam etmeniz, güncellenen politikayı kabul ettiğiniz anlamına gelir.

---
