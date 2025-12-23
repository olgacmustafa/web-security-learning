# Methodology

Brute Force zafiyetini test edebilmek için,
hedef sistem üzerinde öncelikle
erişilebilir servisler ve kimlik doğrulama
mekanizmaları incelenmiştir.

Bu aşamada amaç, hangi servislerin
Brute Force saldırılarına uygun olabileceğini
belirlemektir.

---

## 🔍 İzlenen Yaklaşım

Test sürecinde aşağıdaki adımlar izlenmiştir:

1. Hedef sistemde çalışan servislerin
   tespit edilmesi

2. Kimlik doğrulama gerektiren servislerin
   belirlenmesi

3. Bu servislerde giriş denemelerine karşı
   herhangi bir kısıtlama veya ek güvenlik
   mekanizmasının bulunup bulunmadığının
   gözlemlenmesi

4. Giriş denemesi sınırı bulunmayan
   servisler üzerinde Brute Force
   saldırısının test edilmesine karar verilmesi

