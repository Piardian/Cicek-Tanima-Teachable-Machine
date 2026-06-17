# Cicek Tanima - Teachable Machine Modeli

Bu proje, Google Teachable Machine ile egitilmis cicek tanima modelinin son yerel export paketini icerir.

Model, fotograf uzerinden cicek turunu tahmin etmek icin hazirlanmistir. Etiketler: GUL, Orkide, Papatya, Diger, Kaktus, Lale ve Menekse.

## Son Surum

Bilgisayarda bulunan en yeni model export'u:

- `model/tflite/model_unquant.tflite` - 14.05.2026 tarihli mobil/TFLite model dosyasi.
- `model/tflite/labels.txt` - 14.05.2026 tarihli etiket dosyasi.

Bu dosyalar, bilgisayarda bulunan cicek tanima modelinin en son tarihli surumudur.

## Arsiv

Ek olarak daha eski tarihli Teachable Machine TensorFlow.js web export'u da arsiv olarak eklendi:

- `model/tfjs-archive-2026-05-12/model.json`
- `model/tfjs-archive-2026-05-12/metadata.json`
- `model/tfjs-archive-2026-05-12/weights.bin`
- `model/tfjs-archive-2026-05-12/tm-my-image-model.zip`

Not: Bu web export'u 12.05.2026 tarihli oldugu icin son surum olarak degil, eski export arsivi olarak tutulmustur.

## Klasorler

- `model/tflite/`: Mobil uygulamalar icin TFLite model dosyasi.
- `model/tfjs-archive-2026-05-12/`: Daha eski web export dosyalari.
- `samples/`: Modeli denemek icin ornek cicek fotograflari.
- `dataset/`: Egitimde kullanilan cicek fotograflarinin siniflara ayrilmis zip dosyalari.

## Egitim Veri Seti

Tum egitim fotograflari GitHub'a sinif bazli zip dosyalari olarak eklenmistir:

- `dataset/aycicegi.zip`: 139 fotograf
- `dataset/diger.zip`: 185 fotograf
- `dataset/kaktus.zip`: 168 fotograf
- `dataset/lale.zip`: 190 fotograf
- `dataset/menekse.zip`: 113 fotograf
- `dataset/orkide.zip`: 76 fotograf
- `dataset/papatya.zip`: 65 fotograf

Toplam: 936 fotograf.
