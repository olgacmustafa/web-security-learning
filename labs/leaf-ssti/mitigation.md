# Mitigation

Bu laboratuvarda tespit edilen Server-Side Template Injection (SSTI)
zafiyeti, kullanıcıdan alınan girdilerin
sunucu tarafında kullanılan template motoru
içerisinde doğrudan işlenmesi nedeniyle
ortaya çıkmıştır.

Kullanıcı girdilerinin yeterince filtrelenmemesi
ve güvenli şekilde ayrıştırılmaması,
saldırganın template ifadeleri enjekte etmesine
olanak tanımaktadır.

---

## 🛡️ Önerilen Güvenlik Önlemleri

SSTI zafiyetlerini önlemek için aşağıdaki
önlemler uygulanmalıdır:

- **Template Auto-Escaping Kullanımı**  
  Template motorlarında otomatik escape
  mekanizmaları aktif hale getirilmelidir.

- **Kullanıcı Girdilerinin Filtrelenmesi**  
  Kullanıcıdan alınan veriler,
  template ifadeleri çalıştırılmadan önce
  güvenli şekilde filtrelenmelidir.

- **Mantık ve Görünümün Ayrılması**  
  İş mantığı (logic) template dosyaları
  içerisinde kullanılmamalı,
  yalnızca görünüm (view) katmanı
  template’ler üzerinden oluşturulmalıdır.

- **Güvenli Template Motoru Konfigürasyonu**  
  Template motorlarının tehlikeli fonksiyonlara
  erişimi sınırlandırılmalı veya tamamen
  devre dışı bırakılmalıdır.

---

## 🎯 Sonuç

Bu önlemler uygulandığında,
Server-Side Template Injection zafiyetlerinin
oluşma riski önemli ölçüde azaltılacaktır.

Template motorlarının güvenli kullanımı,
web uygulama güvenliğinin
kritik bir parçasıdır.
