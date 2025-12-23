# Mitigation

Bu laboratuvarda tespit edilen Local File Inclusion (LFI)
zafiyeti, kullanıcıdan alınan parametrelerin
sunucu tarafında yeterince doğrulanmaması
nedeniyle ortaya çıkmıştır.

Kullanıcı girdisinin doğrudan dosya yolu olarak
kullanılması, saldırganın sunucu üzerindeki
yerel dosyalara erişmesine olanak tanımaktadır.

---

## 🛡️ Önerilen Güvenlik Önlemleri

LFI zafiyetlerini önlemek için aşağıdaki
önlemler uygulanmalıdır:

- **Kullanıcı Girdisi Doğrulama (Input Validation)**  
  Dosya çağıran parametreler yalnızca
  beklenen ve güvenli değerleri
  kabul edecek şekilde sınırlandırılmalıdır.

- **Whitelist Yaklaşımı**  
  Sunucu tarafında erişilebilecek dosyalar
  önceden tanımlanmalı, bu listenin
  dışındaki dosyalara erişim engellenmelidir.

- **Path Traversal Kontrolleri**  
  `../` gibi dizin geçiş ifadeleri
  sunucu tarafında filtrelenmelidir.

- **Dosya Yolu Ayrıştırma**  
  Dosya yolları, kullanıcı girdisinden
  bağımsız olarak uygulama tarafından
  oluşturulmalıdır.

---

## 🎯 Sonuç

Bu önlemler uygulandığında,
Local File Inclusion zafiyetlerinin
oluşma riski önemli ölçüde azaltılacaktır.

Güvenli dosya çağırma mekanizmaları,
web uygulama güvenliğinin temel
bileşenlerinden biridir.
