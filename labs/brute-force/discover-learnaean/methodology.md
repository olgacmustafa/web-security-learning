# Methodology

Bu laboratuvarda, Brute Force saldırısının nasıl
gerçekleştirilebildiğini anlamak için **kontrollü ve
adım adım bir test yaklaşımı** izlenmiştir.

Amaç, bir web uygulamasındaki kimlik doğrulama (authentication)
mekanizmasının zayıf noktalarını gözlemlemek ve bu
zayıflıkların nasıl istismar edilebileceğini anlamaktır.

---

## 🔍 Test Yaklaşımı

İzlenen temel metodoloji şu adımlardan oluşmaktadır:

1. Uygulamanın kullanıcı giriş (login) mekanizmasının
   belirlenmesi  

2. Giriş denemeleri sırasında uygulamanın verdiği
   yanıtların analiz edilmesi  

3. Başarısız giriş denemeleri sonrasında herhangi bir
   kısıtlama (kilitleme, gecikme vb.) uygulanıp
   uygulanmadığının gözlemlenmesi  

4. Farklı parola kombinasyonları kullanılarak sistemin
   davranışının test edilmesi  

Bu adımlar, uygulamanın Brute Force saldırılarına karşı
ne kadar dayanıklı olduğunu anlamak için kullanılmıştır.

---

## 🧪 Deneme Süreci

Testler sırasında:

- Yanlış kullanıcı adı ve parola kombinasyonları
  sistematik olarak denenmiştir  

- Uygulamanın başarısız denemelere verdiği tepkiler
  dikkatle incelenmiştir  

- Deneme sayısına bağlı olarak herhangi bir
  güvenlik mekanizmasının devreye girip girmediği
  kontrol edilmiştir  

Bu gözlemler, uygulamanın sınırsız giriş denemesine
izin verip vermediğini ortaya koymaktadır.

---

## ⚠️ Not

Bu metodoloji, **eğitim amaçlı** hazırlanmış bir
senaryoya dayanmaktadır.

Gerçek dünyada Brute Force saldırılarını tespit etmek
ve önlemek için otomatik araçlar, log analizleri ve
gelişmiş güvenlik kontrolleri kullanılmaktadır.
