# Flutter Ürün Uygulaması

▪ **Proje adı:** Flutter Ürün Uygulaması (`flutter_application_1`)

▪ **Kısa açıklama:** Ürünleri bir API üzerinden listeleyen, detay ve sepet ekranları sunan Flutter mobil uygulaması. Veriler `https://wantapi.com/products.php` adresinden alınır. Uygulama içerisinde 3 farklı sayfa bulunmaktadır. Bunlar; ana sayfa, ürün listesi, ürün detayı ekran yapısı. Navigator yapısı kullanılarak ekran geçişleri ayarlanmıştır. Ayrıca Route argument ve gridview yapıları da proje içerisinde kullanılmıştır.

▪ **Kullanılan Flutter sürümü:** Bu makinede doğrulanan ortam: Flutter **3.41.6** (stable), Dart **3.11.4**. `pubspec.yaml` içinde Dart SDK alt sınırı: `^3.11.4`. Farklı bir Flutter kurulumu kullanıyorsanız, en az bu Dart sürümüyle uyumlu bir Flutter sürümü tercih edin.

▪ **Çalıştırma adımları:**

1. Proje klasöründe terminal açın.
2. Bağımlılıkları yükleyin:

   ```bash
   flutter pub get
   ```

3. Bağlı bir cihaz veya emülatör seçip uygulamayı çalıştırın:

   ```bash
   flutter run
   ```

   Gerekirse hedefi belirtin, örneğin: `flutter run -d chrome` (web) veya `flutter devices` ile cihaz listesine bakın.
