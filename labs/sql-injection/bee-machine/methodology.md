# Methodology

SQL Injection zafiyetini tespit etmek için,
uygulamanın kullanıcıdan veri aldığı noktalar
incelenmiştir.

İzlenen yaklaşım şu şekildedir:

1. Web uygulamasında giriş alanları ve parametreler belirlendi.
2. Kullanıcı girdisinin arka planda çalışan SQL sorgularını
   etkileyip etkilemediği test edildi.
3. Basit mantıksal ifadelerle uygulamanın verdiği tepkiler
   gözlemlendi.
4. Normal giriş ile test girdileri arasındaki farklar
   karşılaştırılarak zafiyet doğrulandı.

Bu aşamada amaç, zafiyetin var olup olmadığını
anlamaktır; sömürü bu dosyanın konusu değildir.
