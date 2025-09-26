Intel Image Classification
Bu proje, [Intel Image Classification Dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) kullanılarak geliştirilmiştir.  
Amaç, altı farklı sınıfa (buildings, forest, glacier, mountain, sea, street) ait görüntülerin sınıflandırılmasıdır.
Kullanılan Yöntemler
- CNN tabanlı derin öğrenme modeli (Keras / TensorFlow)
- Veri artırma (ImageDataGenerator)
- Eğitim / Doğrulama ayrımı
- Model değerlendirme (accuracy, precision, recall, f1-score)
- Transfer learning ve Dropout kullanımı ile overfitting kontrolü

Metrikler ve Yorumlar
Aşağıda sınıflara göre detaylı sonuçlar verilmiştir:  

| Class      | Precision | Recall | F1-Score | Support |
|------------|-----------|--------|----------|---------|
| Buildings  | 0.92      | 0.91   | 0.91     | 437     |
| Forest     | 0.97      | 0.98   | 0.98     | 474     |
| Glacier    | 0.83      | 0.82   | 0.83     | 553     |
| Mountain   | 0.83      | 0.80   | 0.82     | 525     |
| Sea        | 0.88      | 0.89   | 0.89     | 510     |
| Street     | 0.89      | 0.93   | 0.91     | 501     |

- Model genel olarak sınıfları ayırt etmede oldukça başarılıdır.  
- Bazı sınıflarda iyileştirme için daha gelişmiş ağ mimarileri (ResNet, EfficientNet) veya ek veri artırma yöntemleri kullanılabilir.  
- Doğruluk, bu veri seti için güçlü bir başlangıç noktasıdır ve gerçek hayatta benzer sınıflandırma problemleri için kullanılabilir bir seviye sunmaktadır.  

Sonuç ve Gelecek Çalışmalar
Bu proje bootcamp kapsamında bir temel model oluşturmak ve transfer learning ile sınıflandırma başarısını göstermek amacıyla geliştirilmiştir. Gelecekte projeyi daha kaliteli hâle getirmek için şu yollar düşünülebilir:  
   - Daha güçlü mimariler: ResNet50, EfficientNet, Inception gibi modern CNN yapıları denenebilir.  
   - Hyperparameter tuning: learning rate, batch size, dropout oranı ve dense layer boyutları otomatik optimizasyon teknikleri ile optimize edilebilir.  
   - Veri seti daha da büyütülebilir veya farklı açılardan veri çoğaltma yöntemleri eklenebilir.  

Gelecek Kariyer Hedefleri
   - Derin öğrenme ve bilgisayarlı görü alanında ileri seviyeye geçiş için transfer learning ve explainable AI deneyimleri artırılabilir.  
   - Modeli daha büyük veri setleri ve farklı problem türleri (object detection, segmentation) ile genişletmek uzun vadeli hedefler arasında yer alabilir.

Linkler
- Kaggle Dataset: [Intel Image Classification](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)  
- Kaggle Notebook: [intel-multiclass-akbank](https://www.kaggle.com/code/sedanazdolu/intel-multiclass-akbank/edit)

Lisans
MIT License

