# Lasso Regresyon ile California Housing Veri Seti Üzerinde Tahmin

Bu proje, **California Housing** veri seti üzerinde **Lasso Regresyon** kullanarak ev fiyatlarını tahmin etmektedir.

VERİ SETİ

Veri seti scikit-learn içinde bulunan California Housing veri setidir. Bu veri seti, Kaliforniya'da 1990'larda ABD nüfus sayımında toplanan bölgesel demografik ve ekonomik bilgilerle ev fiyatlarını içermektedir.

Veri setinde aşağıdaki özellikler bulunmaktadır:

MedInc: Medyan gelir

HouseAge: Evlerin yaşı

AveRooms: Ortalama oda sayısı

AveBedrms: Ortalama yatak odası sayısı

Population: Nüfus

AveOccup: Ev başına düşen ortalama kişi sayısı

Latitude: Enlem

Longitude: Boylam

Target: Medyan ev fiyatı (bağımlı değişken)


Proje Yapısı

Veri Yükleme:
Scikit-learn'den California Housing veri seti yüklenir.

Veriyi Hazırlama:
Bağımsız değişkenler (X) ve bağımlı değişken (y) ayrılır.
Veriyi eğitim ve test setlerine ayırılır (%70 eğitim, %30 test).

Model Eğitimi:
Farklı alfa değerleri ile Lasso Regresyon modeli oluşturulur ve eğitilir.

Model Değerlendirmesi:
Model test seti üzerinde tahmin yapar ve sonuçlar Mean Squared Error (MSE), Mean Absolute Error (MAE) ve R² ile değerlendirilir.
