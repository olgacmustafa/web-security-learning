# Overview

Bu laboratuvar, web uygulamalarında yaygın olarak görülen
**SQL Injection (SQLi)** zafiyetini tanıtmayı amaçlamaktadır.

SQL Injection, kullanıcıdan alınan girdilerin yeterince
doğrulanmaması veya filtrelenmemesi durumunda ortaya çıkar.
Bu tür bir zafiyet, saldırganların arka planda çalışan
veritabanı sorgularını manipüle etmesine olanak tanır.

Bu laboratuvarda, kullanıcı girdisinin doğrudan SQL sorgusu
içerisine eklendiği ve herhangi bir güvenlik kontrolünden
geçirilmediği bir senaryo ele alınmaktadır.

---

## 🎯 Laboratuvarın Amacı

Bu çalışmanın temel amacı:

- SQL Injection zafiyetinin **nasıl oluştuğunu** anlamak  
- Kullanıcı girdilerinin neden güvenli şekilde işlenmesi
  gerektiğini kavramak  
- Basit bir SQL Injection saldırısının uygulama üzerinde
  nasıl etkiler yaratabileceğini görmek  

---

## 🧠 Genel Bakış

Bu laboratuvar kapsamında:

- Savunmasız bir giriş mekanizması incelenecek  
- Saldırganın, girdiler aracılığıyla SQL sorgusunu nasıl
  değiştirebildiği gözlemlenecek  
- Yetkisiz veri erişiminin nasıl mümkün hale geldiği
  anlaşılacaktır  

Bu çalışma tamamen **eğitim amaçlıdır** ve yalnızca
yetkili, kontrollü ortamlarda uygulanmalıdır.
