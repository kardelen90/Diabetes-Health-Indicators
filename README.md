# 🩺 Diyabet Riski Tahmini – Diabetes Health Indicators

## 📌 Proje Hakkında
Bu projede, CDC (Amerika Hastalık Kontrol Merkezi) tarafından sağlanan **"Diabetes Health Indicators Dataset"** kullanılarak bireylerin diyabet riski tahmin edilmeye çalışılmıştır. Projede makine öğrenmesi yöntemleri ile bir sınıflandırma modeli geliştirilmiş ve web arayüzüyle kullanıcılara sunulmuştur.

## 📊 Kullanılan Veri Seti
- 📁 Veri Kaynağı: [Kaggle - Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)
- 📌 Gözlem Sayısı: 70.692
- 📌 Özellik Sayısı: 22  
Her satır, bir bireyin sağlık geçmişi ve yaşam tarzına dair bilgileri içermektedir.

## 🛠️ Kullanılan Yöntemler

### 🔍 Veri Analizi ve Ön İşleme
- Keşifsel Veri Analizi (EDA)
- Eksik değer kontrolü
- Encoding (kategorik değişkenler)
- StandardScaler ile ölçeklendirme

### 🧠 Makine Öğrenmesi Algoritmaları
- Logistic Regression
- Random Forest
- GridSearchCV ile hiperparametre optimizasyonu

### 📈 Model Değerlendirme Metrikleri
- Accuracy (Doğruluk)
- Confusion Matrix (Karışıklık Matrisi)
- ROC AUC
- F1-Score, Precision, Recall (geliştirme aşamasında eklenecek)

## ✅ Sonuçlar
- En iyi doğruluk oranı: **%75**
- Logistic Regression ve Random Forest algoritmaları karşılaştırıldı.
- ROC AUC skoru yaklaşık **0.74** seviyelerinde elde edildi.

## 🌐 Web Uygulaması
Streamlit kullanılarak geliştirilen bu web uygulaması üzerinden kullanıcılar kendi sağlık verilerini girerek diyabet riski tahmininde bulunabilirler.

🔗 [Uygulamayı Açmak İçin Tıklayın](https://diabetes-health-indicators-9dzaszu8sysov3aeszqbfz.streamlit.app/)

## 📁 Proje Dosyaları

| Dosya Adı | Açıklama |
|-----------|----------|
| `notebook/Diabetes-Health-Indicators.ipynb` | Veri analizi ve modelleme adımlarını içeren Jupyter Notebook |
| `app.py` | Streamlit ile geliştirilen web uygulama kodu |
| `data/diabetes.csv` | Kullanılan veri seti |
| `requirements.txt` | Kullanılan Python kütüphaneleri listesi |
| `images/` | Görseller: ROC eğrisi, karışıklık matrisi vb. |

## 📌 Kaggle Proje Sayfası
🔗 [Kaggle Notebook](https://www.kaggle.com/code/kardelen90/diabetes)

## 📝 Not
Bu proje, veri bilimi öğrenme sürecimdeki ilk deneyimlerden biridir. Yol boyunca çok şey öğrendim ve eksiklerime rağmen her adımı kendim yapmaya çalıştım. Gelecekte bu projeyi geliştirerek daha kapsamlı modeller oluşturmayı hedefliyorum.

