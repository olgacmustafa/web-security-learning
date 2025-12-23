# Methodology

Server-Side Template Injection (SSTI) zafiyetini
tespit edebilmek için, uygulamanın kullanıcıdan
aldığı girdileri sunucu tarafında
dinamik olarak işlediği alanlar incelenmiştir.

Bu aşamada amaç, kullanıcı girdilerinin
herhangi bir filtreleme veya güvenli
işleme tabi tutulmadan,
template motoru içerisinde
doğrudan kullanılıp kullanılmadığını
anlamaktır.

---

## 🔍 İzlenen Yaklaşım

Test sürecinde aşağıdaki adımlar izlenmiştir:

1. Uygulamada kullanıcıdan alınan
   girdilerin ekrana dinamik olarak
   yansıtıldığı alanların belirlenmesi

2. Bu alanlarda kullanılan
   template motorunun davranışının
   gözlemlenmesi

3. Kullanıcı girdisinin,
   sunucu tarafında çalışan
   template ifadeleri ile
   etkileşime girip girmediğinin
   değerlendirilmesi

4. Template motoru tarafından
   yorumlanma ihtimali bulunan
   girdiler üzerinde SSTI
   testlerinin yapılmasına
   karar verilmesi

Bu metodoloji ile, SSTI zafiyetinin
rastgele değil,
**bilinçli bir analiz süreci**
sonucunda test edilmesi
hedeflenmiştir.
