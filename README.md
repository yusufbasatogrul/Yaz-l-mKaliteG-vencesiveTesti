### **Yazılım Test Süreci ve Uygulama Projesi**  
**Fırat Üniversitesi - Teknoloji Fakültesi - Yazılım Mühendisliği**  
**Ders:** Yazılım Kalite Güvencesi ve Testi  
**Proje Sahibi:** Yusuf Basatoğrul  
**Proje Danışmanı:** Prof. Dr. Resul DAŞ, Arş. Gör. Semra ÇELEBİ  

---

## 📌 **Proje Açıklaması**
Bu proje, **yazılım test süreçlerini** detaylı olarak ele alarak **n11 e-ticaret platformu** üzerinde çeşitli testler gerçekleştirmeyi amaçlamaktadır. Çeşitli **test türleri ve seviyeleri** kullanılarak yazılımın kalitesini ve güvenliğini ölçmek için analizler yapılmıştır.

## 🔍 **Yapılan Testler**
Projede aşağıdaki test türleri uygulanmıştır:

### **1️⃣ Entegrasyon Testi**
- **Amaç:** Yazılım bileşenlerinin bir araya geldiğinde uyum içinde çalışıp çalışmadığını kontrol etmek  
- **Uygulama:**  
  - Kullanıcı giriş ekranında **Facebook ile giriş** ve **şifre unutma** işlemlerinin entegrasyonu test edildi  
  - Sonuç: Web ortamında başarılı bir entegrasyon sağlanamadı  

### **2️⃣ Fonksiyonellik Testi**
- **Amaç:** Belirli işlevlerin doğru çalışp çalışmadığını test etmek  
- **Uygulama:**  
  - **Arama kutusu**, **butonlar**, **etiketler** ve **görsellerin** düzgün çalıştığı test edildi  
  - Test senaryosu: "Telefon" araması yapıldı, ürün sepete eklendi ve doğrulandı  

### **3️⃣ Yük ve Stres Testi**
- **Araç:** [K6](https://k6.io/)  
- **Amaç:** Sistemin yüksek yük altında nasıl tepki verdiğini ölçmek  
- **Uygulama:**  
  - **50, 70, 90 ve 100 kullanıcılı** yük testleri gerçekleştirildi  
  - Sonuçlar **Grafana Dashboard** üzerinden analiz edildi  

### **4️⃣ Birim Testi**
- **Amaç:** En küçük yazılım birimlerinin doğru çalıştığını doğrulamak  
- **Uygulama:**  
  - **Adres defteri** ekleme, silme ve güncelleme işlemleri test edildi  

### **5️⃣ GUI Testi**
- **Amaç:** Kullanıcı arayüzünün işlevselliğini değerlendirmek  
- **Uygulama:**  
  - n11.com’daki **ürün kategorileri** test edildi  

### **6️⃣ Brute Force Testi**
- **Amaç:** Kullanıcı giriş ekranının güvenliğini test etmek  
- **Uygulama:**  
  - Kullanıcı adı ve parola çok kez girilerek **hesap güvenliği** sınandı  

### **7️⃣ SQL Injection Testi**
- **Amaç:** Uygulamanın **veritabanı güvenliğini** test etmek  
- **Uygulama:**  
  - Arama kutusuna **SQL Injection** sorguları girildi ve yetkisiz erişim test edildi  

---

## 📊 **Kullanılan Araçlar ve Teknolojiler**
- **K6** (Performans Testleri)  
- **Grafana** (Test sonuçlarının görselleştirilmesi)  
- **Selenium** (Fonksiyonel testler)  
- **JUnit** (Birim testler)  

---

## 📢 **Sonuçlar ve Çıkarımlar**
- **Yazılım test süreçlerinin önemi** proje kapsamında detaylı şekilde incelendi  
- Çeşitli test türleri uygulandı ve **güvenlik açıkları tespit edildi**  
- **Yük testleri ve entegrasyon testleri** sırasında sistemin limitleri gözlemlendi  
- Gerçek dünyadaki bir e-ticaret sitesinde yazılım test süreçlerinin **nasıl uygulanabileceği** deneyimlendi  

---
