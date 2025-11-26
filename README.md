# Car-Prediction-Project-Araba-Fiyat-Tahmini

##  Problem Statement / Problem Tanımı

### 🚗 Project Overview / Proje Özeti

**EN:**
Estimating the price of a car is rarely straightforward. Brand value, technical specifications, engine power, fuel efficiency, and even design elements can significantly influence the final price tag. In this project, I aim to build a machine learning model capable of predicting car prices by analyzing these key factors.
This work serves as a hands-on introduction to automotive data analysis and predictive modeling.

**TR:**
Bir arabanın fiyatını belirlemek çoğu zaman kolay değildir. Marka değeri, teknik özellikler, motor gücü, yakıt verimliliği ve hatta tasarım gibi unsurlar fiyat üzerinde önemli bir etkiye sahiptir. Bu projede, bu temel faktörleri inceleyerek araba fiyatlarını tahmin edebilen bir makine öğrenimi modeli oluşturmayı hedefliyorum.
Bu çalışma, otomotiv verisi analizi ve tahmin modelleri konusunda pratik bir başlangıç niteliği taşır.

---

## 🎯 Key Objectives / Temel Hedefler

**EN:**

* Identify and analyze the variables that influence car pricing
* Build and train a machine learning model for price prediction
* Gain real-world experience in data preprocessing, feature engineering, and regression modeling

**TR:**

* Araba fiyatlarını etkileyen değişkenleri belirlemek ve analiz etmek
* Fiyat tahmini için bir makine öğrenimi modeli oluşturmak ve eğitmek
* Veri ön işleme, özellik mühendisliği ve regresyon modelleri üzerine pratik deneyim kazanmak

---

## 📘 Project Summary / Proje Özeti

### 🎯 Objective / Amaç

**EN:**
The goal of this project is to build a machine learning model that can predict car prices by analyzing several influential factors, such as brand reputation, engine power, features, and fuel efficiency.

**TR:**
Bu projenin amacı; marka değeri, motor gücü, özellikler ve yakıt verimliliği gibi çeşitli faktörleri analiz ederek araba fiyatlarını tahmin edebilen bir makine öğrenimi modeli geliştirmektir.

---

### 🚗 Why Car Price Prediction? / Neden Araba Fiyat Tahmini?

**EN:**
Car pricing depends on many variables, making it a suitable real-world problem for machine learning. By examining these variables, we can build a model that offers consistent and data-driven car price predictions.

**TR:**
Araba fiyatları birçok değişkene bağlı olduğundan, bu konu makine öğrenimi için gerçek hayatta karşılığı olan bir problem sunar. Bu değişkenleri analiz ederek tutarlı ve veriye dayalı fiyat tahmini yapabilen bir model oluşturabiliriz.

---

## 🧩 Key Tasks Aligned With Project Headings / Proje Başlıklarına Göre Ana Görevler

### 1. Understanding the Data / Veriyi Anlamak

**EN:** Examine the structure of the dataset, identify key attributes, and understand what each feature represents.

**TR:** Veri setinin yapısını inceleyerek temel özellikleri belirlemek ve her bir özniteliğin ne ifade ettiğini anlamak.

### 2. Exploring the Variables in the Dataset / Veri Setindeki Değişkenleri Keşfetmek

**EN:** Analyze the distribution of variables and inspect which attributes may influence car pricing.

**TR:** Değişkenlerin dağılımını analiz etmek ve hangi özniteliklerin araba fiyatlarını etkileyebileceğini incelemek.

### 3. Data Wrangling (Data Cleaning and Preparation) / Veri Temizleme ve Hazırlama

**EN:** Handle missing values, remove inconsistencies, and transform raw data into a usable format.

**TR:** Eksik verileri yönetmek, tutarsızlıkları gidermek ve ham veriyi kullanılabilir hale getirmek.

### 4. Exploring Relationships Between Variables Using Data Visualization / Veri Görselleştirmesi ile Değişkenler Arasındaki İlişkileri Keşfetmek

**EN:** Use visualization tools to discover correlations and interactions among key variables.

**TR:** Veri görselleştirme araçlarını kullanarak temel değişkenler arasındaki ilişkileri ve etkileşimleri ortaya çıkarmak.

