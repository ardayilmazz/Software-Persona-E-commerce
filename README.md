# Flutter Ürün Uygulaması

Ürünleri bir API üzerinden listeleyen, detay sayfası ve sepet ekranı sunan basit bir **Flutter** mobil uygulaması.

## Ne yapar?

- Ana ekranda ürün listesi (kart görünümü)
- Ürün detay sayfası
- Sepet ekranı
- Veriler `https://wantapi.com/products.php` adresinden (`http` paketi ile) alınır

## Gereksinimler

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (projede tanımlı Dart SDK sürümüne uygun)

## Çalıştırma

```bash
flutter pub get
flutter run
```

Android, iOS, web veya masaüstü hedeflerinden birini seçerek çalıştırabilirsiniz.

## Proje yapısı (özet)

| Klasör / dosya | Açıklama |
|----------------|----------|
| `lib/main.dart` | Uygulama girişi ve tema |
| `lib/views/` | Ana ekran, ürün detayı, sepet |
| `lib/services/api_service.dart` | API istekleri |
| `lib/models/` | Ürün veri modelleri |
| `lib/components/` | Ortak bileşenler (ör. ürün kartı) |

---

