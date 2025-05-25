# Diabetes-Health-Indicators


Bu projede, CDC (Amerika Hastalık Kontrol Merkezi) tarafından paylaşılan "Diabetes Health Indicators Dataset" verileri kullanılarak bireylerin diyabet riski tahmin edilmeye çalışılmıştır. Projede makine öğrenmesi yöntemleri kullanılmış ve veriler üzerinden model oluşturularak bir tahmin sistemi geliştirilmiştir.

Kullanılan Veri Seti
Veri seti Kaggle üzerinden alınmıştır. Toplam 70692 adet örnek ve 22 özellikten oluşmaktadır. Veri seti her bireyin sağlık geçmişi ve yaşam alışkanlıklarına dair bilgileri içermektedir.
Veri seti bağlantısı:
https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

Kullanılan Yöntemler
Keşifsel Veri Analizi (EDA)

Verilerin ön işlenmesi

StandardScaler ile ölçeklendirme

Makine öğrenmesi algoritmaları (Logistic Regression, Random Forest)

GridSearchCV ile hiperparametre optimizasyonu

Başarı metrikleri: Accuracy, Confusion Matrix, ROC AUC

Sonuçlar
En iyi doğruluk oranı: %75

Logistic Regression ve Random Forest sonuçları karşılaştırılmıştır.

ROC AUC skorları 0.74 seviyelerinde çıkmıştır.

Uygulama
Streamlit kullanılarak bir web arayüzü geliştirilmiştir. Bu arayüz ile kullanıcılar kendi sağlık bilgilerini girerek diyabet riski tahmininde bulunabilirler.

Web uygulamasına ulaşmak için:
[https://your-streamlit-link.streamlit.app](https://diabetes-health-indicators-9dzaszu8sysov3aeszqbfz.streamlit.app/)

Diğer Dosyalar
.ipynb uzantılı Jupyter Notebook: Veri analizi ve modelleme adımlarını içerir.

app.py: Streamlit ile oluşturulan web uygulamasının kodudur.

heart.csv veya diabetes.csv: Kullanılan veri setidir.

requirements.txt: Kullanılan kütüphaneleri içerir.

Kaggle Proje Sayfası
Projeye Kaggle üzerinden aşağıdaki bağlantıdan ulaşabilirsiniz:
[https://www.kaggle.com/code/kardelen90/diabetes](https://www.kaggle.com/code/kardelen90/diabetes)

