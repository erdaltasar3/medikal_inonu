# 🧠 HealthAI - Yapay Zeka ve Sağlık Teknolojileri Platformu

![](https://img.shields.io/badge/Django-4.2.22-green.svg)
![](https://img.shields.io/badge/Bootstrap-5-blue.svg)
![](https://img.shields.io/badge/PostgreSQL-Database-blue.svg)
![](https://img.shields.io/badge/Celery-5.3.4-brightgreen.svg)
![](https://img.shields.io/badge/RabbitMQ-Message%20Broker-orange.svg)
![](https://img.shields.io/badge/MONAI-AI%20Framework-red.svg)

## 📋 Proje Tanımı

HealthAI, yapay zeka ve sağlık teknolojilerini birleştiren modern bir platformdur. Kullanıcı dostu arayüzü ve yapay zeka destekli analiz araçlarıyla, sağlık alanında çalışan araştırmacılar, öğrenciler ve profesyoneller için özel olarak tasarlanmıştır.

## ✨ Özellikler

- 📂 **Modül Ekleme:** Yapay zeka modellerinin (PY, PTH, H5) kolay yüklenmesi ve yönetimi
- 🗂 **Modül Yönetimi:** Kullanıcıların kendi yükledikleri modülleri görüntüleme ve düzenleme
- 🤝 **Ekip Yönetimi:** Ekip oluşturma, davet gönderme ve işbirliği yapma
- 🖥️ **3D Görüntüleme:** İnteraktif 3D model görselleştirme ve analiz
- 📊 **2D Görüntü İşleme:** Tıbbi görüntüler üzerinde lezyon tespiti ve işaretleme
- 🔒 **Yetkili Paneli:** Öğrenci kayıt yönetimi ve onay sistemi
- ⚙️ **Modül Erişim Kontrolü:** Grup ID'sine göre modül erişim yetkileri yönetimi

## 🛠️ Teknolojiler

- **Backend:** Django 4.2.22
- **Frontend:** Bootstrap, HTML, CSS, JavaScript
- **Veritabanı:** PostgreSQL
- **Mesaj Kuyruğu:** RabbitMQ
- **Asenkron Görevler:** Celery
- **Yapay Zeka:** MONAI, U-Net, segmentasyon algoritmaları
- **Kimlik Doğrulama:** Django Authentication
- **E-posta:** SMTP

## 🚀 Kurulum

1. Repoyu klonlayın:
   ```bash
   git clone https://github.com/username/HealthAI.git
   cd HealthAI
   ```

2. Bağımlılıkları yükleyin:
   ```bash
   pip install -r requirements.txt
   ```

3. Veritabanını kurun:
   ```bash
   python manage.py migrate
   ```

4. Geliştirme sunucusunu başlatın:
   ```bash
   python manage.py runserver
   ```

5. RabbitMQ ve Celery'i başlatın:
   ```bash
   celery -A HealthAI worker --loglevel=info
   ```

6. Tarayıcınızda [http://localhost:8000](http://localhost:8000) adresine gidin

## 📷 Platform Görselleri

![Modül Ekleme Sayfası](static/images/module_upload.png)
![3D Görüntüleme](static/images/3d_viewer.png)
![2D Görüntü İşleme](static/images/2d_processing.png)
![Ekip Yönetimi](static/images/team_management.png)

## 🗂️ Proje Yapısı

- **core:** Temel sistem bileşenleri, kullanıcı yönetimi
- **modules:** Yapay zeka modülleri ve işlevleri
- **imaging:** 2D ve 3D görüntüleme araçları
- **teams:** Ekip yönetimi ve davet sistemi
- **admin_panel:** Yetkili kontrol paneli
- **static:** CSS, JavaScript, resimler
- **templates:** HTML şablonları
- **media:** Kullanıcı yüklenen dosyalar ve modeller

## 📝 Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.

## 📞 İletişim

Sorularınız veya önerileriniz için: [erdaltasar24@gmail.com](mailto:erdaltasar24@gmail.com)

---

## 🧪 Modüller ve Kullanım Alanları

### 1️⃣ Modül Ekleme ve Yönetim

Yapay zeka modellerinizi platforma kolayca yükleyebilir, grup ID'nize göre düzenleyebilir ve diğer kullanıcılarla paylaşabilirsiniz. Modüller PY, PTH veya H5 formatlarında olabilir.

### 2️⃣ 3D Görüntüleme

Sağlık alanında kullanılan 3D modelleri interaktif olarak görüntüleyebilir, döndürebilir ve detaylı inceleyebilirsiniz. Bu özellik, özellikle anatomi çalışmaları ve cerrahi planlama için değerlidir.

### 3️⃣ 2D Görüntü İşleme

Diş röntgenleri ve diğer tıbbi görüntüler üzerinde lezyon tespiti yapabilir, dikdörtgen, poligon ve çizgi işaretlemeleri kullanarak tanı süreçlerine yardımcı olabilirsiniz.

### 4️⃣ Ekip İşbirliği

Projeleriniz için ekipler oluşturabilir, davetler gönderebilir ve ortak çalışma alanları oluşturabilirsiniz. Her ekip için benzersiz bir Grup ID'si oluşturulur.

⭐ Bu projeyi beğendiyseniz, yıldız vermeyi unutmayın! ⭐
