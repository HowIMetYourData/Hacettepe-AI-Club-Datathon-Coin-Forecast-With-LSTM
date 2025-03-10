Public LB: 206.53464 - Private LB: 238.05324 - 2024.04 Yarışma Sonucu: 3. Derece

💡 Yaklaşım - Approach Bu yarışmada hiperparametre optimizasyonuna odaklanmak yerine, LSTM modelini kripto para piyasasının dinamiklerine uygun şekilde özelleştirmeyi tercih ettim. Coin verilerinin doğasını anlamak için zaman serisi özellikleri (günlük dalgalanmalar, haftanın günleri, teknik göstergeler) üzerinde derinlemesine çalıştım. Özellikle RSI, MACD ve Bollinger Bantları gibi teknik göstergeleri modele entegre ederek, finansal piyasa davranışlarını yakalamayı hedefledim.

Ayrıca, zaman bazlı özellik mühendisliği (örneğin, haftalık ortalamalar, geçmiş fiyat lagları) ile modelin tahmin gücünü artırdım. Hiperparametre optimizasyonu yapmadan, sadece bu özelliklerin doğru tasarımıyla MAE skorunda ciddi bir iyileşme sağladım.

📊 Sonuçlar - Results Public LB (PV): 206.53464

Private LB (PB): 238.05324

Late (Current) Submission Score: 197.94489

Ortalama Mutlak Hata (MAE): ~200 birim

Bu skor, tahminlerimin gerçek değerlerden ortalama 200 birim sapmayla sonuçlandığını gösteriyor. Kripto para piyasasının yüksek volatilitesi düşünüldüğünde, bu sapma kabul edilebilir bir performans olarak değerlendirildi.
