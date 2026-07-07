#  Çiçek Türü Sınıflandırma (Flower Image Classification)

Bu proje, Derin Öğrenme  yöntemleri kullanılarak, yüklenen bir görselin 5 farklı çiçek türünden (Gül, Papatya, Lale, Ayçiçeği, Karahindiba) hangisine ait olduğunu tespit eden bir görüntü işleme  modelidir.

##  Proje Hakkında
`main.ipynb` içerisinde aşağıdaki aşamalar detaylıca işlenmiştir:
* Görüntülerin ön işlenmesi 
* Veri Artırma teknikleri
* Derin Öğrenme modelinin inşası ve eğitimi
* Yüklenen yeni fotoğraflar üzerinden canlı tahmin yapılması

##  Veri Seti ve Model Ağırlıkları
GitHub'ın dosya boyutu sınırlandırmaları nedeniyle, binlerce fotoğraftan oluşan orijinal çiçek veri seti ve eğitilmiş model dosyaları bu repoya yüklenmemiştir. Kodu kendi bilgisayarınızda çalıştırmak için veri setini aşağıdaki bağlantıdan indirebilirsiniz:
* https://www.kaggle.com/datasets/alxmamaev/flowers-recognition

##  Kurulum ve Kullanım
1. Veri setini indirin ve `main.ipynb` dosyasının bulunduğu dizine çıkartın.
2. Gerekli kütüphaneleri kurun (`pip install tensorflow keras opencv-python matplotlib`)
3. Jupyter Notebook üzerinden `main.ipynb` dosyasını çalıştırarak modeli eğitebilir veya kendi test fotoğraflarınızı modele tahmin ettirebilirsiniz.
