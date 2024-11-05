# Multiple-Lineer-Regression-HousePrice
Çoklu Lineer Regresyon ile Ev Fiyat Tahmini
Bu proje, çeşitli özelliklere (ortalama gelir, ev yaşı, oda sayısı ve diğer sosyo-ekonomik faktörler) dayanarak Çoklu Lineer Regresyon kullanarak ev fiyatlarını tahmin eden bir makine öğrenmesi çalışmasıdır.

Proje Yapısı
Veri Ön İşleme:

House Age, Number of Rooms, Number of Bedrooms gibi özellikler, tutarlılık sağlamak amacıyla tam sayı tipine dönüştürüldü.
Address (Adres) sütunu, modellemede uyumluluk için sayısal hale getirildi.
Price (Fiyat) tam sayıya çevrilerek net bir karşılaştırma yapılması sağlandı.
Keşifsel Veri Analizi (EDA):

Özellikler arasındaki ilişkileri ve fiyat üzerindeki etkilerini anlamak için bir korelasyon matrisi oluşturuldu.
Seaborn kütüphanesi kullanılarak korelasyon haritası ile görselleştirme yapıldı.
Modelleme:

Scikit-Learn kütüphanesinin LinearRegression sınıfı kullanılarak Çoklu Lineer Regresyon modeli oluşturuldu.
Veriyi eğitim ve test setlerine ayırarak model performansını değerlendirmek için eğitim yapıldı.
Değerlendirme:

Modelin doğruluğu, Mean Squared Error (MSE) ve R-squared (R²) ile ölçüldü.
Gerçek ve tahmin edilen fiyatlar yan yana görüntülenerek modelin başarısı incelendi.
Görselleştirme:

Gerçek fiyatlarla tahmin edilen fiyatlar karşılaştırmalı olarak çizdirildi.
Kullanılan Başlıca Kütüphaneler
pandas: Veri manipülasyonu ve analiz.
scikit-learn: Model oluşturma ve değerlendirme.
seaborn ve matplotlib: Veri görselleştirme.
Sonuçlar
Model aşağıdaki metriklerle değerlendirildi:

Mean Squared Error (MSE): Tahmin edilen ve gerçek değerler arasındaki ortalama kare farkını gösterir.
R-squared (R²): Bağımlı değişkendeki varyansın bağımsız değişkenlerle ne kadar açıklanabildiğini gösterir.


![indir](https://github.com/user-attachments/assets/322f90ed-729c-4e98-9fd0-0c06e6361e45)

