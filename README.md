# Java Telefon Rehberi (Adres Defteri)

Bu proje, Java ve Swing kullanılarak geliştirilmiş bir masaüstü telefon rehberi uygulamasıdır. Projede standart koleksiyonlar (ArrayList vb.) yerine, kapasitesi dinamik olarak artabilen özel bir dizi veri yapısı (`OzelKisiDizisi`) kullanılmıştır.

## Özellikler
* **Kişi Yönetimi:** Yeni kişi ekleme, silme ve güncelleme işlemleri.
* **Arama ve Filtreleme:** İsim bazlı gerçek zamanlı arama.
* **Sıralama:** Rehberdeki kişileri A-Z'ye alfabetik olarak sıralama.
* **Dosya İşlemleri (I/O):** Veriler `rehber.txt` dosyasına kaydedilir ve program her açıldığında bu dosyadan geri okunur (Kalıcı veri depolama).
* **Modern Arayüz:** Kullanıcı dostu ve renkli Java Swing GUI.
* **Hata Kontrolü:** Aynı numaranın tekrar eklenmesini engelleme ve boş veri girişini kontrol etme.