### 5. Feature Engineering and Data Preprocessing / Öznitelik Mühendisliği ve Veri Ön İşleme

**EN:** Create new meaningful features, scale numerical data, encode categorical variables, and prepare the dataset for modeling.

**TR:** Yeni anlamlı öznitelikler oluşturmak, sayısal veriyi ölçeklendirmek, kategorik verileri kodlamak ve veri setini modellemeye hazırlamak.

### 6. Machine Learning Models and Explanations / Makine Öğrenimi Modelleri ve Açıklamaları

**EN:** Build and evaluate different machine learning models, compare their performance, and explain the logic behind each approach.

**TR:** Çeşitli makine öğrenimi modelleri oluşturmak ve değerlendirmek, performanslarını karşılaştırmak ve her yaklaşımın mantığını açıklamak.

---

## 🌟 Benefits / Kazanımlar

**EN:** Through this project, we gain practical experience in machine learning, data analytics, and automotive pricing. The final result is a functional car price prediction model that can support future pricing decisions or be expanded for more complex use cases.

**TR:** Bu proje sayesinde makine öğrenimi, veri analizi ve otomotiv fiyatlandırması konularında pratik deneyim edinmiş oluruz. Sonuç olarak, gelecekteki fiyatlandırma kararlarını destekleyebilecek veya daha karmaşık senaryolara uyarlanabilecek işlevsel bir araba fiyat tahmin modeli elde ederiz.

---

## ✅ Results / Sonuçlar

Below are the performance results of all machine learning models evaluated in this project.
Rather than relying only on Train and Test R² values, I used a more comprehensive set of regression metrics—**MSE, RMSE, MAE, Train R², Test R², and Adjusted R²**—to gain a deeper understanding of each model’s behavior.

Using multiple metrics together makes it much easier to detect issues such as **overfitting, underfitting, high variance**, or cases where a model performs extremely well during training but fails to generalize to unseen data.

During evaluation, I also identified and removed models that showed clear signs of overfitting (e.g., excessively high Train R², negative Test R² scores, or unrealistic error values).
After excluding these problematic models, the remaining results provide a more reliable comparison between the standard and tuned versions of each algorithm.

The final table below summarizes the complete performance profile of all regression models used in the Car Price Prediction project.

---
Bu projede değerlendirilen tüm makine öğrenimi modellerinin performans sonuçları aşağıda verilmiştir.
Sadece Train ve Test R² değerlerine bağlı kalmak yerine, her modelin davranışını daha detaylı görmek için **MSE, RMSE, MAE, Train R², Test R² ve Adjusted R²** gibi daha kapsamlı regresyon metrikleri kullandım.

Birden fazla metriği birlikte değerlendirmek; **aşırı öğrenme (overfitting), yetersiz öğrenme (underfitting), yüksek varyans** gibi problemleri ya da modelin eğitimde çok iyi performans gösterip testte genelleme yapamaması gibi durumları tespit etmeyi çok daha kolay hale getiriyor.

Değerlendirme sırasında, aşırı öğrenme belirtileri gösteren (örneğin çok yüksek Train R², negatif Test R² veya gerçekçi olmayan hata değerleri) modelleri belirleyip eledim.
Bu modelleri çıkardıktan sonra kalan sonuçlar, hem standart hem de iyileştirilmiş (tuned) algoritmalar arasında daha doğru bir karşılaştırma yapılmasını sağlıyor.

Aşağıdaki final tablo, Car Price Prediction projesinde kullanılan tüm regresyon modellerinin performans özetini sunmaktadır.

---

