# Electric_Vehicles_EDA

## Proje Hakkında
Bu proje, ABD'nin Washington (WA) eyaletindeki elektrikli araç (EV) verilerini kullanarak yapılan bir Keşifsel Veri Analizi (EDA) çalışmasıdır. Amaç, elektrikli araçların ilçe bazındaki dağılımı, en çok tercih edilen markalar ve araç türlerinin (BEV / PHEV) oranlarını incelemektir.

## Veri Seti
- Veri kaynağı: [veri seti kaynağı veya açıklama]  
- Önemli kolonlar: `County`, `City`, `State`, `Make`, `Model`, `Electric Vehicle Type`, `Electric Range`  

## Analizler
1. **İlçe Bazlı Elektrikli Araç Sayısı:**  
   Washington içindeki ilçelerin EV kayıt sayıları görselleştirildi; en yüksek 15 ilçe karşılaştırıldı.
2. **Top 10 Marka Analizi:**  
   Tesla, açık ara lider. Diğer markalar (Chevrolet, Nissan, Ford, Kia, BMW, Toyota, Hyundai, Rivian, Volvo) birbirine yakın sayılarda tercih edilmiş.
3. **EV Türleri (BEV vs PHEV):**  
   Top 10 markadaki araçların %80’i BEV, %20’si PHEV. Tesla’nın tüm modelleri BEV olduğu için bu oran yüksek.  
4. **Electric Range Dağılımı:**  
   Verilerin yetersizliğinden Electric Range analizi yapmamaya karar verildi.

## Kullanılan Kütüphaneler
- pandas  
- matplotlib  
- seaborn   

## Sonuçlar ve Öneriler
- Tesla’nın pazar payı, BEV ağırlığını belirgin şekilde yukarı çekiyor.  
- İlçe bazlı yoğunluk, altyapı ve nüfus etkilerini gösterebilir.  
- Gelecekte menzil verilerinin tamamlanması ile daha detaylı analizler yapılabilir.

## Görseller
- İlçe bazlı araç sayısı grafiği  
- Top 10 markanın araç sayısı grafiği  
- EV türleri dağılımı (BEV / PHEV)  


