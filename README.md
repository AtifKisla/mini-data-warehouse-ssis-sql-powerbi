# Mini Veri Ambarı Projesi (SSIS + SQL + Power BI)

Bu proje, ETL sürecini ve veri ambarı kavramlarını öğrenmek için geliştirdiğim küçük ölçekli bir veri ambarı çalışmasıdır.  
3. sınıfta aldığım Business Intelligence dersinde öğrendiklerimi pratiğe dökerek uygulamalı bir örnek oluşturdum.

## 🚀 Süreç
1. **Staging → DWH**: SQL Server üzerinde staging alanından veri ambarına aktarım
2. **ETL (SSIS):** Excel/CSV’den verilerin alınması, dönüştürülmesi ve DWH’a yüklenmesi
3. **Modelleme:** Star schema mantığında boyut (dimension) ve olgu (fact) tabloları
4. **Dashboard:** Power BI ile anlamlı görselleştirmeler ve raporlar

## 🛠️ Kullanılan Teknolojiler
- SQL Server
- SSIS (ETL)
- Power BI (Modelleme & Dashboard)

## 📂 Dosyalar
- `etl-package/` → SSIS paketi (`.dtsx`)
- `sql/` → DWH tablo ve yükleme scriptleri
- `powerbi/` → Dashboard (`.pbix`)
- `screenshots/` → Görseller

## 🔍 Önizleme
![ETL](screenshots/control_flow.png)
![Star Schema](screenshots/star_schema.png)
![Dashboard](screenshots/dashboard.png)

## 🎯 Öğrendiklerim
- ETL sürecinde veri entegrasyonu
- Star schema modelleme
- Power BI ile raporlama
