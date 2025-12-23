# Lessons Learned

Bu laboratuvar çalışması sayesinde,
File Upload mekanizmalarının
yetersiz şekilde kontrol edilmesi durumunda,
uygulama güvenliği açısından
ne kadar ciddi riskler oluşabileceği
net bir şekilde görülmüştür.

---

## 🧠 Edinilen Kazanımlar

Bu lab kapsamında:

- Dosya yükleme alanlarının,
  saldırganlar için önemli bir
  giriş noktası olabileceği anlaşılmıştır.

- Yalnızca istemci tarafında yapılan
  dosya kontrollerinin güvenli olmadığı
  gözlemlenmiştir.

- Dosya uzantısı kontrollerinin
  farklı yöntemlerle (çift uzantı,
  büyük/küçük harf farkı vb.)
  aşılabildiği görülmüştür.

- Yüklenen dosyaların doğrudan
  erişilebilir dizinlerde tutulmasının,
  daha ileri saldırılara
  (örneğin RCE) zemin hazırladığı
  anlaşılmıştır.

---

## 🎯 Genel Değerlendirme

Bu çalışma, File Upload zafiyetlerinin
tek başına basit gibi görünse de,
uygulamanın tamamen ele geçirilmesine
kadar gidebilecek sonuçlar
doğurabileceğini göstermiştir.

Güvenli dosya yükleme mekanizmalarının
tasarlanması, web uygulama güvenliğinin
kritik bir parçasıdır.
