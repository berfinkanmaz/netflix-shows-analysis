# Netflix İçerik Analizi Projesi

Bu proje, Netflix'in içerik kataloğundaki film ve TV şovlarını analiz ederek tür dağılımları, puanlar ve yayın trendleri gibi önemli bilgileri görselleştirmektedir.

## 📊 Proje Hakkında
- **Veri Kümesi**: 20.601 satır ve 8 sütundan oluşmaktadır.
- **Ana Odak**: Tür dağılımları, IMDB puanları ve yıllık içerik trendleri.
- **Kullanılan Araçlar**: Python, Jupyter Notebook, Pandas, Matplotlib, Seaborn.

## 🔍 Temel Gözlemler
1. **Veri Yapısı**:
   - **Boş Değerler**: `imdbAverageRating` ve `imdbNumVotes` en yüksek boş değer oranına sahip.
   - **Yinelenen Satırlar**: 105 adet yinelenen satır tespit edildi.
   
2. **İçerik Dağılımı**:
   - **Filmler**: %75
   - **TV Şovları**: %23

3. **Tür Analizi**:
   - **Toplam Tür**: 37 benzersiz tür.
   - **En Popüler Türler**: 
     - Dram (9468 içerik)
     - Komedi (7189 içerik)
   - **En Yüksek Puanlı Türler**:
     1. Belgesel (6.95)
     2. Biyografi (6.93)
     3. Tarih (6.91)

4. **Zaman Trendleri**:
   - 2006'da 270 içerik → 2022'de 1969 içerik (belirgin artış).

## 📂 Dosyalar
- `netflix_analysis.ipynb`: Analiz kodlarını içeren Jupyter Notebook.
- `netflix_watch.csv`: Ham veri seti.
- `requirements.txt`: Gerekli Python kütüphaneleri.

## 🛠️ Kullanılan Teknolojiler
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
