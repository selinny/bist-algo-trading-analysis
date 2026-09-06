# Borsa İstanbul Kantitatif Portföy Analizi ve Algoritmik Stratejiler

Bu proje, Borsa İstanbul (BIST) hisse senetleri üzerinde veri odaklı yatırım kararları almak amacıyla geliştirilmiş veri analitiği ve algoritmik ticaret prototiplerini içerir.

## Proje İçeriği
- **Risk ve Korelasyon Analizi:** Farklı sektör hisselerinin (GARAN, SISE, THYAO, ASELS) getirileri ve $4 \times 4$ getiri korelasyon matrisi.
- **Markowitz Etkin Sınır Simülasyonu:** Monte Carlo yöntemiyle 3.000 rastgele portföy türetilerek maksimum Sharpe oranına sahip portföy ağırlıklarının tespiti.
- **Strateji Backtestleri:**
  - Hareketli Ortalama Kesişimi (SMA 20/50) ve Stop-Loss kuralı testi.
  - 14 günlük RSI (Göreceli Güç Endeksi) aşırı alım/aşırı satım osilatörü ile getiri karşılaştırması.
  - **Bollinger Bantları Göstergesi:** 20 günlük periyot ve 2 standart sapma aralığı ile fiyat kanalı analizi ve aşırı sapma tespiti.

## Kullanılan Teknolojiler
- Python
- `yfinance`, `pandas`, `numpy`
- `matplotlib`, `seaborn`


