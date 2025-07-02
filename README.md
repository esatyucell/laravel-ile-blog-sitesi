# 📰 Laravel Blog Projesi

Laravel tabanlı geliştirilmiş bir blog yönetim sistemidir. Basit ve kullanışlı bir arayüz ile yazı, kategori ve kullanıcı yönetimini sağlamaktadır.

---

## 📸 Ekran Görüntüleri

![Giriş Sayfası](img/laravelblogss.png)

---


![Kayıt Sayfası](img/laravelblogss2.png)

---

![Admin Paneli](img/laravelblogss3.png)

---


![Yazı Ekle](img/laravelblogss4.png)

---


![Yazı Listesi](img/laravelblogss5.png)

---

![Kategori Yönetimi](img/laravelblogss6.png)

---

## ⚙️ Kurulum Adımları

```bash
git clone https://github.com/kullaniciadi/laravel-blog-master.git
cd laravel-blog-master

composer install
npm install && npm run dev

cp .env.example .env
php artisan key:generate

php artisan migrate --seed
php artisan serve
