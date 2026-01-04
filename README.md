# Nested JSON to CSV Converter 🔄

Bu proje, karmaşık ve iç içe geçmiş (nested) yapıdaki JSON verilerini, veri analizi ve işlemeye uygun düz (flat) CSV formatına dönüştürmek için geliştirilmiştir. Proje içerisinde hem popüler veri bilimi kütüphanesi **Pandas** ile hem de **saf (native) Python** yöntemleriyle iki farklı çözüm sunulmaktadır.

## 🚀 Proje Hakkında

Veri mühendisliği ve veri analitiği süreçlerinde, API'lardan veya NoSQL veritabanlarından gelen veriler genellikle iç içe geçmiş JSON formatındadır. Bu verileri ilişkisel veritabanlarına yüklemek veya analiz etmek için "düzleştirmek" gerekir.

Bu notebook şu iki yaklaşımı göstermektedir:
1.  **Pandas Yaklaşımı:** `json_normalize` fonksiyonu kullanılarak hızlı ve etkili dönüşüm.
2.  **Manuel Python Yaklaşımı:** Rekürsif fonksiyonlar kullanılarak, kütüphane bağımlılığı olmadan özel bir düzleştirme algoritması.

## 📂 Dosya Yapısı

* `nestedJson_to_csv.ipynb`: Dönüştürme kodlarını içeren Jupyter Notebook dosyası.
* `indir.json`:proej için random değer üreten wb site url = https://randomuser.me/api/?results=50
* `output.csv`: Pandas yöntemi ile üretilen çıktı dosyası.
* `output_manual.csv`: Manuel Python fonksiyonu ile üretilen çıktı dosyası.

