# 🎯 A/B Testi Simülasyonu: Buton Renginin Dönüşüm Oranına Etkisi

## 📌 Proje Özeti

Bu projede, bir web formundaki “Gönder” butonunun renginin kullanıcıların formu gönderme oranı (dönüşüm) üzerindeki etkisi incelenmiştir. Kırmızı ve mavi butonlar için A/B testi simüle edilerek, veri analizi ve istatistiksel testlerle farkın anlamlılığı değerlendirilmiştir.

---

## 📊 Kullanılan Yöntemler

- **Python** ile sahte kullanıcı verisi üretildi (`numpy`, `pandas`)
- **Görselleştirme** için `matplotlib` ve `seaborn` kullanıldı
- **İstatistiksel anlamlılık testi** olarak bağımsız örneklem T-Testi (`scipy`) uygulandı

---

## 🧪 Test Senaryosu

- **Grup A (Kırmızı Buton):** 1000 kullanıcı, dönüşüm oranı %12
- **Grup B (Mavi Buton):** 1000 kullanıcı, dönüşüm oranı %16

Toplam 2000 kullanıcıdan elde edilen sonuçlara göre mavi butonun dönüşüm oranı daha yüksektir.

---

## 📈 Sonuçlar

- **T-istatistiği:** -2.4901  
- **P-değeri:** 0.0129  
- **Yorum:** Fark istatistiksel olarak anlamlı ✅

---

## 📥 Rapor

Bu projenin detaylı Türkçe PDF raporuna aşağıdaki bağlantıdan ulaşabilirsiniz:

👉 [AB_Testi_Raporu_Sefa_Yasin_Namli.pdf](./AB_Testi_Raporu_Sefa_Yasin_Namli.pdf)

---

## 🧠 Öğrenilenler

- A/B testlerinin nasıl tasarlandığı ve analiz edildiği
- Ürün kararlarında veri analizinin rolü
- Python ile veri üretimi, görselleştirme ve anlamlılık testi uygulamaları

---

## 👨‍💻 Geliştiren: Sefa Yasin Namlı
