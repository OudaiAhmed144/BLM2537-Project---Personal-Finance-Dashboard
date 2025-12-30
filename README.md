# Kişisel Finans Panosu (Personal Finance Dashboard)

Kişisel Finans Panosu, kullanıcıların harcamalarını takip etmelerine ve harcama verilerini açık ve etkileşimli grafikler aracılığıyla görselleştirmelerine yardımcı olmak için tasarlanmış bir web uygulamasıdır.

---

## Projenin Çalıştırılması

1. Depoyu indirin veya klonlayın
2. `nhome.html` dosyasını herhangi bir modern web tarayıcısında açın
3. Uygulama ek bir kurulum gerektirmeden yerel olarak çalışır

---

## Özellikler ve İşlevler

### Profil Yönetimi
- Kullanıcılar en fazla **10 profil** oluşturabilir
- Her profil istenilen şekilde adlandırılabilir
- Tüm profiller sol tarafta **onay kutuları (checkbox)** ile listelenir
- Kullanıcılar bir veya birden fazla profil seçebilir
- Seçilen profillere ait harcamalar harcama tablosunda görüntülenir

**Profil Yönetimi** sayfasında kullanıcılar:
- Profilin **son güncellenme zamanı** gibi bilgileri görüntüleyebilir
- İlgili profilin yanındaki silme butonu ile profilleri silebilir

---

### Harcama Yönetimi
- Ana sayfada bir **harcama tablosu** bulunmaktadır
- Kullanıcılar:
  - Yeni harcama ekleyebilir
  - Mevcut harcamaları düzenleyebilir
  - Harcamaları tablodan doğrudan silebilir
- Harcama eklerken, harcamanın hangi profile ait olduğu seçilir
- Herhangi bir değişiklikten sonra tablo **anında güncellenir**

---

### Veri Dışa Aktarma
- Harcama tablosunun üzerinde bir **Export As a xlsx File** butonu bulunmaktadır
- Görüntülenen tüm veriler **XLSX (Excel)** dosyası olarak dışa aktarılabilir

---

### Veri Analizi ve Görselleştirme
**Analiz** sayfası, seçili profillere göre finansal analizler sunar.

> Not: Profil seçimi değiştirildiğinde grafiklerin güncellenmesi için sayfanın yeniden yüklenmesi gerekmektedir.

Sunulan grafikler ve istatistikler:
- Kategori bazında toplam harcamaları gösteren **pasta grafik**
- En çok harcama yapılan ilk 5 kategoriyi gösteren **yatay çubuk grafik**
- **Toplam harcama** özeti
- En eski ve en yeni tarihler arasına göre hesaplanan **günlük ortalama harcama**
- Haftanın günlerine göre toplam harcamaları gösteren **çubuk grafik**
- Tarihlere göre toplam harcamayı gösteren **çizgi grafik**

---

## Veri Saklama ve Kalıcılık

- Tüm uygulama verileri **localStorage** kullanılarak saklanmaktadır
- Saklanan veriler:
  - Kullanıcı profilleri
  - Seçili profiller
  - Harcama kayıtları
- Tarayıcı yenilense veya kapatılsa bile veriler **kalıcı olarak korunur**

---

## Kullanılan Teknolojiler

- **HTML5**
- **CSS**
- **JavaScript**
- Veri görselleştirme için **Chart.js**
- Excel’e veri aktarma için **SheetJS (XLSX)**
- Sayısal değer animasyonları için **CountUp.js**
- DOM manipülasyonu ve olay yönetimi için **jQuery**

---

## Geliştirici

- İsim: **OUDIA THARIK ALMUNTASIR AHMED**
- GitHub: **https://github.com/OudaiAhmed144**

---

## Notlar ve Kısıtlamalar

- Maksimum profil sayısı **10** ile sınırlıdır
- Profil seçimi değiştirildikten sonra grafiklerin güncellenmesi için sayfanın yeniden yüklenmesi gerekir
- Uygulamanın çalışabilmesi için **JavaScript etkin olmalıdır**
