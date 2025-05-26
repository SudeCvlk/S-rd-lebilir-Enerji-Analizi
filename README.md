#Surdurulebilir-Enerji-Analizi-ve-Yatirim-Tahmini

Bu projede, ülkelerin enerji ve çevre göstergeleri kullanılarak sürdürülebilir enerji yatırımlarını ve karbon emisyonlarını analiz etmek ve tahmin etmek amaçlanmıştır. Python dilinde geliştirilen bu çalışma; veri temizleme, görselleştirme, regresyon ve sınıflandırma yöntemlerini içeren bir veri bilimi projesidir.
Projenin amacı; CO₂ emisyonlarını eetkileyen temel faktörleri belirlemek, ülkeleri enerji tüketim profillerine göre incelemek, enerji yatırım seviyelerini sınıflandırmak ve tahmin etmektir. 

Kullanılan araçlar: Veri temizleme ve görselleştirme için Pandas, Matplotlib, Seaborn; Eksik veri doldurma için KNN imputation; Aykırı değer analizi için IQR yöntemi ve Boxplot görselleştirme; Kümeleme için K-Means Clustering; Regresyon modelleri için Lineer Regresyon ve Random Forest Regressor; Sınıflandırma için Logistic Regression 

**Elde Eldilen Sonuçlar:**
Projede yapılan analizler sonucunda, karbon emisyonlarını artıran en önemli etkenlerin enerji kullanımı ve fosil yakıt tüketimi olduğu görülmüştür. Buna karşılık, yenilenebilir enerji kullanımının artması emisyonları azaltma yönünde olumlu bir etki yaratmaktadır.
Kullanılan modellerden lineer regresyon temel düzeyde bir tahmin gücü sunarken, daha gelişmiş bir yöntem olan Random Forest modeli çok daha başarılı tahminler yapmıştır. Bu model, değişkenler arasındaki karmaşık ilişkileri daha iyi yakalayarak karbon emisyonlarını daha doğru öngörebilmiştir.
Sonuç olarak, ülkelerin enerji profilleri karbon salımlarında belirleyici bir rol oynamakta ve sürdürülebilir enerjiye geçişin çevresel etkileri açıkça ortaya konulmaktadır.