| Metric        | Linear Regression | Linear Regression (Tuned) | Ridge Regression | Ridge (Alpha=30) | Lasso Regression | Lasso (Alpha=0.01) | Decision Tree | Decision Tree (Tuned) | Random Forest | Random Forest (Tuned) | Gradient Boosting | Gradient Boosting (Tuned) |
|--------------|-------------------|----------------------------|------------------|------------------|------------------|---------------------|----------------|------------------------|----------------|-------------------------|---------------------|-----------------------------|
| **MSE**      | 3.877121 | 3.877121 | 3.878827 | 3.954513 | 11.146460 | 3.998941 | 0.697864 | 2.994610 | 0.471639 | 2.315361 | 0.728020 | 0.979039 |
| **RMSE**     | 1.969041 | 1.969041 | 1.969474 | 1.988596 | 3.338631 | 1.999735 | 0.835383 | 1.730494 | 0.686760 | 1.521631 | 0.853241 | 0.989464 |
| **MAE**      | 1.267639 | 1.267639 | 1.268640 | 1.310808 | 2.662008 | 1.288639 | 0.571311 | 1.138254 | 0.469212 | 1.020317 | 0.538582 | 0.630355 |
| **Train R²** | 0.625705 | 0.625705 | 0.625398 | 0.614584 | -0.099788 | 0.616224 | 1.000000 | 0.781167 | 0.985229 | 0.781827 | 0.985395 | 0.967486 |
| **Test R²**  | 0.571480 | 0.571480 | 0.571292 | 0.562927 | -0.231965 | 0.558016 | 0.922868 | 0.669020 | 0.947872 | 0.744094 | 0.919535 | 0.891791 |
| **Adjusted R²** | 0.475282 | 0.475282 | 0.475051 | 0.464808 | -0.508528 | 0.458795 | 0.905553 | 0.594719 | 0.936170 | 0.686646 | 0.901472 | 0.867500 |

---
## Conclusion

This project explores the automotive industry with the goal of predicting car prices using machine learning. By analyzing key features like fuel type, seller type, transmission, year, and ownership, we gain insights into market trends and consumer preferences.

**Key Insights:**

* The most popular car models in the dataset are **City, Corolla Altis, Verna, Fortuner, and Brio**.
* Cars from **2015, 2016, and 2014** are the most frequently sold.
* **Petrol** is the dominant fuel type, and **manual** transmission cars are more common than automatic ones.
* Cars sold by **dealers** usually have higher prices than those sold by individuals.
* **First-owner** cars tend to be more expensive, and cars with fewer kilometers sell for higher prices.
* **Diesel** vehicles generally have higher selling prices than petrol or CNG cars.

Several machine learning models were evaluated, and the **Random Forest Regressor** was selected for price prediction due to its strong performance. The model achieved **98% R² on training data** and **94% R² on testing data**, showing reliable generalization and suitability for practical applications.

This project highlights important factors influencing car prices and demonstrates the potential of machine learning in the automotive market, while also providing hands-on experience in data analysis and predictive modeling.

---
## Sonuç

Bu proje, otomotiv sektöründe araç fiyatlarını tahmin etmek amacıyla **makine öğrenmesi** yöntemlerini kullanmaktadır. Yakıt türü, satıcı tipi, vites türü, üretim yılı ve sahiplik gibi temel özellikler analiz edilerek piyasa trendleri ve tüketici tercihleri hakkında önemli bilgiler elde edilmiştir.

**Öne Çıkan Bulgular:**

* Veri setindeki en popüler modeller: **City, Corolla Altis, Verna, Fortuner ve Brio**.
* En çok satış yapılan yıllar: **2015, 2016 ve 2014**.
* **Benzinli** araçlar daha yaygın ve **manuel** vitesli araçlar otomatiklere göre daha fazla.
* **Bayiler** aracılığıyla satılan araçlar genellikle bireysel satıcılardan daha yüksek fiyatla alıcı buluyor.
* **İlk sahipli** araçlar daha yüksek fiyatlı, az kilometreli araçlar ise daha değerli.
* **Dizel** araçlar genellikle benzinli veya CNG araçlardan daha yüksek fiyatlara sahip.

Farklı makine öğrenmesi modelleri değerlendirildikten sonra, fiyat tahmini için **Random Forest Regressor** seçilmiştir. Model, **%98 eğitim R²** ve **%94 test R²** başarısı ile güvenilir bir performans göstermiştir.

Bu proje, araç fiyatlarını etkileyen önemli faktörleri ortaya koyarken, makine öğrenmesinin otomotiv sektöründe pratik uygulamalarda nasıl kullanılabileceğini de göstermektedir. Ayrıca veri analizi ve tahmin modelleme konularında değerli deneyim kazandırmaktadır.
