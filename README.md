<p align="center">
  <img src="https://i.hizliresim.com/9jpe8xo.jpg" alt="LeiCAD Logo" width="150"/>
</p>

<h1 align="center">LeiCAD - Web Tabanlı CAD Uygulaması (Beta)</h1>

<p align="center">
  <strong>Netcad benzeri bir kullanıcı deneyimi sunmayı hedefleyen, modern web teknolojileriyle geliştirilmiş 2D CAD çizim ve düzenleme aracı.</strong>
</p>

<p align="center">
  <a href="#-proje-hakkında">Proje Hakkında</a> •
  <a href="#-temel-özellikler">Temel Özellikler</a> •
  <a href="#-teknolojiler">Teknolojiler</a> •
  <a href="#-beta-süreci">Beta Süreci</a> •
  <a href="#-nasıl-başlarım">Nasıl Başlarım?</a> •
  <a href="#-gelecek-planları">Gelecek Planları</a> •
  <a href="#-katkıda-bulunma">Katkıda Bulunma</a> •
  <a href="#-lisans">Lisans</a>
</p>

---

## 🚀 Proje Hakkında

**LeiCAD**, coğrafi bilgi sistemleri (CBS) ve bilgisayar destekli tasarım (CAD) alanlarında çalışan profesyoneller ve öğrenciler için kullanıcı dostu, erişilebilir ve güçlü bir 2D çizim aracı sunmayı amaçlamaktadır. Geleneksel masaüstü CAD yazılımlarının temel işlevlerini web tarayıcınıza taşıyarak, platform bağımsız bir çalışma ortamı sağlamayı hedefler.

Bu proje, özellikle Netcad gibi yazılımlara aşina olan kullanıcıların kolayca adapte olabileceği bir arayüz ve iş akışı sunmaya odaklanmıştır. Ancak modern web teknolojilerinin getirdiği esneklik ve performans avantajlarından da sonuna kadar faydalanmaktadır.

**Şu anda Beta aşamasındayız!** Bu, uygulamanın hala aktif geliştirme altında olduğu ve bazı hatalar veya eksik özellikler içerebileceği anlamına gelir. Geri bildirimleriniz, LeiCAD'i daha iyi bir araç haline getirmemizde kritik rol oynayacaktır.

## ✨ Temel Özellikler (Beta Sürümü)

LeiCAD'in mevcut beta sürümünde aşağıdaki temel özellikleri deneyimleyebilirsiniz:

* **🗺️ İnteraktif Harita Arayüzü:**
  * Farklı altlık harita seçenekleri (Google Uydu, OpenStreetMap, OpenTopoMap, CartoDB vb.)
  * Haritayı açma/kapama ve kareli çizim arka planı.
  * Yakınlaşma/Uzaklaşma ve koordinat gösterimi.
* **✏️ Çizim Araçları:**
  * **Nokta (Özel):** Numaralı ve stilize edilebilir noktalar ekleme.
  * **Çizgi:** İki nokta arasında düz çizgiler oluşturma.
  * **Çoklu Doğru (Polyline):** Birden fazla segmentten oluşan çizgiler çizme.
  * **Alan (Polygon):** Kapalı alanlar oluşturma.
  * **Daire:** Merkez ve yarıçap belirleyerek daireler çizme.
  * **Yay:** Üç nokta (başlangıç, bitiş, kontrol) ile yaylar çizme.
  * **Yazı:** Harita üzerine metin ekleme (font, boyut, açı ve stil seçenekleriyle).
