# Projenin Amacı 
Projemin amacı Nike firmasının 2024 satış verilerini Makine Öğrenmesi yöntemleriyle ele alıp, konu hakkinda analizi yapmaktir. Bu hususta aşağıdaki anlatılan adımlar gerçekleştirilmiştir.

# Kullanılan Diller
Proje kodlanırken Google Colaboratory kullanılmış ve kodlama dili olarak evrensel çapta yaygın olan Python dili kullanılmıştır. 

# Veri Temizleme Adımları
Kodun ilk adiminda veri setindeki verileri analiz ettim ve eksik verileri doldurdum. Gerekli adımlar kod dosyasinda mevcut olup, aşağıdaki çıktıyı vermektedir. İki adım sonra bulunan adımda ise sayısal sütunların temizlenmesi ve ölçeklenmesi gerçekleştirilmiş olup veri temizliği tamamlanmıştır.

![image](https://github.com/user-attachments/assets/bba8f4ec-9401-4b3c-8387-63a3763c0a80)

# Görselleştirme Adımları 
Kodlamanın altıncı adımında ise Histogram ve Korelasyon Matrisi kullanılmış olup kodun görsel açıdan grafiklerle desteklenmesi sağlanmıştır.

![image](https://github.com/user-attachments/assets/29678363-fb0c-4ab6-8c10-d775447dabbb)
![image](https://github.com/user-attachments/assets/8a10b0dc-fa59-44a7-8677-7c7576ec039a)

Ek olarak kodda kullanılan üç tür makine öğrenmesi algoritması olan Lineer Regresyon, Random Forest ve KNN türlerinin grafik çıktıları verilmistir. Model çıktıları modeli açıklama kisminda mevcuttur.

# Model Seçimi Uygulama Adımları 
Projede bir önceki adımda da belirtildiği üzere üç tür uygulama adımı kullanılmıştır ve kurallarına uygun şekilde projeye aktarılmıştır. Gragfıklerde ele alınan x ve y düzlemleri ise "Tahmin Edilen Gelir" ve "Gerçek Gelir" olarak .csv uzantılı dosyadan alınmıştır. Ve adımlarda ilk olarak modali belirleyip değerleri atadıktan sonra yöntem kurallarına uygun sekilde grafiklerini elde edilmiştir.

Lineer Regresyon : 

![image](https://github.com/user-attachments/assets/10e8215d-9c55-4289-894a-f58fbd88f349)

Random Forest : 

![image](https://github.com/user-attachments/assets/7843958f-8ce7-4533-97c1-d98d37987496)

KNN : 

![image](https://github.com/user-attachments/assets/637b8ebe-016a-4e68-b2c0-086112d0376e)

# Sonuç Ve Değerlendirme Adımı  
Projenin onuncu adımında ise kullanılan yöntemlerin R2 doğruluk değerleri karşılaştırılmış olup bu proje bazında Random Forest algoritmasının kullanımının daha yararlı olacağı anlaşılmıştır.

![image](https://github.com/user-attachments/assets/3f99cd14-f8af-4902-996d-ed34f8b926c9)

# Proje Hakkındaki YouTube Video Linki
https://youtu.be/mWHWlKJmXXw
