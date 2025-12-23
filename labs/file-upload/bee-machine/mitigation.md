# Mitigation

Bu laboratuvarda tespit edilen File Upload zafiyeti,
dosya yükleme mekanizmasında
sunucu taraflı güvenlik kontrollerinin
yetersiz olması nedeniyle ortaya çıkmıştır.

Yalnızca istemci tarafında yapılan
kontroller, saldırganlar tarafından
kolaylıkla aşılabilmektedir.

---

## 🛡️ Önerilen Güvenlik Önlemleri

File Upload zafiyetlerini önlemek için
aşağıdaki önlemler uygulanmalıdır:

- **Sunucu Taraflı Dosya Kontrolü**  
  Yüklenen dosyaların uzantısı,
  MIME tipi ve içerik yapısı
  sunucu tarafında doğrulanmalıdır.

- **İzin Verilen Uzantılar (Whitelist)**  
  Yalnızca belirli ve güvenli dosya
  uzantılarına izin verilmelidir.

- **Dosya Yeniden Adlandırma**  
  Yüklenen dosyaların isimleri
  sunucu tarafından rastgele
  şekilde yeniden oluşturulmalıdır.

- **Çalıştırılamaz Dizin Kullanımı**  
  Yüklenen dosyalar,
  çalıştırma izni olmayan
  dizinlerde saklanmalıdır.

---

## 🎯 Sonuç

Bu önlemler uygulandığında,
File Upload zafiyetlerinin
oluşma riski önemli ölçüde
azaltılacaktır.
