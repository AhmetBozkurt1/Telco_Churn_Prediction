<img width="1100" alt="Ekran Resmi 2024-06-20 16 36 13" src="https://github.com/AhmetBozkurt1/Salary_Predict_with_Machine_Learning/assets/120393650/dada04c5-9dd0-4909-a4e7-a4e2b4896dfc">

# TELCO CHURN PREDICTION

### İŞ PROBLEMİ
☞ Şirketi terk edecek müşterileri tahmin edebilecek bir makine öğrenmesi modeli geliştirilmesi beklenmektedir.Telco müşteri kaybı verileri, üçüncü çeyrekte Kaliforniya'daki 7043 müşteriye ev telefonu ve İnternet hizmetleri sağlayan hayali bir telekom şirketi hakkında bilgi içerir. Hangi müşterilerin hizmetlerinden ayrıldığını, kaldığını veya hizmete kaydolduğunu gösterir.

### VERİ SETİ HİKAYESİ
☞ Telco müşteri kaybı verileri, üçüncü çeyrekte Kaliforniya'daki 7043 müşteriye ev telefonu ve İnternet hizmetleri sağlayan hayali bir telekom şirketi hakkında bilgi içerir. Hangi müşterilerin hizmetlerinden ayrıldığını, kaldığını veya hizmete kaydolduğunu gösterir.

### DEĞİŞKENLER
- **CustomerId:** Müşteri İd’si
- **Gender:** Cinsiyet
- **SeniorCitizen:** Müşterinin yaşlı olup olmadığı (1, 0)
- **Partner:** Müşterinin bir ortağı olup olmadığı (Evet, Hayır)
- **Dependents:** Müşterinin bakmakla yükümlü olduğu kişiler olup olmadığı (Evet, Hayır
- **tenure:** Müşterinin şirkette kaldığı ay sayısı
- **PhoneService:** Müşterinin telefon hizmeti olup olmadığı (Evet, Hayır)
- **MultipleLines:** Müşterinin birden fazla hattı olup olmadığı (Evet, Hayır, Telefon hizmeti yok)
- **InternetService:** Müşterinin internet servis sağlayıcısı (DSL, Fiber optik, Hayır)
- **OnlineSecurity:** Müşterinin çevrimiçi güvenliğinin olup olmadığı (Evet, Hayır, İnternet hizmeti yok)
- **OnlineBackup:** Müşterinin online yedeğinin olup olmadığı (Evet, Hayır, İnternet hizmeti yok)
- **DeviceProtection:** Müşterinin cihaz korumasına sahip olup olmadığı (Evet, Hayır, İnternet hizmeti yok)
- **TechSupport:** Müşterinin teknik destek alıp almadığı (Evet, Hayır, İnternet hizmeti yok)
- **StreamingTV:** Müşterinin TV yayını olup olmadığı (Evet, Hayır, İnternet hizmeti yok)
- **StreamingMovies:** Müşterinin film akışı olup olmadığı (Evet, Hayır, İnternet hizmeti yok)
- **Contract:** Müşterinin sözleşme süresi (Aydan aya, Bir yıl, İki yıl)
- **PaperlessBilling:** Müşterinin kağıtsız faturası olup olmadığı (Evet, Hayır)
- **PaymentMethod:** Müşterinin ödeme yöntemi (Elektronik çek, Posta çeki, Banka havalesi (otomatik), Kredi kartı (otomatik))
- **MonthlyCharges:** Müşteriden aylık olarak tahsil edilen tutar
- **TotalCharges:** Müşteriden tahsil edilen toplam tutar
- **Churn:** Müşterinin kullanıp kullanmadığı (Evet veya Hayır)

### MODEL OLUŞTURMA
- Veri seti keşfedilir ve özelliklerin analizi yapılır.
- Eksik veriler ve aykırı değerler işlenir.
- Özellik mühendisliği adımlarıyla yeni özellikler türetilir.
- Kategorik değişkenler sayısal formata dönüştürülür.
- Model seçimi yapılır ve hiperparametre optimizasyonu gerçekleştirilir.
- En iyi modelin performansı değerlendirilir.


### Gereksinimler
☞ Bu proje çalıştırılmak için aşağıdaki kütüphanelerin yüklü olması gerekmektedir:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- optuna
- lightgbm
- xgboost
- catboost

### Kurulum
☞ Projeyi yerel makinenizde çalıştırmak için şu adımları izleyebilirsiniz:

- GitHub'dan projeyi klonlayın.
- Projeyi içeren dizine gidin ve terminalde `conda env create -f environment.yaml` komutunu çalıştırarak gerekli bağımlılıkları yükleyin.
- Derleyicinizi `conda` ortamına göre ayarlayın.
- Projeyi bir Python IDE'sinde veya Jupyter Notebook'ta açın.
