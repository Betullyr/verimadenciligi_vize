# verimadenciligi_vize
# Malware Tespiti için Makine Öğrenimi Modeli

Bu proje, ağ trafiğindeki potansiyel malware etkinliklerini tespit etmek amacıyla geliştirilmiş bir makine öğrenimi modelini içermektedir.

## Kullanılan Teknolojiler ve Kütüphaneler

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Proje Açıklaması

Bu proje, bir malware tespiti veri seti üzerinde çalışan bir makine öğrenimi modelini içermektedir. Proje adımları şu şekildedir:

1. **Veri Yükleme ve Temizleme**: Veri seti, Pandas kullanılarak yüklenir ve eksik değerler temizlenir.

2. **Veri Ön İşleme ve Normalizasyon**: Veri seti üzerinde ön işleme adımları gerçekleştirilir. Eksik veriler doldurulur ve özellikler normalleştirilir.

3. **Model Seçimi ve Eğitimi**: Karar Ağaçları ve Rastgele Ormanlar modeli seçilir, Scikit-learn kullanılarak eğitilir.

4. **Model Değerlendirmesi**: Modelin performansı, confusion matrix ve doğruluk skoru üzerinden değerlendirilir.
