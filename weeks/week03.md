# Hafta 3 — Optimizasyon: Çok Değişkenli Problemler

Kaynak: Givens ve Hoeting, "Computational Statistics", 2nd edition — Part I: Optimization, Section 2.2 (Multivariate Problems).

Amaç
- Çok değişkenli optimizasyon problemlerinin temellerini öğrenmek.
- Gradien ve Hessian gibi türevsel yaklaşımlar ile yerel ve küresel optimumların bulunması.
- Çok değişkenli fonksiyonlarda kısıtlı ve kısıtsız optimizasyon yöntemlerini gözden geçirmek.

Okuma
- Givens & Hoeting, Computational Statistics (2nd ed.), Part I — Optimization, Section 2.2: "Multivariate Problems".

Önerilen içerik ve başlıklar
1. Tanımlar ve notasyon
   - Çok değişkenli fonksiyon f(x), gradient ∇f(x), Hessian H(x).
   - Kritik noktalar: yerel minimum, maksimum, eyer noktaları.
2. Analitik testler
   - Hessian kullanarak ikinci mertebe şartları.
3. Sayısal yöntemler
   - Çok değişkenli Newton yöntemi
   - Doğrultu ve line-search (azaltma) yöntemleri
   - Quasi-Newton yöntemleri (BFGS gibi) ��� kısa giriş
4. Kısıtlı optimizasyon
   - Lagrange çarpanları ile eşitlik kısıtları
   - Kısıtlu çözümler için kısa fikir (e.g., aktif küme yaklaşımları)
5. Uygulamalar ve örnekler
   - Basit iki-değişkenli örneklerle Newton ve BFGS karşılaştırması
   - R (veya Python) ile sayısal örnek: gradient hesaplama ve optimize() kullanımı

Ödev / Problem önerileri
- Kitaptaki örnekleri takip ederek küçük bir optimizasyon problemi çözün (analitik ve sayısal sonuçları karşılaştırın).
- Bir BFGS uygulaması kullanarak bir test fonksiyonunun minimumunu bulun (R: optim(), Python: scipy.optimize.minimize).

Notlar
- Ders notları, sunum slaytları ve örnek kodlar (R/Python) eklenecek.

İlgili dosya
- Bu içerik weeks/week03.md altında eklendi.