* **📐 Düzenleme ve Manipülasyon Araçları:**
  * **Katman Yöneticisi:**
    * Yeni katman oluşturma, silme.
    * Katman özelliklerini düzenleme (isim, çizgi/dolgu rengi, çizgi kalınlığı, dolgu opaklığı, katı dolgu, nokta numarası gösterimi, kilit, yazdırılabilirlik).
    * Katman görünürlüğünü açma/kapama.
    * Aktif katman seçimi.
  * **Nokta Editörü:** Seçili katmanlardaki noktaları tablo formatında görüntüleme, düzenleme ve silme.
  * **Silgi Aracı:** Objeleri tekli, çoklu veya alanla seçerek silme.
  * **Taşıma Aracı:** Seçilen objeleri referans noktası belirleyerek taşıma (tekli, çoklu, alanla seçim modları).
  * **Obje Düzenleme:** Tıklanan objenin (nokta, çizgi, alan, daire, yazı vb.) geometrik ve stil özelliklerini detaylı olarak düzenleme.
  * **Obje Sorgulama:** Tıklanan objenin tür, katman, uzunluk, alan gibi temel bilgilerini görüntüleme.
* **⚙️ Yardımcı Araçlar:**
  * **Cetvel:** Harita üzerinde mesafe ölçümü yapma.
  * **Yakalama Modları (Snap):** Çizim yaparken mevcut objelerin uç noktalarına, orta noktalarına veya en yakın noktalarına otomatik yakalanma.
  * **Geri Al / İleri Al (Undo/Redo):** Yapılan işlemleri geri alma ve ileri alma.
* **🎨 Kullanıcı Arayüzü:**
  * Modern, sezgisel ve Netcad benzeri bir araç çubuğu ve panel düzeni.
  * Durum çubuğunda anlık bilgi gösterimi.
  * Dinamik açılır paneller ve diyaloglar.
  * Hoş geldin ve yükleme animasyonları.

## 💻 Teknolojiler

