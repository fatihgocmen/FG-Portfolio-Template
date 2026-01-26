# FG Portfolio Template

Modern, tek sayfa (one-page) portfolyo/CV web sitesi. Tamamen statik HTML/CSS/JS ile çalışır; hızlı kurulur, kolay özelleştirilir.

## İçerik

- Proje özeti
- Öne çıkanlar
- Teknoloji yığını
- Kurulum ve çalıştırma
- Proje yapısı
- Özelleştirme rehberi
- İletişim formu
- Yayınlama
- Sorun giderme
- Lisans

## Proje özeti

Bu şablon; kişisel portfolyo, özgeçmiş ve hizmet tanıtımı için tek sayfalık, görsel açıdan zengin bir arayüz sunar. Bölümler arasında yumuşak kaydırma, portfolyo filtreleme, popup galeri ve animasyonlar hazır gelir.

## Öne çıkanlar

- Bölümler: Home, About, Services, Experience, Works, Blog, Contact
- Portfolyo filtreleme (Isotope) ve sonsuz yükleme
- Görsel/video/popup içerik (Magnific Popup)
- Slider (Slick), sayaç (CounterUp), animasyon (WOW.js + Animate.css)
- Parallax katmanlar ve metin rotasyonu
- Bootstrap tabanlı, responsive düzen

## Teknoloji yığını

- HTML5, CSS3, JavaScript (jQuery)
- Bootstrap, Font Awesome, Simple Line Icons
- Isotope, Infinite Scroll, imagesLoaded
- Slick Slider, Magnific Popup, WOW.js, Animate.css, Morphext, Parallax.js
- Waypoints, CounterUp, jQuery Easing, 1000hz Bootstrap Validator

## Kurulum ve çalıştırma

Statik yapı olduğu için ek kurulum gerektirmez.

1. Doğrudan aç:

```
index.html
```

2. Yerel sunucu önerisi:

```bash
python -m http.server 8080
```

Tarayıcıda: `http://localhost:8080`

## Proje yapısı

- `index.html` – sayfa içeriği ve tüm bölümler
- `css/` – stiller (Bootstrap, animate, popup vb.)
- `js/` – davranışlar ve eklentiler (`custom.js` merkez dosyadır)
- `images/` – görseller, logo ve avatarlar
- `fonts/`, `webfonts/` – ikon ve font dosyaları

## Özelleştirme rehberi

Hızlı bir kişiselleştirme için aşağıdaki adımlar yeterlidir:

1. Metin ve içerikler
   `index.html` içinde; başlıklar, açıklamalar, butonlar ve bölüm içeriklerini güncelleyin.

2. Marka kimliği
   Logo dosyalarını değiştirin:

- `images/logo.svg`
- `images/logo2.svg`

3. Renkler ve tipografi
   `css/style.css` dosyasında renk paleti, font boyutları ve buton stillerini düzenleyin.

4. Portfolyo öğeleri
   Works bölümündeki kartları ve filtreleri güncelleyin. Filtreleme, `data-filter` değerleri üzerinden çalışır.

5. Blog bölümü
   Blog kartları statiktir. Başlık, tarih, özet ve görselleri `index.html` içinde güncelleyin.

6. Animasyon ve etkileşimler
   Genel davranışlar `js/custom.js` içinde. Slider, popup, sayaç ve scroll animasyonlarını buradan kontrol edebilirsiniz.

## İletişim formu

`js/contact.js`, form gönderimini `form/contact.php` adresine yapar. Bu repoda PHP backend yoktur. Çalıştırmak için:

- Kendi backend’inizi ekleyin, veya
- Formspree / Netlify Forms gibi bir servis entegre edin.

## Yayınlama

Statik bir site olduğu için aşağıdaki platformlarda kolayca yayınlanabilir:

- GitHub Pages
- Netlify
- Vercel
- Kendi hostinginiz

Yayınlamadan önce içerikleri ve bağlantıları güncellediğinizden emin olun.

## Sorun giderme

- Portfolyo filtreleri çalışmıyorsa sayfayı yerel sunucuda açın (dosyayı direkt açmak bazı tarayıcılarda kısıtlama yaratabilir).
- Popup veya slider çalışmıyorsa `js/` dosyalarının sayfaya doğru sırayla yüklendiğini kontrol edin.

## Lisans

Bu repo MIT lisansı ile yayınlandı.
