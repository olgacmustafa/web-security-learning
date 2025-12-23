# Methodology

Local File Inclusion (LFI) zafiyetini tespit edebilmek için,
uygulamanın kullanıcı girdisine bağlı olarak
sunucu üzerindeki dosyaları çağıran
mekanizmaları incelenmiştir.

Bu aşamada amaç, kullanıcıdan alınan bir parametrenin
sunucu tarafında doğrudan dosya yolu olarak
kullanılıp kullanılmadığını anlamaktır.

---

## 🔍 İzlenen Yaklaşım

Test sürecinde aşağıdaki adımlar izlenmiştir:

1. URL parametreleri ve istekler incelenerek,
   dosya çağırma ihtimali bulunan alanların
   belirlenmesi

2. Parametre değerlerinin sunucu tarafında
   nasıl işlendiğinin gözlemlenmesi

3. Parametre üzerinde yapılan küçük değişikliklerin
   uygulama davranışında farklılık oluşturup
   oluşturmadığının kontrol edilmesi

4. Dosya yolu manipülasyonuna açık olabilecek
   noktalar üzerinde LFI testlerinin
   yapılmasına karar verilmesi

Bu metodoloji ile, zafiyetin rastgele değil,
**bilinçli bir analiz süreci** sonucunda
tespit edilmesi hedeflenmiştir.
