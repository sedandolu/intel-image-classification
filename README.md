# intel-image-classification# Intel Image Classification

Bu proje, [Intel Image Classification Dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) kullanılarak geliştirilmiştir.  
Amaç, altı farklı sınıfa (buildings, forest, glacier, mountain, sea, street) ait görüntülerin sınıflandırılmasıdır.

## Kullanılan Yöntemler
- CNN tabanlı derin öğrenme modeli (Keras / TensorFlow)
- Veri artırma (ImageDataGenerator)
- Eğitim / Doğrulama ayrımı
- Model değerlendirme (accuracy, precision, recall, f1-score)

## Sonuçlar
Model, test seti üzerinde **%88 doğruluk** elde etmiştir.

| Class      | Precision | Recall | F1-Score |
|------------|-----------|--------|----------|
| Buildings  | 0.88      | 0.93   | 0.90     |
| Forest     | 0.98      | 0.98   | 0.98     |
| Glacier    | 0.81      | 0.86   | 0.83     |
| Mountain   | 0.84      | 0.78   | 0.81     |
| Sea        | 0.88      | 0.89   | 0.88     |
| Street     | 0.94      | 0.89   | 0.91     |

**Overall Accuracy: 0.88**

## Gelecek Çalışmalar
- Daha derin mimariler (ResNet, EfficientNet) denenebilir.
- Hyperparameter tuning yapılabilir.
- Streamlit ile görselleştirme eklenebilir.

## Linkler
- Kaggle Dataset: [Intel Image Classification](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)
