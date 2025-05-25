Diabetes-Health-Indicators
Bu projede, CDC (Amerika Hastalık Kontrol Merkezi) tarafından paylaşılan "Diabetes Health Indicators Dataset" verileri kullanılarak bireylerin diyabet riski tahmin edilmeye çalışılmıştır. Projede makine öğrenmesi yöntemleri kullanılmış ve veriler üzerinden bir model oluşturularak tahmin sistemi geliştirilmiştir.

Kullanılan Veri Seti
Veri seti Kaggle üzerinden alınmıştır. Toplam 70692 örnek ve 22 özellikten oluşmaktadır. Her satır bir bireyin sağlık geçmişi ve yaşam alışkanlıklarına ait bilgileri içermektedir.

Veri seti bağlantısı:
https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

Kullanılan Yöntemler
Keşifsel Veri Analizi (EDA)

Verilerin ön işlenmesi

StandardScaler ile ölçeklendirme

Makine öğrenmesi algoritmaları:

Logistic Regression

Random Forest

GridSearchCV ile hiperparametre optimizasyonu

Model değerlendirme metrikleri:

Accuracy

Confusion Matrix

ROC AUC

Sonuçlar
En iyi doğruluk oranı: %75

Logistic Regression ve Random Forest karşılaştırıldı.

ROC AUC skoru yaklaşık 0.74 seviyelerinde elde edildi.

Uygulama
Streamlit kullanılarak bir web arayüzü geliştirildi. Bu arayüz üzerinden kullanıcılar kendi sağlık bilgilerini girerek diyabet riski tahmininde bulunabilirler.
 
Web uygulaması bağlantısı:
https://diabetes-health-indicators-9dzaszu8sysov3aeszqbfz.streamlit.app/

Proje Dosyaları
Diabetes-Health-Indicators.ipynb – Veri analizi ve modelleme içeren Jupyter Notebook

app.py – Streamlit ile geliştirilen web uygulaması kodu

diabetes.csv – Kullanılan veri seti

requirements.txt – Kullanılan kütüphane listesi

Kaggle Proje Sayfası
https://www.kaggle.com/code/kardelen90/diabetes

Notu
Bu proje, veri bilimi öğrenme sürecimdeki ilk deneyimlerimden biri.
Yol boyunca pek çok şey öğrendim, eksiklerim olsa da her adımı kendim yapmaya çalıştım.
İleride bu projeyi geliştirmeyi ve daha fazlasını yapmayı hedefliyorum.
