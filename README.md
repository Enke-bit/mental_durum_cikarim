# Karar Ağacı (CART) Modeli ile Ruh Hali Tahmini

Bu proje, çeşitli faktörlere dayanarak ruh hali dalgalanmalarını tahmin etmeyi amaçlamaktadır. Bunun için bir Karar Ağacı Sınıflandırıcısı (CART modeli) kullanılmıştır. Veri seti, yaş, cinsiyet, meslek, kapalı alanda geçirilen gün sayısı, artan stres seviyeleri ve daha fazlasını içeren çeşitli özellikleri içermektedir.

## Veri Seti

`mental_health_finaldata_1.csv` adlı veri seti aşağıdaki sütunları içermektedir:

- `Age`
- `Gender`
- `Occupation`
- `Days_Indoors`
- `Growing_Stress`
- `Quarantine_Frustrations`
- `Changes_Habits`
- `Mental_Health_History`
- `Weight_Change`
- `Mood_Swings` (hedef değişken)
- `Coping_Struggles`
- `Work_Interest`
- `Social_Weakness`

## Proje Yapısı

- `mood_prediction_with_visuals.py`: Veriyi işleyen, modeli eğiten ve görselleştirmeler oluşturan ana script.
- `mental_health_finaldata_1.csv`: Eğitim ve değerlendirme için kullanılan veri seti.
- `README.md`: Proje dokümantasyonu.

## Gereksinimler

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Gerekli paketleri pip kullanarak yükleyebilirsiniz:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn

## Veri Yükleme ve Ön İşleme:

Veri setini yükler.
Kategorik değişkenleri Label Encoding kullanarak sayısal değerlere dönüştürür.
Keşifsel Veri Analizi (EDA):

## Veri seti hakkında temel istatistikleri ve bilgileri görüntüler.
Hedef değişken Mood_Swings dağılımını görselleştirir.
Özellikler arasındaki korelasyonları göstermek için bir ısı haritası çizer.
Model Eğitimi ve Değerlendirme:

## Veriyi eğitim ve test setlerine böler.
Eğitim verileri üzerinde bir Karar Ağacı Sınıflandırıcısı eğitir.
Modeli test verileri üzerinde değerlendirir ve doğruluk ile sınıflandırma raporunu yazdırır.
Karar Ağacını görselleştirir.
Karışıklık Matrisini çizer.

## Görselleştirmeler
- Mood Swings Dağılımı:

- Özellik Korelasyon Matrisi:

- Karar Ağacı Görselleştirmesi:

- Karışıklık Matrisi:

- Katkıda Bulunma

## Bu depoyu forklayarak ve pull request göndererek katkıda bulunabilirsiniz. Büyük değişiklikler için lütfen önce neyi değiştirmek istediğinizi tartışmak üzere bir konu açın.