LeiCAD, aşağıdaki temel teknolojiler ve kütüphaneler kullanılarak geliştirilmiştir:

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+ Modüller)
* **Haritalama Kütüphanesi:** [Leaflet.js](https://leafletjs.com/)
* **Geometrik Analizler:** [Turf.js](https://turfjs.org/) (Alanla seçim, özellik hesaplamaları vb.)
* **Yardımcı Kütüphaneler:**
  * [Leaflet.GeometryUtil](https://github.com/makinacorpus/Leaflet.GeometryUtil) (Yakalama modları gibi geometrik işlemler için)
  * [Font Awesome](https://fontawesome.com/) (İkonlar için)
  * [Spectrum Color Picker](https://seballot.github.io/spectrum/) (Renk seçici için jQuery bağımlılığı ile)
  * [jQuery](https://jquery.com/) (Spectrum için)
* **Geliştirme Ortamı:** Modern tarayıcılar, VS Code (veya tercih edilen IDE)

## 🧪 Beta Süreci

LeiCAD şu anda **aktif beta** sürecindedir. Bu, uygulamanın temel işlevlerinin çalıştığı ancak hala geliştirme ve iyileştirme aşamasında olduğu anlamına gelir. Beta sürecinde şunlarla karşılaşabilirsiniz:

* Bazı **hatalar** veya beklenmedik davranışlar.
* **Eksik özellikler** veya tam olarak geliştirilmemiş fonksiyonlar.
* Performansla ilgili iyileştirme alanları.

**Geri Bildirimleriniz Çok Değerli!**
Bu süreçte sizden ricamız, uygulamayı kullanırken karşılaştığınız sorunları, hataları, eksik gördüğünüz özellikleri veya genel kullanıcı deneyimi hakkındaki düşüncelerinizi bizimle paylaşmanızdır. Geri bildirimleriniz, LeiCAD'i daha stabil, kullanışlı ve güçlü bir araç haline getirmemize yardımcı olacaktır.

Geri bildirimlerinizi GitHub Issues üzerinden veya doğrudan [ejder.erdgn@gmail.com](mailto:proje_eposta_adresi@example.com) adresine iletebilirsiniz.

## 🚀 Nasıl Başlarım?  (Çok Yakında !)

LeiCAD'i yerel makinenizde çalıştırmak oldukça basittir:

1. **Repoyu Klonlayın:**

   ```bash
   git clone https://github.com/kullanici_adiniz/leicad.git
   cd leicad
   ```
2. **Yerel Bir Sunucu Başlatın:**
   Proje dosyalarını doğrudan tarayıcıda (`file:///`) açmak, JavaScript modülleri ve bazı API istekleri nedeniyle sorunlara yol açabilir. Bu yüzden yerel bir HTTP sunucusu kullanmanız önerilir.

   * Eğer Python yüklüyse:
     ```bash
     python -m http.server 8000
     ```

     Ardından tarayıcınızda `http://localhost:8000` adresine gidin.
   * Node.js ve `live-server` (veya benzeri) kullanıyorsanız:
     ```bash
     npm install -g live-server
     live-server
     ```

     `live-server` genellikle otomatik olarak tarayıcıda bir sekme açacaktır.
   * VS Code kullanıyorsanız, "Live Server" eklentisini kurup `index.html` dosyasına sağ tıklayarak "Open with Live Server" seçeneğini kullanabilirsiniz.
3. **Kullanmaya Başlayın!**
   Uygulama tarayıcınızda açıldığında, arayüzü keşfetmeye ve özellikleri denemeye başlayabilirsiniz.

## 📅 Gelecek Planları

LeiCAD için planladığımız bazı önemli geliştirmeler ve özellikler şunlardır:

* **Gelişmiş Düzenleme Araçları:**
  * Köşe ekleme/silme/kaydırma.
  * Objeleri bölme, birleştirme, kırma.
  * Paralel oluşturma, ofsetleme.
  * Döndürme, ölçekleme.
* **Özellik Hesaplamaları:**
  * Seçili çizgilerin toplam uzunluğu.
  * Seçili alanların toplam alanı ve çevresi.
* **Veri Import/Export:**
  * GeoJSON, KML, DXF (basit) formatlarında veri alma ve verme.
* **Daha Fazla Analiz Aracı:**
  * Basit tampon (buffer) analizi.
  * Kesişim analizleri.
* **Özelleştirme ve Ayarlar:**
  * Kullanıcı arayüzü tema seçenekleri.
  * Kısayol tuşu özelleştirmeleri.
* **Performans İyileştirmeleri:** Özellikle çok sayıda obje ile çalışırken.
* **Mobil Uyumluluk:** Dokunmatik cihazlarda temel görüntüleme ve sorgulama.
* **Detaylı Dokümantasyon ve Kullanım Kılavuzu.**

## 🤝 Katkıda Bulunma

LeiCAD açık kaynaklı bir projedir ve topluluk katkılarına açıktır! Eğer projeye katkıda bulunmak isterseniz, aşağıdaki yolları izleyebilirsiniz:

1. **Hata Bildirimi:** Karşılaştığınız hataları lütfen GitHub [Issues](https://github.com/kullanici_adiniz/leicad/issues) bölümünde detaylı bir şekilde bildirin.
2. **Özellik Talebi:** Eklenmesini istediğiniz özellikleri veya iyileştirme önerilerinizi Issues bölümünde paylaşın.
3. **Kod Katkısı:**
   * Repoyu fork'layın.
   * Yeni bir özellik veya hata düzeltmesi için kendi branch'inizi oluşturun (`git checkout -b ozellik/yeni-bir-ozellik`).
   * Değişikliklerinizi commit'leyin (`git commit -am 'Yeni bir özellik eklendi'`).
   * Branch'inizi push'layın (`git push origin ozellik/yeni-bir-ozellik`).
   * Bir Pull Request oluşturun.

Tüm katkılar değerlidir ve takdirle karşılanacaktır!

## 📄 Lisans

Bu proje [MIT Lisansı](https://opensource.org/licenses/MIT) altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakınız.

---

<p align="center">
  <em>LeiCAD ile çizim keyfini web'e taşıyın!</em>
</p>
