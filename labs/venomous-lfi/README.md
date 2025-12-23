# 🧬 Venomous – Local File Inclusion (LFI) Lab

- **Platform:** Hackviser  
- **Kategori:** Web Uygulama Güvenliği  
 

Bu laboratuvar çalışmasında, bir web uygulamasında bulunan
**Local File Inclusion (LFI)** zafiyeti test edilmiştir.

Amaç, kullanıcıdan alınan parametrelerin
sunucu tarafında yeterince kontrol edilmemesi durumunda,
saldırganın sunucu üzerindeki yerel dosyalara
yetkisiz şekilde erişip erişemeyeceğini
pratik olarak gözlemlemektir.

Bu çalışma, yetkili ve kontrollü bir
laboratuvar ortamında,
eğitim ve portföy amacıyla gerçekleştirilmiştir.

---

## 🎯 Laboratuvarın Amacı

Bu lab’ın temel amacı:

- LFI zafiyetinin nasıl oluştuğunu
  pratik bir senaryo üzerinden görmek  
- Dosya çağırma mekanizmalarının
  neden kritik bir güvenlik riski
  oluşturduğunu anlamak  
- Kullanıcı girdilerinin,
  sunucu tarafında kontrol edilmediğinde
  hangi sonuçlara yol açabileceğini
  gözlemlemektir  

---

## 🔓 Ele Alınan Zafiyet

Bu laboratuvar kapsamında ele alınan
ana güvenlik açığı:

- **Local File Inclusion (LFI)**  
  Kullanıcıdan alınan parametrelerin,
  sunucu üzerindeki dosyaları çağırmak
  için doğrudan kullanılması

Bu zafiyet, saldırganın sistem dosyalarına
erişmesine ve daha ileri saldırılar için
bilgi toplamasına olanak tanımaktadır.

---

## 📁 İçerik Yapısı

Bu klasörde yer alan dosyalar:

- **overview.md**  
  LFI zafiyetinin genel tanımı ve lab’ın kapsamı

- **methodology.md**  
  Zafiyeti tespit etmek için izlenen
  analiz yaklaşımı

- **exploitation.md**  
  LFI zafiyetinin pratikte nasıl
  test edildiğini ve doğrulandığını
  gösteren uygulama adımları

- **mitigation.md**  
  LFI zafiyetlerine karşı alınabilecek
  güvenlik önlemleri

- **conclusion.md**  
  Laboratuvar çalışması sonucunda
  elde edilen genel değerlendirme
  ve çıkarımlar

---


