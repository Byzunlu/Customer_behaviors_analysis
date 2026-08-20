# 📊 Veri Analizi Projesi

> 🇬🇧 [Click here for the English version](README.md)

## 📌 Proje Genel Bakışı

Bu proje, ham verilerin yüklenmesinden başlayarak veri temizleme, Keşifsel Veri Analizi (EDA), SQL sorguları, Power BI dashboard geliştirme, raporlama ve sunum hazırlama süreçlerini kapsayan uçtan uca bir veri analizi projesidir.

Projenin amacı, ham verileri anlamlı içgörülere dönüştürmek ve veriye dayalı karar alma süreçlerini desteklemektir.

---

## 🎯 Proje Amaçları

Bu projenin temel amaçları:

* Veri setini yüklemek ve anlamak
* Keşifsel Veri Analizi (EDA) gerçekleştirmek
* Verileri analiz için temizlemek ve hazırlamak
* Trendleri, desenleri ve önemli içgörüleri belirlemek
* SQL kullanarak iş odaklı soruları yanıtlamak
* İnteraktif bir Power BI dashboard oluşturmak
* Analiz sonuçlarını rapor haline getirmek
* Önemli bulguları ve önerileri sunmak

---

## 📂 Veri Seti

Veri seti analiz ve hazırlık sürecinde çeşitli aşamalardan geçirilmiştir:

* Veri seti yapısının incelenmesi
* Veri tiplerinin kontrol edilmesi
* Eksik değerlerin belirlenmesi
* Yinelenen kayıtların tespit edilmesi
* Tutarsız veya hatalı verilerin kontrol edilmesi
* Gerekli durumlarda yeni değişkenlerin oluşturulması

Projede verilerin hem ham hem de temizlenmiş versiyonları kullanılmaktadır.

---

## 🛠️ Kullanılan Araçlar ve Teknolojiler

| Araç                            | Kullanım Amacı                    |
| ------------------------------- | --------------------------------- |
| Python                          | Veri yükleme, temizleme ve analiz |
| Pandas                          | Veri manipülasyonu ve analizi     |
| NumPy                           | Sayısal işlemler                  |
| Matplotlib / Seaborn            | Veri görselleştirme               |
| SQL                             | Veri sorgulama ve analiz          |
| PostgreSQL / MySQL / SQL Server | Veritabanı yönetimi               |
| Power BI                        | İnteraktif dashboard geliştirme   |
| Jupyter Notebook                | Veri analizi süreci               |
| Gamma                           | Sunum hazırlama                   |

---

## 🔄 Proje İş Akışı

### 1. Veri Yükleme

Veri seti Python ortamına aktarıldı ve ilk incelemeler gerçekleştirildi.

Kontrol edilen temel alanlar:

* Satır ve sütun sayısı
* Sütun isimleri
* Veri tipleri
* Eksik değerler
* Temel istatistiksel bilgiler

---

### 2. Keşifsel Veri Analizi (EDA)

Veriyi daha iyi anlamak ve önemli desenleri belirlemek amacıyla Keşifsel Veri Analizi gerçekleştirildi.

Analiz kapsamında:

* Değişkenlerin dağılımları incelendi
* Zaman içerisindeki trendler analiz edildi
* Değişkenler arasındaki ilişkiler araştırıldı
* Kategori ve segment karşılaştırmaları yapıldı
* Aykırı değerler incelendi
* Önemli trendler ve desenler belirlendi

Bulguları daha anlaşılır hale getirmek için çeşitli görselleştirmeler oluşturuldu.

---

### 3. Veri Temizleme

Ham veriler daha güvenilir ve analiz edilebilir hale getirilmek üzere temizlendi.

Veri temizleme sürecinde:

* Eksik değerler ele alındı
* Yinelenen kayıtlar kaldırıldı
* Tutarsız veriler düzeltildi
* Veri tipleri uygun formatlara dönüştürüldü
* Sütun değerleri standardize edildi
* Gerektiğinde yeni hesaplanmış sütunlar oluşturuldu

---

### 4. SQL Analizi

Temizlenen veri seti ilişkisel bir veritabanına aktarıldı ve SQL kullanılarak analiz edildi.

Analiz kapsamında kullanılan yapılar:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `JOIN`
* `CASE WHEN`
* Aggregate Functions
* Subqueries

SQL sorguları, iş sorularını yanıtlamak ve veriden anlamlı içgörüler elde etmek amacıyla kullanıldı.

---

## 📊 Power BI Dashboard

Analiz sonuçlarını görselleştirmek amacıyla Power BI üzerinde interaktif bir dashboard oluşturuldu.

