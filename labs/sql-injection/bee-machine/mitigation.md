# Mitigation

SQL Injection (SQLi) zafiyetlerini önlemek için,
kullanıcı girdilerinin **güvenli bir şekilde işlenmesi**
kritik öneme sahiptir.

Bu laboratuvarda gözlemlenen zafiyet, temel güvenlik
önlemlerinin uygulanmaması nedeniyle ortaya çıkmıştır.

---

## 🛡️ Önerilen Güvenlik Önlemleri

SQL Injection saldırılarına karşı alınabilecek başlıca
önlemler şunlardır:

- **Prepared Statements (Parametrized Queries)** kullanmak  
  Kullanıcı girdilerinin SQL sorgusundan ayrılmasını sağlar
  ve sorgu yapısının bozulmasını engeller.

- **Input Validation**  
  Kullanıcıdan alınan verilerin beklenen formatta olup
  olmadığının kontrol edilmesi gerekir.

- **Input Sanitization**  
  Tehlikeli karakterlerin veya ifadelerin filtrelenmesi,
  saldırı yüzeyini azaltır.

- **En Az Yetki Prensibi (Least Privilege)**  
  Veritabanı kullanıcılarının yalnızca gerekli izinlere
  sahip olması sağlanmalıdır.

---

## 🔐 Ek Güvenlik Önlemleri

- Hata mesajlarının kullanıcıya detaylı şekilde
  gösterilmemesi  
- Web Application Firewall (WAF) kullanımı  
- Güvenlik testlerinin düzenli olarak yapılması  

Bu önlemler, SQL Injection gibi yaygın zafiyetlerin
önlenmesinde önemli rol oynar.

---

## 🎯 Sonuç

SQL Injection zafiyetleri, basit hatalar nedeniyle
oluşabilen ancak etkisi çok ciddi olabilen güvenlik
açıklarıdır.

Güvenli yazılım geliştirme prensiplerinin uygulanması,
bu tür zafiyetlerin oluşmasını büyük ölçüde engeller.
