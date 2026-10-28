# 🛍️ Trendyol Fiyat Takip Sistemi

Bu proje, kullanıcıların takip etmek istedikleri Trendyol ürünlerini sisteme (en fazla 10 ürün olacak şekilde) ekleyerek fiyat düşüşlerinden anında haberdar olmalarını sağlayan web tabanlı bir fiyat takip otomasyonudur.

## 🎯 Neden Böyle Bir Proje?
Trendyol gibi dev e-ticaret siteleri kullanıcılarına sürekli genel bildirimler gönderir; ancak bu kalabalığın arasında gerçekten almak istemediğimiz veya sadece belirli bir indirime girmesini beklediğimiz ürünleri gözden kaçırabiliyoruz. Sürekli gereksiz bildirimler almak yerine; **kendi seçtiğimiz, gerçekten takip etmek istediğimiz ürünlerin** indirim durumunu tek bir panelden yönetmek çok daha etkilidir. Üstelik vazgeçtiğiniz veya takip etmek istemediğiniz ürünleri sistemden kolayca silebilir, yerine yenilerini ekleyebilirsiniz.

## 📸 Ekran Görüntüleri

* Giriş ve Kayıt Ekranı:
  <img width="1282" height="573" alt="Giriş" src="https://github.com/user-attachments/assets/d3864257-e4b9-47f9-a2d0-3411f62aafaf" />

* Dashboard Ekranı:
  <img width="1284" height="572" alt="Dashboard" src="https://github.com/user-attachments/assets/b985ae5c-abfa-45a7-828c-1e36bac73ea3" />

* Mail Bildirimi:
  <img width="916" height="460" alt="İndirim" src="https://github.com/user-attachments/assets/4032fa78-7a00-445c-9aab-24eb909f8bb6" />


## ⚙️ Kurulum ve Çalıştırma 

Kaynak kodlarını indirmeden, doğrudan çalıştırılabilir versiyonu kullanmak için:
1. Bu repodaki **`run.exe`** ve **`headers.json`** dosyalarını bilgisayarınızda aynı klasöre indirin.
2. Aynı klasörün içinde **`.env`** adında bir dosya oluşturun ve içine şu bilgileri kendi mail adresinize göre girin:
   ```env
   MAIL_USERNAME=senin_mail_adresin@gmail.com
   MAIL_PASSWORD=16_hane_uygulama_sifren


## 🛠️ Kullanılan Teknolojiler
* Python (Flask, Flask-SQLAlchemy, Flask-Mail)
* BeautifulSoup & curl_cffi (Web Scraping)
* APScheduler (Arka Plan Görev Yöneticisi)
* SQLite (Veritabanı)
