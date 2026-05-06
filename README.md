# 🌐 Community Blog
### (Topluluk Üyelerinin Paylaşım Yapabildiği Full-Stack Blog Platformu)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Ruby on Rails](https://img.shields.io/badge/Ruby%20on%20Rails-CC0000?style=flat&logo=ruby-on-rails&logoColor=white)](#)
[![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)](#)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)](#)

Bu proje, topluluk üyelerinin makaleler paylaşabildiği, fikir alışverişinde bulunabildiği ve tartışmalara katılabildiği full-stack bir web uygulamasıdır.

## 📚 İçindekiler
- [Proje Hakkında](#proje-hakkında)
- [Özellikler](#özellikler)
- [Teknoloji Yığını](#teknoloji-yığını)
- [Kurulum ve Kullanım](#kurulum-ve-kullanım)
- [Proje Yapısı](#proje-yapısı)
- [Katkıda Bulunma](#katkıda-bulunma)
- [İletişim](#iletisim)
- [Lisans](#lisans)

---

## Proje Hakkında
Community Blog, topluluk üyelerinin bir araya gelerek içerik üretebileceği, yorum yapabileceği ve birbirleriyle etkileşime geçebileceği bir platformdur. Kullanıcı kimlik doğrulama, blog yazısı yönetimi ve yorum sistemi gibi temel özellikleri barındırır.

* **Geliştirici:** Haluk Can SARIÖZ
* **Tür:** Full-Stack Web Uygulaması
* **Canlı Demo:** *(Yakında)*

---

## Özellikler
* **Kullanıcı Kimlik Doğrulama:** Güvenli kayıt ve giriş işlevselliği.
* **Blog Yazısı Yönetimi:** Kullanıcılar kendi yazılarını oluşturabilir, düzenleyebilir ve silebilir.
* **Yorum Sistemi:** Diğer yazarların gönderilerine yorum yaparak etkileşimde bulunma.
* **Responsive Tasarım:** Masaüstü ve mobil cihazlara tam uyumlu arayüz.

---

## Teknoloji Yığını
| Katman | Teknoloji |
|--------|-----------|
| **Frontend** | HTML5, CSS3, Bootstrap, JavaScript (React) |
| **Backend** | Ruby on Rails |
| **Veritabanı** | PostgreSQL / SQLite |
| **Versiyon Kontrol** | Git & GitHub |

---

## Kurulum ve Kullanım

### Ön Gereksinimler
Projeyi yerel makinenizde çalıştırmak için aşağıdaki araçların kurulu olduğundan emin olun:
* [Ruby](https://www.ruby-lang.org/en/downloads/)
* [Ruby on Rails](https://rubyonrails.org/)
* [Node.js & npm](https://nodejs.org/en/download/)
* Git

### Kurulum Adımları

**1. Depoyu klonlayın:**
```bash
git clone https://github.com/halukcansarioz/community-blog.git
cd community-blog
```

**2. Backend bağımlılıklarını yükleyin:**
```bash
bundle install
```

**3. Frontend bağımlılıklarını yükleyin:**
```bash
yarn install
# veya
npm install
```

**4. Veritabanını hazırlayın:**
```bash
rails db:create
rails db:migrate
rails db:seed
```

**5. Geliştirme sunucusunu başlatın:**
```bash
rails server
```

**6. Tarayıcınızda açın:**
`http://localhost:3000` adresine giderek uygulamayı görüntüleyin.

---

## Proje Yapısı
```text
community-blog/
├── app/
│   ├── controllers/      # Uygulama kontrolcüleri
│   ├── models/           # Veri modelleri
│   └── views/            # Görünüm şablonları
├── config/               # Uygulama yapılandırması
├── db/                   # Veritabanı migrasyonları
├── lib/                  # Yardımcı kütüphaneler
├── bin/                  # Çalıştırılabilir scriptler
├── Dockerfile            # Docker yapılandırması
├── Gemfile               # Ruby bağımlılıkları
├── package.json          # Node.js bağımlılıkları
└── README.md             # Proje dökümantasyonu
```

---

## Katkıda Bulunma
Katkılarınız, hata bildirimleriniz ve özellik istekleriniz memnuniyetle karşılanır!

1. Bu depoyu **Fork**'layın.
2. Bir **Branch** oluşturun (`git checkout -b feature/AmazingFeature`).
3. Değişikliklerinizi **Commit** edin (`git commit -m 'Ekleme: Harika özellik'`).
4. Kodlarınızı **Push**'layın (`git push origin feature/AmazingFeature`).
5. Bir **Pull Request** açın.

---

<a name="iletisim"></a>
## İletişim
**Haluk Can Sarıöz**
- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- E-posta: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

---

*Bu projeyi beğendiyseniz ⭐ vermeyi unutmayın!*

---

## Lisans
Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
