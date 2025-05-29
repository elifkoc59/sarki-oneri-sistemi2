# Şarkı Öneri Sistemi - NLP Final Proje

Bu proje, Doğal Dil İşleme (NLP) dersi kapsamında hazırlanmış bir şarkı öneri sistemidir. Projede, şarkı sözleri üzerinden TF-IDF ve Word2Vec modelleri eğitilerek benzer şarkılar önerilmektedir. Hem lemmatized hem de stemmed verilerle ayrı ayrı analiz yapılmıştır.

---

## 📁 Proje Dosya Yapısı

```
project_root/
│
├── lyrics_analysis.ipynb         # Tüm işlemlerin yapıldığı Jupyter Notebook
├── lemmatized_lyrics.csv         # Lemmatize edilmiş şarkı sözleri
├── stemmed_lyrics.csv            # Stem uygulanmış şarkı sözleri


---

## ⚙️ Kurulum ve Çalıştırma Talimatları

### 🔹 1. Gerekli Paketlerin Kurulumu

Python 3.10 kurulu olmalıdır. Daha sonra terminal ya da Jupyter Lab içinde aşağıdaki komutlarla kütüphaneleri yükleyin:

```bash
pip install pandas numpy matplotlib gensim scikit-learn
```

### 🔹 2. Jupyter Notebook'u Başlatma

```bash
jupyter lab
```

Açılan sayfadan `lyrics_analysis.ipynb` dosyasını açarak hücreleri sırayla çalıştırın.

---

## 🔍 Yapılan İşlemler

- ✅ Verilerin yüklenmesi (`lemmatized_lyrics.csv`, `stemmed_lyrics.csv`)
- ✅ Zipf Kanunu analizi ve grafik çizimi
- ✅ TF-IDF vektörlerinin kullanılması ve cosine similarity hesaplaması
- ✅ Word2Vec modeli eğitimi ve ortalama vektörlerle benzerlik analizi
- ✅ 4 ayrı modelin karşılaştırılması (tf-idf/word2vec + stem/lemma)
- ✅ Anlamsal değerlendirme (kendi yorumlarım + skorlar)
- ✅ Sıralama tutarlılığı için Jaccard benzerliği
- ✅ Grafiklerle sonuçların görselleştirilmesi

---

## 📊 Kullanılan Modeller

- **TF-IDF (TfidfVectorizer)**
- **Word2Vec (Gensim) - CBOW**

Her iki model hem **lemmatize edilmiş** hem de **stem uygulanmış** verilerle ayrı ayrı eğitildi ve değerlendirildi.

---

## 📌 Notlar

- Proje boyunca `lyrics_analysis.ipynb` dosyası üzerinden adım adım ilerlenmiştir.
- Sonuçlar `rapor.pdf` dosyasında detaylı yorumlarla açıklanmıştır.
- Zipf analizi, benzerlik skorları, Jaccard benzerliği ve grafikler bu notebook içinde mevcuttur.

---

## 📚 Kaynaklar

- Wikipedia: [Zipf's Law](https://en.wikipedia.org/wiki/Zipf%27s_law)
- Gensim Dokümantasyonu
- Scikit-learn (sklearn) Dökümantasyonu
- Doğal Dil İşleme Dersi PDF
- ChatGPT 

---

Hazırlayan: ELİF kOÇ
Ders: Doğal Dil İşleme  

