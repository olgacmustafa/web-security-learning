# Methodology

Bu laboratuvarda, SQL Injection zafiyetini tespit etmek ve
anlamak için **adım adım bir test yaklaşımı** izlenmiştir.

İlk olarak, uygulamanın kullanıcıdan veri aldığı giriş
noktaları incelenmiştir. Özellikle, bu girdilerin arka planda
çalışan SQL sorgularında nasıl kullanıldığına odaklanılmıştır.

---

## 🔍 Test Yaklaşımı

İzlenen temel adımlar şunlardır:

1. Kullanıcıdan veri alan giriş alanlarının belirlenmesi  
2. Girilen verinin sunucu tarafında herhangi bir doğrulama
   veya filtrelemeden geçip geçmediğinin gözlemlenmesi  
3. Özel olarak hazırlanmış giriş değerleri (payload) ile
   uygulamanın davranışının test edilmesi  

Bu süreçte, uygulamanın beklenmeyen veya hatalı girdilere
nasıl tepki verdiği dikkatle analiz edilmiştir.

---

## 🧪 Deneme ve Gözlem

Testler sırasında:

- Normal kullanıcı girdileri ile uygulamanın beklenen şekilde
  çalıştığı gözlemlenmiştir  
- Özel karakterler ve mantıksal ifadeler içeren girdiler
  girildiğinde, uygulamanın verdiği yanıtlar incelenmiştir  

Bu gözlemler, uygulamanın kullanıcı girdisini doğrudan
SQL sorgusu içerisine eklediğini ve yeterli güvenlik
kontrollerini uygulamadığını göstermektedir.

---

## ⚠️ Not

Bu metodoloji, **eğitim amaçlı** hazırlanmış basit bir
senaryoyu temel almaktadır.
Gerçek dünyadaki uygulamalarda, SQL Injection zafiyetlerini
tespit etmek için daha kapsamlı ve otomatik test yöntemleri
kullanılabilir.