Dashboard içerisinde:

* Temel Performans Göstergeleri (KPI)
* Trend analizleri
* Kategori karşılaştırmaları
* Segment analizleri
* İnteraktif filtreler
* Veri odaklı görselleştirmeler

yer almaktadır.

Dashboard'un amacı, analiz sonuçlarının daha kolay anlaşılmasını sağlamak ve karar alma süreçlerini desteklemektir.

---

## 🔍 Önemli Bulgular ve Sonuçlar

Analiz sonucunda veri içerisindeki önemli trendler ve desenler belirlenmiştir.

Başlıca analiz sonuçları:

* Önemli performans trendlerinin belirlenmesi
* Farklı kategori ve segmentlerin karşılaştırılması
* Genel performansı etkileyen faktörlerin incelenmesi
* Zaman içerisindeki değişimlerin analiz edilmesi
* Geliştirme fırsatlarının tespit edilmesi

Detaylı bulgular ve öneriler proje raporunda ve sunumunda yer almaktadır.

---

## 📄 Rapor ve Sunum

Proje sonuçları iki farklı formatta dokümante edilmiştir:

* **Rapor:** Analiz süreci, kullanılan yöntemler, bulgular ve önerilerin detaylı açıklaması
* **Sunum:** Önemli içgörülerin ve sonuçların paydaşlara daha etkili şekilde aktarılması için hazırlanan özet çalışma

Sunum Gamma kullanılarak hazırlanmıştır.

---

## 📁 Proje Yapısı

```text
data-analytics-project/
│
├── data/
│   ├── raw/                      # Ham veri seti
│   └── cleaned/                  # Temizlenmiş veri seti
│
├── notebooks/
│   ├── 01_data_loading.ipynb     # Veri yükleme ve ilk inceleme
│   ├── 02_eda.ipynb              # Keşifsel Veri Analizi
│   └── 03_data_cleaning.ipynb    # Veri temizleme ve hazırlama
│
├── sql/
│   └── analysis_queries.sql      # SQL sorguları
│
├── dashboard/
│   └── powerbi_dashboard.pbix    # Power BI dashboard
│
├── reports/
│   └── project_report.pdf        # Proje raporu
│
├── presentation/
│   └── project_presentation      # Gamma sunumu
│
├── README.md                     # İngilizce README
├── README_TR.md                  # Türkçe README
└── requirements.txt              # Python kütüphaneleri
```

---

## 🚀 Proje Nasıl Çalıştırılır?

### 1. Repoyu Klonlayın

```bash
git clone <repository-url>
cd data-analytics-project
```

### 2. Gerekli Kütüphaneleri Yükleyin

```bash
pip install -r requirements.txt
```

### 3. Python Analizini Çalıştırın

Jupyter Notebook'u başlatın:

```bash
jupyter notebook
```

Ardından `notebooks/` klasöründeki dosyaları sırasıyla çalıştırın:

1. `01_data_loading.ipynb`
2. `02_eda.ipynb`
3. `03_data_cleaning.ipynb`

### 4. SQL Sorgularını Çalıştırın

Temizlenmiş veri setini tercih ettiğiniz veritabanı yönetim sistemine aktarın:

* PostgreSQL
* MySQL
* SQL Server

Daha sonra aşağıdaki dosyada bulunan sorguları çalıştırın:

```text
sql/analysis_queries.sql
```

### 5. Power BI Dashboard'u Açın

`dashboard/` klasöründeki `.pbix` dosyasını Power BI Desktop kullanarak açabilirsiniz.

---

## 💡 Gösterilen Beceriler

Bu proje aşağıdaki veri analizi yetkinliklerini göstermektedir:

* Veri Temizleme
* Veri Hazırlama
* Keşifsel Veri Analizi (EDA)
* Veri Görselleştirme
* Python Programlama
* Pandas ve NumPy
* SQL Sorgulama
* Veritabanı Analizi
* Power BI Dashboard Geliştirme
* İş Analizi
* Data Storytelling
* Raporlama
* Analitik İçgörülerin Sunulması

---

## 👤 Hazırlayan

**[Beyza ÜNLÜ]**

Data Analyst | Python | SQL | Power BI

* GitHub: [(https://github.com/Byzunlu/BeyzaNL)]
* LinkedIn: [(https://www.linkedin.com/in/beyza-%C3%BCnl%C3%BC-b17878333?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)]

---

## 📬 İletişim

Proje hakkında soru, görüş veya önerileriniz varsa GitHub veya LinkedIn üzerinden benimle iletişime geçebilirsiniz.
