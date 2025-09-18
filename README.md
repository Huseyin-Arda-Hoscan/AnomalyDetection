# 🚨 HDFS Log Anomali Tespit Sistemi

Bartın Üniversitesi Mühendislik bitirme projesi kapsamında geliştirilmiş, HDFS log dosyalarındaki anomalileri tespit eden gelişmiş bir makine öğrenmesi sistemi.

Bu proje, geleneksel güvenlik yöntemlerinin yetersiz kaldığı siber güvenlik tehditlerine karşı yapay zeka tabanlı bir anomali tespit sistemi geliştirmeyi amaçlamaktadır. Sistem, karmaşık ve sürekli evrilen siber saldırılara karşı akıllı ve etkin bir savunma mekanizması oluşturmayı hedefler.

## ✨ Özellikler

- 🔍 Çoklu log formatı desteği
- 🤖 6 farklı ML modeli (XGBoost, LightGBM, CatBoost, Random Forest, Voting, KNN)
- 📊 Detaylı analiz ve görselleştirme
- 📄 PDF ve Excel raporlama
- 🎯 Gerçek zamanlı anomali tespiti

Proje hakkında ki tüm bilgileri Tez Raporu, Final Sunumu ve Poster/BitirmeProjesi_21010310057.pdf kısmında bulabilirsiniz.
Model eğitimi "ana.ipynb" dosyası ile gerçekleştirildi. "main.py" dosyası kodları "ana.ipynb" dosyası kodları ile aynıdır sadece format değişikliği bulunur. Proje için dosyayı indirmenin ardından "AnomalyDetectionGUI.py" yi çalıştırarak arayüze ulaşılabilir ve arayüz kullanılabilir. Tüm joblib dosyaları "outputs" klasörü içerisindedir. Projede bulunan "first_try/first.ipynb" dosyası ilk eğitim denemesidir. Başarı oranlarının düşük olması sebebiyle kullanılmamıştır (incelenebilmesi adına paylaşılmıştır).
