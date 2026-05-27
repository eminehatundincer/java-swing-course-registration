# Yaz Okulu Ders Talep Sistemi 🎓

Bu proje, öğrencilerin yaz okulunda almak istedikleri dersleri belirleyip listelemelerini ve bu talepleri bir dosyaya kaydetmelerini sağlayan **Java Swing** tabanlı bir masaüstü uygulamasıdır.

## 🚀 Özellikler

* **Ders ve Bölüm Seçimi:** Öğrenciler, sunulan temel dersler (örn. Fizik 1, Mat 1 vb.) ve bölümler arasından seçim yapabilir. (Sistemde en az 5 farklı ders ve 4 farklı bölüm tanımlıdır).
* **Dinamik Tablo (JTable) Yönetimi:** Seçilen dersler, kullanıcı onayından geçtikten sonra arayüzdeki bir tabloya eklenir.
* **Kural Kontrolleri:** 
  * Bir öğrenci en fazla **4 farklı ders** ekleyebilir.
  * Aynı ders, farklı bir bölümden seçilse dahi tabloya **tekrar eklenemez**.
* **Güvenli İşlem Onayları:** Ders ekleme ve silme işlemleri sırasında `JOptionPane` ile kullanıcıdan işlem onayı istenir.
* **Dosyaya Kaydetme:** Seçilen ders listesi, onaylandığında projenin kök dizininde bulunan `dersler.txt` dosyasına otomatik olarak yazdırılır.
* **Modüler Arayüz:** Kullanıcı arayüzü (UI), görünümü ve kodu düzenli tutmak adına en az 2 farklı `JPanel` kullanılarak tasarlanmıştır.

## 🛠️ Kullanılan Teknolojiler

* **Dil:** Java
* **Kullanıcı Arayüzü:** Java Swing (`JFrame`, `JPanel`, `JTable`, `JComboBox`, `JOptionPane`, `JButton`)
* **Veri Yönetimi:** Java File I/O (Dosya Okuma/Yazma)
