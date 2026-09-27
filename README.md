# Futures Chart — Mobil

Tek dosyalık, mobil öncelikli kripto vadeli işlem (futures) grafik terminali.

- **Grafik**: TradingView Lightweight Charts (v4.2.3, gömülü)
- **Veri kaynağı**: Binance Futures → OKX → sentetik (demo) fallback zinciri
- **Strateji**: VWMA + Gaussian kesişim sistemi ("SATIŞ1" pozisyon takibi, giriş/TP ışınları, canlı PnL çipi)
- **UI**: Alt sheet tabanlı coin seçici ve ayarlar paneli, açık/koyu tema

Bağımlılık yok, build adımı yok — tek `index.html` dosyası doğrudan tarayıcıda çalışır.
