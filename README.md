# Müşteri Analizi ve Strateji Geliştirme Projesi

Bu proje, **Hacettepe AI Club Datathon** yarışması için **Ulaş Taylan Met** ile birlikte geliştirdiğimiz ve bir şirketin müşteri verilerini kapsamlı şekilde analiz ederek iş performansını iyileştirmeyi hedefleyen bir çalışmadır. 

Ekip olarak **müşteri segmentasyon stratejileri** oluşturduk, temel problemleri belirledik ve veriye dayalı çözüm önerileri geliştirdik. Proje kapsamında, müşteri davranışlarını anlamak için çeşitli analitik yöntemler kullanıldı ve elde edilen bulgular doğrultusunda **stratejik karar alma süreçlerini destekleyecek sonuçlar** üretildi. 

Aşağıda **projenin metodolojisi, analiz süreçleri ve ulaştığımız temel çıktılar** detaylı şekilde özetlenmiştir.

---

## 📌 **Proje Amacı**
- Müşteri segmentasyonu ve davranış analizi yaparak şirketin **bölgesel, demografik ve operasyonel performansını** değerlendirmek.
- **Müşteri memnuniyeti, sadakat ve gelir ilişkisini** analiz ederek iyileştirme alanlarını belirlemek.
- Veriye dayalı **stratejik öneriler geliştirerek** şirketin karar alma süreçlerini desteklemek.

---

## 📊 **Kullanılan Metodoloji ve Analizler**

### 1️⃣ **Veri Kaynakları**  
- **Demografik veriler:** Yaş, bölge, cinsiyet  
- **Gelir metrikleri:** MRR (Aylık Tekrarlayan Gelir)  
- **Ürün kullanım verileri:** Kullanım süresi, tavsiye puanları, help ticket sayıları  
- **Kalite ve kullanılabilirlik derecelendirmeleri**  

### 2️⃣ **Analiz Yöntemleri**  
✔ **ANOVA Testi** – Yaş gruplarına göre müşteri seviyeleri arasındaki farklılıkların istatistiksel anlamlılığı değerlendirildi.  
✔ **Korelasyon Analizi** – Gelir, kullanım süresi, tavsiye puanları ve diğer metrikler arasındaki ilişkiler incelendi.  
✔ **Regresyon Modelleri** – Kullanım sıklığı ve gelir ilişkisi modellendi.  
✔ **Kümeleme (K-Means)** – Müşteriler yaş, bölge ve gelir düzeyine göre segmentlere ayrıldı.  
✔ **Görsel Analizler** – Dağılım grafikleri, kutu grafikleri ve ısı haritaları ile veri yorumlandı.  

---

## 🔍 **Temel Bulgular**

### 1️⃣ **Müşteri Memnuniyeti ve Sadakat**
- **Uzun Süreli Kullanıcılar:** 40 ay ve üzeri kullanıcıların tavsiye puanları düşük (4-6 aralığı).  
- **Help Ticket İlişkisi:** Yardım talebi sayısı arttıkça müşteri memnuniyeti azalıyor. 200+ ticket olan müşterilerin puanları belirgin şekilde düşük.  

### 2️⃣ **Bölgesel Performans**
- **Türkiye** – En yüksek müşteri sayısına sahip ülke (**%25.2**), ancak en düşük ortalama **MRR** değeri burada.  
- **Avustralya ve Brezilya** – Daha yüksek **MRR** değerleri, ancak düşük müşteri sayısı.  
- **Retained Müşteri Dağılımı** – Türkiye %20 ile lider, ancak Japonya ve Meksika gibi bölgelerde oranlar düşük.  

### 3️⃣ **Ürün ve Destek Süreçleri**
- **Kalite ve Destek Talebi:** Yüksek kalite puanına sahip ürünlerde **help ticket sayısı** ve **çözüm süreleri** artıyor.  
- **Kullanılabilirlik:** Panel kullanılabilirliği ile **MRR** arasında zayıf ilişki (korelasyon: **0.07**).  

### 4️⃣ **Segmentasyon ve Gelir**
- **Enterprise Müşteriler:** En yüksek gelir kaynağı, ancak gelir dağılımı geniş.  
- **Long-tail Müşteriler:** Düşük gelir, ancak yüksek sayıda kullanıcı potansiyeli.  




