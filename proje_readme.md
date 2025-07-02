
# 🛍️ Mall Customer Segmentation Project

## 📊 Proje Açıklaması

Bu proje, alışveriş merkezi müşterilerinin **yıllık gelirleri** ve **harcama alışkanlıkları** gibi demografik özelliklerine göre segmentlere ayrılması amacıyla geliştirilmiştir. Projede, **K-Means Kümeleme Algoritması** kullanılarak pazarlama stratejilerine yön verecek müşteri kümeleri oluşturulmuştur.

Veri seti: [Kaggle – Mall Customers Dataset](https://www.kaggle.com/datasets/shwetabh123/mall-customers)

---

## 🧰 Kullanılan Teknolojiler

- Python 3.x
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Proje Dosyaları

- `mall_costumer_analizing_project.ipynb`  
  Projenin tüm adımlarını içeren Jupyter Notebook dosyası.

---

## 🔍 Proje Adımları

1. **Veri Yükleme ve Ön İnceleme**
   - İlk 5 kayıt, eksik değer kontrolü, temel istatistikler
2. **Veri Görselleştirme**
   - Yaş, gelir ve harcama skorlarının dağılımları
   - Cinsiyet, yaş ve skor ilişkileri
3. **Elbow Method ile Küme Sayısı Belirleme**
   - Farklı `k` değerlerine göre WCSS hesaplama
4. **K-Means Kümeleme**
   - En uygun küme sayısına göre segmentlerin belirlenmesi
5. **Küme Görselleştirmesi**
   - Scatter plot ile müşteri kümelerinin görselleştirilmesi

---

## 📌 Nasıl Çalıştırılır?

1. Python ortamınızda gerekli kütüphaneleri yükleyin:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. Jupyter Notebook'u açın:
   ```bash
   jupyter notebook
   ```

3. `mall_costumer_analizing_project.ipynb` dosyasını çalıştırarak tüm hücreleri sırayla çalıştırın.

---

## 📈 Sonuçlar

- Müşteriler 5 farklı segmente ayrıldı.
- Harcama skoruna göre düşük ve yüksek potansiyelli müşteri grupları görselleştirildi.
- Pazarlama stratejileri için hangi segmentlerin hedeflenmesi gerektiği analiz edildi.

---

## 📎 Lisans

Bu proje eğitim amaçlıdır. Veri seti Kaggle üzerinden herkese açık olarak paylaşılmıştır.
