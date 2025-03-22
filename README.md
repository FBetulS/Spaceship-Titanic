# Spaceship-Titanic
# 🚀 Spaceship Titanic Projesi

Bu proje, Kaggle üzerindeki **[Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic/)** yarışmasına katılmayı amaçlamaktadır. Amacımız, uzay gemisinde meydana gelen bir felaket sonrası yolcuların hayatta kalma olasılıklarını tahmin eden bir makine öğrenimi modeli geliştirmektir.

## 📑 İçindekiler

- [🔧 Kurulum](#kurulum)
- [📦 Kullanılan Kütüphaneler](#kullanılan-kütüphaneler)
- [📊 Veri Seti](#veri-seti)
- [⚙️ Model Geliştirme Süreci](#model-geliştirme-süreci)
- [📈 Sonuçlar](#sonuçlar)
- [🏆 Yarışma Linki](#yarışma-linki)
- [👨‍💻 Katkıda Bulunanlar](#katkıda-bulunanlar)

---

## 🔧 Kurulum

Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

1. **Gerekli kütüphaneleri yükleyin**  
   ```bash
   pip install -r requirements.txt
📦 Kullanılan Kütüphaneler
Bu projede aşağıdaki Python kütüphaneleri kullanılmıştır:

pandas - Veri manipülasyonu için

numpy - Sayısal işlemler için

scikit-learn - Makine öğrenimi algoritmaları için

matplotlib & seaborn - Veri görselleştirme için

xgboost - Güçlü modelleme teknikleri için

📊 Veri Seti
Veri seti, yolcuların demografik ve seyahat bilgilerini içermektedir. Ana değişkenler:

PassengerId - Yolcu kimliği

HomePlanet - Yolcunun geldiği gezegen

CryoSleep - Yolcunun kriyojenik uykuda olup olmadığı

Cabin - Kabin numarası

Destination - Hedef gezegen

Age - Yolcunun yaşı

VIP - Yolcunun VIP olup olmadığı

Spending Features - Yolcunun harcamaları (RoomService, FoodCourt, ShoppingMall vb.)

Transported (Hedef Değişken) - Yolcunun hayatta kalıp kalmadığı (0 veya 1)

⚙️ Model Geliştirme Süreci
Projede aşağıdaki makine öğrenimi adımları izlenmiştir:

Veri Analizi ve Eksik Verilerin İşlenmesi

Eksik verilerin doldurulması

Veri görselleştirme ve istatistiksel analiz

Özellik Mühendisliği

Kategorik değişkenlerin sayısallaştırılması (One-Hot Encoding, Label Encoding)

Yeni değişkenler oluşturma ve özellik seçimi

Model Eğitimi
Kullanılan modeller:

RandomForestClassifier

XGBoostClassifier

Hiperparametre Optimizasyonu

GridSearchCV kullanılarak en iyi parametreler belirlendi

📈 Sonuçlar
En iyi modelin doğruluk skoru: 0.78863

Model, yolcuların hayatta kalma durumlarını başarılı bir şekilde tahmin etmektedir.

🏆 Yarışma Linki
📌 Yarışma sayfasına erişmek için:
🔗 Spaceship Titanic Yarışması
