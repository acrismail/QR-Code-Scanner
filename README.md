# QR Kod Tarayıcı

Bu proje, Python ve OpenCV kullanılarak QR kodlarını algılayıp çözümleyen bir uygulamadır. Uygulama, görüntüden QR kodunu algılar, ilgili veriyi çözer ve görselleştirir. Ayrıca, QR kodunun köşe noktalarını ve doğrularını çizerek algılama sürecini kullanıcıya sunar.

## Özellikler

- **QR Kod Algılama**: Görüntüden QR kodlarını algılar.
- **Veri Çözümleme**: QR kodu çözümleyerek içeriği terminalde gösterir.
- **Görselleştirme**: QR kodunun algılanan bölgelerini işaretler ve doğruları çizer.
- **Matplotlib Entegrasyonu**: Algılanan QR kodunun ve düzleştirilmiş versiyonunun görselleştirilmesi.

---

## Gereksinimler

Projenin çalışması için aşağıdaki yazılımlar ve kütüphaneler gereklidir:

- **Python 3.x**
- **OpenCV**
- **NumPy**
- **Matplotlib**

Gerekli Python kütüphanelerini yüklemek için aşağıdaki komutu kullanabilirsiniz:

pip install opencv-python 
numpy matplotlib

## Çalışma Prensibi
1.QR Kod Algılama:OpenCV'nin QRCodeDetector sınıfı kullanılarak QR kodu algılanır ve çözümleme yapılır.

2.Köşe Noktalarının Çizimi:Algılanan QR kodunun köşe noktaları tespit edilir ve işaretlenir.

3.Matplotlib ile Görselleştirme:QR kodun orijinal ve düzleştirilmiş versiyonu Matplotlib ile gösterilir.






