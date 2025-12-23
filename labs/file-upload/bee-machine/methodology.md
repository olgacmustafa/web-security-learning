# Methodology

File Upload zafiyetini tespit edebilmek için,
uygulamada kullanıcıdan dosya yüklenmesine
izin verilen alanlar incelenmiştir.

Bu aşamada amaç, yüklenen dosyalar üzerinde
herhangi bir dosya türü, uzantı veya içerik
kontrolü yapılıp yapılmadığını anlamaktır.

---

## 🔍 İzlenen Yaklaşım

Test sürecinde aşağıdaki adımlar izlenmiştir:

1. Uygulamada dosya yükleme özelliği bulunan
   alanların tespit edilmesi

2. Yüklenen dosyaların uzantılarına göre
   herhangi bir kısıtlama uygulanıp
   uygulanmadığının gözlemlenmesi

3. Sunucu tarafında dosya içeriğine yönelik
   bir kontrol (MIME type, içerik analizi vb.)
   yapılıp yapılmadığının değerlendirilmesi

4. Dosyaların yüklendikten sonra
   nerede saklandığının ve
   doğrudan erişilebilir olup olmadığının
   incelenmesi

Bu yaklaşım ile, dosya yükleme mekanizmasının
ne kadar güvenli olduğu belirlenmeye çalışılmıştır.
