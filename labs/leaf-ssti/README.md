# 🧪 Server-Side Template Injection (SSTI) Lab

- **Platform:** Hackviser  
- **Kategori:** Web Uygulama Güvenliği  


Bu laboratuvar çalışmasında, bir web uygulamasında bulunan
**Server-Side Template Injection (SSTI)** zafiyeti test edilmiştir.

Amaç, sunucu tarafında kullanılan template (şablon) motorlarının
kullanıcı girdilerini güvenli şekilde işlemediği durumlarda,
uygulama güvenliği açısından ortaya çıkabilecek riskleri
pratik olarak gözlemlemektir.

Bu çalışma, yetkili ve kontrollü bir
laboratuvar ortamında,
eğitim ve portföy amacıyla gerçekleştirilmiştir.

---

## 🎯 Laboratuvarın Amacı

Bu lab’ın temel amacı:

- SSTI zafiyetinin nasıl tespit edilebileceğini
  pratik bir senaryo üzerinden göstermek  
- Template motorlarının davranışlarını analiz ederek,
  kullanıcı girdilerinin nasıl yorumlandığını anlamak  
- SSTI zafiyetlerinin, uygun koşullar altında
  ne kadar ciddi etkilere yol açabileceğini
  kavramaktır  

---

## 🔓 Ele Alınan Zafiyet

Bu laboratuvar kapsamında ele alınan
ana güvenlik açığı:

- **Server-Side Template Injection (SSTI)**  
  Kullanıcı girdilerinin, sunucu tarafında
  çalışan template motoru içerisinde
  filtrelenmeden işlenmesi

Bu zafiyet, saldırganın uygulama üzerinde
beklenmeyen işlemler gerçekleştirmesine
olanak tanımaktadır.

---

## 📁 İçerik Yapısı

Bu klasörde yer alan dosyalar:

- **overview.md**  
  SSTI zafiyetinin genel tanımı ve lab’ın kapsamı

- **methodology.md**  
  SSTI zafiyetini tespit etmek için izlenen
  analiz ve test yaklaşımı

- **exploitation.md**  
  SSTI zafiyetinin pratikte nasıl test edildiğini,
  doğrulandığını ve etkilerinin gözlemlendiğini
  gösteren uygulama adımları

- **mitigation.md**  
  SSTI zafiyetlerine karşı alınabilecek
  güvenlik önlemleri

- **conclusion.md**  
  Laboratuvar çalışması sonucunda
  elde edilen genel değerlendirme
  ve çıkarımlar

---
