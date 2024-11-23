# global_ai_hub_adult_dataset

# **Adult Dataset Analizi**

Bu proje, **Adult Dataset** üzerinde veri analizi yapmayı amaçlamaktadır. Projede, eksik değerlerin işlenmesi, aykırı değerlerin ele alınması, özellik mühendisliği ve veri görselleştirme gibi temel veri analitiği adımları uygulanmıştır.

---

## Kullanılan Kütüphaneler

Bu projede aşağıdaki Python kütüphaneleri kullanılmıştır:

1. **pandas**: Veri manipülasyonu ve analizi için.
2. **numpy**: Sayısal hesaplamalar ve dizilerle çalışma için.
3. **matplotlib**: Grafikler ve görselleştirme için.
4. **seaborn**: Veri görselleştirmeleri için.
5. **missingno**: Eksik veri analizi ve görselleştirme için.
6. **scikit-learn**: Makine öğrenmesi modelleri ve veri işleme araçları için.

---

## **İçindekiler**

1. [Veri Setinin Hazırlanması](https://www.kaggle.com/code/cemrebasakkilic/global-ai-hub#Global-AI-Hub-Proje-%7C-Adult-Veri-Seti)
2. [Veriye İlk Bakış](https://www.kaggle.com/code/cemrebasakkilic/global-ai-hub#Veriye-%C4%B0lk-Bak%C4%B1%C5%9F)
3. [Eksik Veri Analizi](https://www.kaggle.com/code/cemrebasakkilic/global-ai-hub#Eksik-Veri-Analizi)
4. [Aykırı Değer Analizi](https://www.kaggle.com/code/cemrebasakkilic/global-ai-hub#Ayk%C4%B1r%C4%B1-De%C4%9Fer-Analizi)
5. [Sayısal ve Kategorik Değişken Analizi](https://www.kaggle.com/code/cemrebasakkilic/global-ai-hub#Say%C4%B1sal-ve-Kategorik-De%C4%9Fi%C5%9Fken-Analizi)
6. [Feature Engineering (Özellik Mühendisliği)](https://www.kaggle.com/code/cemrebasakkilic/global-ai-hub#Feature-Engineering)

---

## **Veri Setinin Hazırlanması**

Proje, Kaggle üzerinde bulunan **Adult Dataset** kullanılarak gerçekleştirilmiştir. Bu veri seti, bireylerin demografik bilgilerini ve gelir durumlarını içermektedir. Veri seti yüklenmiş ve analiz için gerekli olan kütüphaneler ile temel hazırlıklar yapılmıştır.

---

## **Veriye İlk Bakış**

Veri setine genel bir bakış atılmış; sütun isimleri, veri türleri ve temel istatistiksel bilgiler incelenmiştir. Bu aşamada veri setindeki eksik değerler, kategorik ve sayısal değişkenler ile ilgili ilk gözlemler yapılmıştır.

---

## **Eksik Veri Analizi**

Eksik değerlerin tespiti için hem sayısal hem görsel analizler yapılmıştır. Eksik veriler, uygun doldurma yöntemleri (ör. medyan, ortalama, mod) kullanılarak ele alınmıştır.

---

## **Aykırı Değer Analizi**

Aykırı değerler tespit edilerek, **IQR (Interquartile Range)** yöntemiyle sınır değerlerin dışına çıkan veriler incelenmiş ve gerekli durumlarda ayarlanmıştır.

---

## **Sayısal ve Kategorik Değişken Analizi**

Sayısal değişkenler için istatistiksel analizler ve dağılım grafikleri oluşturulmuştur. Kategorik değişkenler ise **countplot** görselleştirmeleri ile analiz edilmiştir. Gelir durumu gibi hedef değişkenlere göre farklı kategorilerin davranışları incelenmiştir.

---

## **Feature Engineering (Özellik Mühendisliği)**

Yeni değişkenler oluşturularak veri seti zenginleştirilmiştir. Haftalık çalışma saati aralıklarına göre kategorik bir değişken olan `hours_category` türetilmiştir. Ayrıca, gereksiz veya düşük bilgi değerine sahip sütunlar veri setinden kaldırılmıştır.

---

Bu proje, veri analitiği süreçlerinde kullanılabilecek adımları uygulamalı bir şekilde göstermektedir. Elde edilen sonuçlar, veri setinin içgörülerini anlamak ve gelecekteki modelleme süreçlerine zemin hazırlamak için değerlidir.

---
## Ortam ve Kullanım Talimatları  

Bu proje Python programlama dili kullanılarak geliştirilmiştir. 

---

### Geliştirme Ortamı    
- **Geliştirme Ortamı**: Jupyter Notebook veya herhangi bir IDE (PyCharm, VSCode vb.)  

### Gereksinimler  
Projeyi çalıştırmadan önce yukarıda bahsedilen kütüphanelerin kurulu olduğundan emin olun.

---

### Kaggle Proje Linki
- [Kaggle Proje Linki](https://www.kaggle.com/code/cemrebasakkilic/global-ai-hub)
