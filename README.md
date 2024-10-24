# Fish Classification Using Artificial Neural Networks

## Projenin Kaggle Linki

https://www.kaggle.com/code/berraoguz/fishclassification

## Proje Tanımı

Bu proje, bir balık sınıflandırma veri setini kullanarak derin öğrenme yöntemleri ile balık türlerini sınıflandırmayı amaçlamaktadır. Görsel verileri işlemek ve sınıflandırmak için bir Yapay Sinir Ağı (ANN) modeli geliştirilmiştir. Proje, balıkların farklı türlerini tanımak için makine öğrenimi tekniklerinin nasıl uygulanabileceğine dair bir örnek sunmaktadır.

## Kullanılan Teknolojiler

- **Python**: Projenin temel programlama dili.
- **TensorFlow & Keras**: Derin öğrenme modeli oluşturmak için kullanıldı.
- **Pandas**: Veri analizi ve manipülasyonu için.
- **Matplotlib & Seaborn**: Veri görselleştirmeleri oluşturmak için.
- **Scikit-Learn**: Model değerlendirmesi ve metrik hesaplamaları için.

## Veri Seti

Proje, [A Large-Scale Fish Dataset](https://www.kaggle.com/datasets/zaffar/large-scale-fish-dataset) adlı Kaggle veri setini temel alıyor. Bu veri seti, çeşitli balık türlerine ait yüzlerce görüntü içermekte ve sınıflandırma problemlerine yönelik gerçek bir senaryo sunmaktadır.

## Proje Aşamaları

1. **Veri Önişleme**: Veri seti yüklendi ve etiketler ile dosya yolları bir DataFrame'e dönüştürüldü.
2. **Veri Görselleştirme**: Rastgele bir balık görüntüsü gösterilerek, veri setinin genel yapısı gözlemlendi.
3. **Eğitim ve Test Setine Ayırma**: Veriler, modelin eğitimi ve test edilmesi için iki ayrı gruba ayrıldı.
4. **Model Eğitimi**: Yapay sinir ağı modeli oluşturuldu ve eğitim verisi kullanılarak eğitildi.
5. **Model Değerlendirmesi**: Test verileri ile modelin başarısı ölçüldü; confusion matrix ve classification report ile sonuçlar analiz edildi.
6. **Görselleştirme**: Eğitim sürecindeki kayıplar grafikleştirildi.

## Sonuçlar

Model, test setinde yüksek doğruluk oranları elde etti. Eğitim süreci boyunca kayıplar gözlemlendi ve grafikler aracılığıyla modelin performansı değerlendirildi. Bu proje, derin öğrenme uygulamalarının gerçek dünya problemlerine nasıl uygulanabileceği konusunda önemli bir örnektir.

## Kurulum Talimatları

Projenin çalışabilmesi için gerekli Python kütüphanelerinin yüklenmesi gerekmektedir. Aşağıdaki komutları terminalde çalıştırarak gerekli kütüphaneleri yükleyebilirsiniz:

```bash
pip install tensorflow pandas matplotlib seaborn scikit-learn
