# Ormanİzin — Test & Prototip Sayfası

Bu proje, tek sayfalık (single-page) modern ve etkileşimli bir test web sitesidir.

## 🚀 Özellikler

- **Modern Tasarım:** Tailwind CSS ile hazırlanmış, duyarlı (responsive) ve estetik kullanıcı arayüzü.
- **Karanlık / Aydınlık Mod:** LocalStorage destekli, sistem temasını otomatik algılayan mod geçişi.
- **Etkileşimli Test Bileşenleri:**
  - **Toast Bildirim Motoru:** Başarılı, uyarı, hata ve bilgi bildirimleri.
  - **Modal / Pop-up Testi:** Odak kilitleme ve ESC tuşu desteği olan modal pencereler.
  - **Asenkron API Simülatörü:** Gecikmeli mock fetch isteği ve JSON ayrıştırma önizlemesi.
  - **Form Doğrulama:** Örnek izin formu ve girdi denetimleri.
  - **Canlı Sayaç:** DOM ve JavaScript durum yönetimi testi.
  - **Akordeon:** Açılır/kapanır SSS alanı.
- **Sistem ve Tarayıcı Tanılamaları:**
  - Ekran çözünürlüğü ve DPR oranı (canlı yeniden boyutlandırma dinleyicisi ile).
  - Tarayıcı motoru ve platform tespiti.
  - Çevrimiçi/Çevrimdışı ağ bağlantı denetimi.
  - LocalStorage / SessionStorage / Çerez kullanılabilirlik testleri.
  - CPU çekirdek sayısı ve donanım ipuçları.

## 💻 Nasıl Çalıştırılır?

Herhangi bir sunucu kurulumu ya da derleme aracı gerekmez:

1. `index.html` dosyasına çift tıklayarak doğrudan tarayıcınızda açabilirsiniz.
2. Veya yerel bir geliştirme sunucusu başlatmak isterseniz:
   ```bash
   # Python ile
   python -m http.server 8000

   # veya Node.js / npx ile
   npx serve .
   ```
   Ardından tarayıcınızda `http://localhost:8000` adresine gidin.
