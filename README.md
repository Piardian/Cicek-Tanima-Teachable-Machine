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
