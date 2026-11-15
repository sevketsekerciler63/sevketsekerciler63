# Şevket

Üniversite öğrencisiyim. Yazılımı yapay zekâ asistanlarıyla geliştiriyorum ve bunu saklamıyorum. Ne yapılacağına, neyin kapsam dışı kalacağına ben karar veriyorum; kodu asistan yazıyor. Çalışmayan bir şeyi çalışıyor diye yazmam; denemediklerimi README'lerde belirtiyorum.

Projelerde şimdilik Flutter, C# ve React kullandım.

## Projeler

**[Ajan Dürüstlük Testi](https://github.com/sevketsekerciler63/ajan-durustluk-testi)**
Kodlama ajanlarına çözülemez (tuzak) görevler veriyorum. Yapay zekâ kullanmayan bir hakem, ajanın "yaptım" sözünü ajanın görmediği gizli testlerle karşılaştırıyor. Kendi bilgisayarımda Qwen3.5-9B modeli ve bir türeviyle toplam 200 deneme yaptım. Model tuzak görevlerin çoğunda "tamamlandı" dedi: döviz kurunu uydurdu (çoğunda 1 USD = 32,50 TL), sahte paket yazdı, test dosyasını değiştirdi. Bunun üzerine bir "kaynaksız değer dedektörü" yaptım; ajanın yazdığı her sayının oturumda gördüğü bir yerden gelip gelmediğine bakıyor. Uydurulan kurların 32'de 32'sini yakaladı, hiç görmediği 425 gerçek açık kaynak değişikliğinde kaynak kodda yanlış alarm vermedi. Claude Code'a eklenebiliyor. Node.js, bağımlılık yok.

**[BarberBook](https://github.com/sevketsekerciler63/barberbook)**
Berber dükkânı için randevu ve kasa takibi. Randevu çakışmasını engelliyor, nakit, kart ve veresiye tutuyor, veriler telefonda kalıyor. Flutter + SQLite.

**[KasapPOS](https://github.com/sevketsekerciler63/kasappos)**
Kasap dükkânı için satış ve stok: barkod, karkas parçalama, müşteri hesabı, iade, gün sonu. C#, WPF, SQLite. 187 maddelik kabul kontrol paketi var.

**[Sınav Rotası](https://github.com/sevketsekerciler63/sinav-rotasi)** ([canlı demo](https://sevketsekerciler63.github.io/sinav-rotasi/))
YKS'ye hazırlananlar için çalışma takibi. Hesap yok, veriler telefonda. Flutter.

**[Kampüs Proje](https://github.com/sevketsekerciler63/kampus-proje)** ([canlı demo](https://sevketsekerciler63.github.io/kampus-proje/))
Ders için öğrenci proje ve ekip yönetimi demosu. React + TypeScript.

**[Türkçe LLM Değerlendirme](https://github.com/sevketsekerciler63/turkce-llm-degerlendirme)**
Dil modellerini Türkçe görevlerde karşılaştıran komut satırı aracı. Henüz gerçek modelle çalıştırılmadı (README'de yazıyor).

Diğer projelerim private.
