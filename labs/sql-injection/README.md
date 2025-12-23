# 🐝 Bee Machine – SQL Injection Lab

- **Platform:** Hackviser  
- **Kategori:** Web Uygulama Güvenliği  

Bu laboratuvar çalışmasında, bir web uygulamasında bulunan
**SQL Injection (SQLi)** zafiyeti test edilmiştir.

Çalışma, yetkili ve kontrollü bir laboratuvar ortamında,
eğitim ve öğrenme amacıyla gerçekleştirilmiştir.

---

## 🎯 Laboratuvarın Amacı

Bu lab’ın amacı:

- Kullanıcıdan alınan girdilerin yeterince
  doğrulanmaması durumunda ortaya çıkabilecek
  güvenlik risklerini görmek  
- SQL Injection zafiyetinin kimlik doğrulama
  mekanizmalarını nasıl etkileyebildiğini
  pratik olarak gözlemlemek  
- Birden fazla zafiyetin bir arada bulunmasının,
  uygulama güvenliği açısından neden tehlikeli
  olduğunu anlamaktır  

---

## 🔓 Tespit Edilen Zafiyetler

Bu laboratuvar kapsamında aşağıdaki zafiyetler
gözlemlenmiştir:

- **SQL Injection (Authentication Bypass)**  
  Kullanıcı girdisinin SQL sorgusunu etkilemesi
  sonucunda kimlik doğrulama mekanizmasının
  atlatılabilmesi

- **File Upload Zafiyeti**  
  Yüklenen dosyaların yeterince kontrol edilmemesi

- **Remote Code Execution (RCE)**  
  Uygulama üzerinde yetkisiz komut çalıştırılabilmesi

Bu write-up içerisinde ağırlıklı olarak
**SQL Injection zafiyeti** ele alınmıştır.

---

## 📁 İçerik Yapısı

Bu klasörde yer alan dosyalar:

- **overview.md**  
  SQL Injection zafiyetinin genel tanımı ve lab’ın kapsamı

- **methodology.md**  
  Zafiyeti tespit etmek için izlenen yaklaşım ve test süreci

- **exploitation.md**  
  SQL Injection zafiyetinin pratikte nasıl test edildiği
  ve doğrulandığı adımlar

- **mitigation.md**  
  Bu tür zafiyetlerin nasıl önlenebileceğine dair
  güvenlik önerileri

- **lessons-learned.md**  
  Laboratuvar çalışması sonucunda edinilen
  kişisel kazanımlar ve çıkarımlar

---


