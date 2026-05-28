# TR
# Lookscout — Web Uygulaması Açılış Sayfası
Lookscout markası için tasarlanmış, saf HTML ve CSS kullanılarak geliştirilmiş tam duyarlı bir kurumsal açılış sayfası. Navigasyon, özellik kartları, blog yazıları, müşteri yorumu ve footer gibi tüm temel bölümleri kapsar.

## Canlı Önizleme

[Projeyi deploy edildikten sonra canlı önizleme.](https://dursunkokturk.github.io/Front-End-School-Responsive-Project-Lookscout-Website-App-Landing-Page/)


## Özellikler

Duyarlı Navigasyon — Mobil/tablette hamburger menü, masaüstünde tam menü çubuğu <br>
Hero Bölümü — Destekçi marka logolarıyla birlikte CTA ve açıklayıcı metin <br>
6 Özellik Kartı — İkon, başlık ve bağlantıyla iş organizasyonu, analitik, entegrasyon gibi başlıklar <br>
Koşullu Görsel — Masaüstünde farklı, mobil/tablette farklı klavye görseli (CSS active / not-active sınıfları ile) <br>
Karanlık Bölümler — #151B28 arka planlı özellikler ve footer alanları <br>
Blog Kartları — Mobilde 1, tablette 2, masaüstünde 3 sütunlu ızgara; üçüncü kart mobilden gizlenir <br>
Müşteri Yorumu — Avatar, isim ve unvanla birlikte alıntı bölümü <br>
E-posta Abonelik Formu — Güvenlik, destek ve anlaşma onay ikonlarıyla birlikte <br>
Footer — Kaynaklar ve Ürünler bağlantıları, e-posta girişi ve sosyal medya ikonları <br>
Saf HTML & CSS — JavaScript veya harici kütüphane kullanılmaz <br>


## Duyarlı Düzenler
Ekran Genişlik Öne Çıkan Değişiklikler <br>
Mobil varsayılan Tek sütun, hamburger menü <br>
Tablet> 767px2 sütunlu grid, gizli üçüncü blog kartı <br>
Masaüstü> 1109px3 sütunlu grid, tam navbar, koşullu görsel değişimi <br>

## Teknolojiler
Teknoloji Açıklama <br>
HTML5Semantik sayfa yapısı <br>
CSS3Grid, Flexbox, @media sorguları <br>
Google FontsInter yazı ailesi <br>

## Proje Yapısı
lookscout/ <br>
├── index.html <br>
└── assets/ <br>
    ├── css/ <br>
    │   └── lookscout.css <br>
    └── img/ <br>
        ├── avatars/ <br>
        │   ├── avatar.png <br>
        │   ├── avatar-man.png <br>
        │   └── avatar-woman.png <br>
        ├── icons/ <br>
        │   ├── icon-organization.png <br>
        │   ├── icon-process.png <br>
        │   ├── icon-analize.png <br>
        │   ├── icon-connection.png <br>
        │   ├── icon-integration.png <br>
        │   ├── icon-workflow.png <br>
        │   ├── icon-explere.png <br>
        │   ├── icon-bulb.png <br>
        │   ├── icon-ship.png <br>
        │   ├── icon-check.png <br>
        │   └── icon-right.png <br>
        ├── logos/ <br>
        │   ├── logo-company.png <br>
        │   ├── logo-company-dark.png <br>
        │   ├── logo-gitlab.png <br>
        │   ├── logo-slack.png <br>
        │   ├── logo-slack-black.png <br>
        │   ├── logo-netflix.png <br>
        │   ├── logo-paypal.png <br>
        │   ├── logo-paypal-blue.png <br>
        │   ├── logo-verge.png <br>
        │   ├── logo-google.png <br>
        │   ├── logo-google-letter.png <br>
        │   ├── logo-pinterest.png <br>
        │   ├── logo-mailchimp.png <br>
        │   ├── logo-facebook.png <br>
        │   ├── logo-apple.png <br>
        │   └── logo-instagram.png <br>
        ├── wall.png <br>
        ├── wall-computer.png <br>
        ├── photo-grass.png <br>
        ├── photo-radiator.png <br>
        ├── photo-desk-chair.png <br>
        ├── burger-menu.png <br>
        └── chevron-down.png <br>

## Kurulum
Proje herhangi bir bağımlılık gerektirmez. Klonladıktan sonra doğrudan tarayıcıda açabilirsiniz. <br>
bash# Repoyu klonlayın
git clone https://github.com/kullanici-adi/lookscout-landing.git

### Proje klasörüne girin
cd lookscout-landing

### index.html dosyasını tarayıcıda açın
open index.html

# Tasarım Detayları

Renk Paleti:

#2663FD — Ana mavi (navbar, hero arka planı) <br>
#437EF7 — Açık mavi (butonlar, bağlantılar) <br>
#151B28 — Koyu lacivert (karanlık bölümler, footer) <br>
#5F6D7E — Gri (gövde metni) <br>
#A5ACBA — Açık gri (karanlık arka plan metinleri) <br> <br>


Font: Inter

# EN
# Lookscout — Web App Landing Page
A fully responsive corporate landing page designed for the Lookscout brand, built with pure HTML and CSS. Covers all essential sections including navigation, feature cards, blog posts, customer testimonial, and footer. <br>

# Live Preview
[Live preview after the project is deployed.](https://dursunkokturk.github.io/Front-End-School-Responsive-Project-Lookscout-Website-App-Landing-Page/)

# Features
Responsive Navigation — Hamburger menu on mobile/tablet, full menu bar on desktop  <br>
Hero Section — CTA and descriptive text with supporting brand logos <br>
6 Feature Cards — Business organization, analytics, integrations and more, each with icon, title, and link <br>
Conditional Image — Different keyboard visuals for desktop vs. mobile/tablet (via CSS active / not-active classes) <br>
Dark Sections — Features and footer areas with #151B28 background <br>
Blog Cards — 1-column on mobile, 2 on tablet, 3 on desktop grid; third card hidden on mobile
Customer Testimonial — Quote section with avatar, name, and title <br>
Email Subscription Form — With security, support, and agreement confirmation icons <br>
Footer — Resources and Products links, email input, and social media icons <br>
Pure HTML & CSS — No JavaScript or external libraries used <br>

# Responsive Layouts
Screen Width Key Changes <br>
Mobile (default)Single column, hamburger menu <br>
Tablet > 767px2-column grid, third blog card hidden <br>
Desktop > 1109px3-column grid, full navbar, conditional image swap <br>

# Technologies
Technology Description <br>
HTML5Semantic page structure <br>
CSS3Grid, Flexbox, @media queries <br>
Google Fonts <br>
Inter typeface

# Project Structure
lookscout/ <br>
├── index.html <br>
└── assets/ <br>
    ├── css/ <br>
    │   └── lookscout.css <br>
    └── img/ <br>
        ├── avatars/ <br>
        │   ├── avatar.png <br>
        │   ├── avatar-man.png <br>
        │   └── avatar-woman.png <br>
        ├── icons/ <br>
        │   ├── icon-organization.png <br>
        │   ├── icon-process.png <br>
        │   ├── icon-analize.png <br>
        │   ├── icon-connection.png <br>
        │   ├── icon-integration.png <br>
        │   ├── icon-workflow.png <br>
        │   ├── icon-explere.png <br>
        │   ├── icon-bulb.png <br>
        │   ├── icon-ship.png <br>
        │   ├── icon-check.png <br>
        │   └── icon-right.png <br>
        ├── logos/ <br>
        │   ├── logo-company.png <br>
        │   ├── logo-company-dark.png <br>
        │   ├── logo-gitlab.png <br>
        │   ├── logo-slack.png <br>
        │   ├── logo-slack-black.png <br>
        │   ├── logo-netflix.png <br>
        │   ├── logo-paypal.png <br>
        │   ├── logo-paypal-blue.png <br>
        │   ├── logo-verge.png <br>
        │   ├── logo-google.png <br>
        │   ├── logo-google-letter.png <br>
        │   ├── logo-pinterest.png <br>
        │   ├── logo-mailchimp.png <br>
        │   ├── logo-facebook.png <br>
        │   ├── logo-apple.png <br>
        │   └── logo-instagram.png <br>
        ├── wall.png <br>
        ├── wall-computer.png <br>
        ├── photo-grass.png <br>
        ├── photo-radiator.png <br>
        ├── photo-desk-chair.png <br>
        ├── burger-menu.png <br>
        └── chevron-down.png <br>

# Installation
The project requires no dependencies. After cloning, you can open it directly in the browser.
bash# Clone the repo
git clone https://github.com/username/lookscout-landing.git

## Navigate to the project folder
cd lookscout-landing

## Open index.html in the browser
open index.html

# Design Details
Color Palette: <br>

#2663FD — Primary blue (navbar, hero background) <br>
#437EF7 — Light blue (buttons, links) <br>
#151B28 — Dark navy (dark sections, footer) <br>
#5F6D7E — Gray (body text) <br>
#A5ACBA — Light gray (text on dark backgrounds) <br>

Font: Inter
