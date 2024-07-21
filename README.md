# Diabetes Prediction Models

## Proje Açıklaması

Bu proje, diyabet hastalığını tahmin etmek için çeşitli makine öğrenmesi modellerini karşılaştırmak ve performanslarını değerlendirmek amacıyla oluşturulmuştur. Projede, veri yükleme, görselleştirme, model eğitimi ve performans analizi adımlarını içerir. Aşağıdaki modeller değerlendirilmiştir:

- K-Nearest Neighbors
- Random Forest
- Gradient Boosting
- Logistic Regression
- Support Vector Machine
- Decision Tree
- Naive Bayes
- XGBoost
- CatBoost

## İçindekiler

- [Veri Yükleme ve Ön İşleme](#veri-yükleme-ve-ön-i%CC%87sleme)
- [Veri Görselleştirme](#veri-görselleştirme)
- [Korelasyon ve Kovaryans Analizi](#korelasyon-ve-kovaryans-analizi)
- [Model Eğitim ve Performans Analizi](#model-eğitim-ve-performans-analizi)
- [Sonuçlar ve Performans Karşılaştırması](#sonuçlar-ve-performans-karşılaştırması)


## Veri Yükleme ve Ön İşleme

Veri kümesi `diabetes.csv` dosyasından yüklenir ve eksik veri kontrolü ile ön işleme adımları gerçekleştirilir.

## Veri Görselleştirme

Veri, çeşitli grafik türleri kullanılarak görselleştirilir:
- Histogramlar
  
  ![Screenshot from 2024-07-21 21-24-55](https://github.com/user-attachments/assets/ebe38b5b-642b-48c3-af75-b813b8b9cbf1)

- Scatter Plot

  ![Screenshot from 2024-07-21 21-25-41](https://github.com/user-attachments/assets/161c55f5-654c-4e4f-b4fc-b7a62f11ee9c)

- Box Plot

  ![Screenshot from 2024-07-21 21-26-11](https://github.com/user-attachments/assets/d86a71d9-fb2d-4a28-bf4d-960f1e3b57ee)

- Pie Chart

  ![Screenshot from 2024-07-21 21-26-59](https://github.com/user-attachments/assets/f38500ea-fb35-4ad1-833d-baa7d07b8da7)


## Korelasyon ve Kovaryans Analizi

Veri setinin korelasyon ve kovaryans matrisleri ısı haritaları (heatmap) ile görselleştirilir.

-Korelasyon

![Screenshot from 2024-07-21 21-27-58](https://github.com/user-attachments/assets/d182b317-9a9d-472c-87cc-ef1d210e95d5)

-Kovaryans

![Screenshot from 2024-07-21 21-29-07](https://github.com/user-attachments/assets/edcfc2bf-08ed-40f5-9870-f89032c29912)


## Model Eğitim ve Performans Analizi

Çeşitli makine öğrenmesi modelleri eğitilir ve validasyon ile test setlerinde performansları değerlendirilir. Performans metrikleri:
- F1 Skoru
- Precision
- Recall
- Accuracy

## Sonuçlar ve Performans Karşılaştırması

Her modelin test setindeki performansları karşılaştırılır ve en iyi performansı gösteren modeller belirlenir. Sonuçlar, `tabulate` kütüphanesi kullanılarak tablo şeklinde sunulur.


![Screenshot from 2024-07-21 21-29-54](https://github.com/user-attachments/assets/6dd2d4c3-ab72-4c20-b15c-357904baaf8e)

