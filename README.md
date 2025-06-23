# CryptoTracker 📈

Modern ve kullanıcı dostu bir React Native kripto para takip uygulaması. Gerçek zamanlı fiyat takibi, portföy yönetimi ve detaylı grafik analizi ile kripto para yatırımlarınızı kolayca yönetin.

## ✨ Özellikler

### 🏠 Ana Ekran
- Gerçek zamanlı kripto para fiyat listesi
- 24 saatlik değişim yüzdeleri
- Arama ve filtreleme özellikleri
- Favori kripto paralar (Watchlist)

### 📊 Portfolio Yönetimi
- Kişisel kripto para portföyü
- Toplam portföy değeri hesaplama
- Kar/zarar analizi
- Varlık dağılımı görüntüleme

### 📈 Detaylı Grafik Analizi
- İnteraktif fiyat grafikleri
- Farklı zaman aralıkları (1G, 1H, 1A, 5Y)
- Teknik analiz göstergeleri
- Fiyat geçmişi ve trend analizi

### 🎯 Watchlist
- Favori kripto paraları takip etme
- Hızlı erişim ve fiyat monitörü
- Özelleştirilebilir liste yönetimi

## 🛠️ Teknolojiler

- **React Native** - Cross-platform mobil uygulama geliştirme
- **Expo** - React Native geliştirme platformu
- **React Navigation** - Uygulama içi navigasyon
- **Recoil** - Global state yönetimi
- **React Native SVG** - Vektörel grafik desteği
- **React Native Reanimated** - Gelişmiş animasyonlar
- **React Native Gesture Handler** - Dokunmatik etkileşimler
- **WAGMI Charts** - Kripto para grafikleri
- **Axios** - HTTP istekleri

## 📱 Ekran Görüntüleri

> Ana ekran, portföy yönetimi, grafik analizi ve watchlist özelliklerini gösteren ekran görüntüleri eklenecek.

## 🚀 Kurulum

### Gereksinimler
- Node.js (v14 veya üstü)
- npm veya yarn
- Expo CLI
- iOS Simulator (iOS geliştirme için)
- Android Studio (Android geliştirme için)

### Adımlar

1. **Repoyu klonlayın**
   ```bash
   git clone https://github.com/kullaniciadi/CryptoTracker-main.git
   cd CryptoTracker-main
   ```

2. **Bağımlılıkları yükleyin**
   ```bash
   npm install
   # veya
   yarn install
   ```

3. **Uygulamayı başlatın**
   ```bash
   expo start
   ```

4. **Mobil cihazda test edin**
   - iOS: iOS Simulator'da çalıştırın veya Expo Go uygulaması ile QR kodu tarayın
   - Android: Android Emulator'da çalıştırın veya Expo Go ile QR kodu tarayın

## 📁 Proje Yapısı

```
CryptoTracker-main/
├── assets/                 # Resimler, fontlar ve diğer medya dosyaları
│   ├── data/               # JSON veri dosyaları
│   ├── fonts/              # Özel fontlar
│   ├── icon.png            # Uygulama ikonu
│   └── splash.png          # Açılış ekranı
├── src/                    # Ana kaynak kod dizini
│   ├── atoms/              # Recoil state tanımları
│   ├── components/         # Yeniden kullanılabilir bileşenler
│   │   └── CoinItem/       # Kripto para liste öğesi
│   ├── Contexts/           # React Context tanımları
│   ├── navigation/         # Navigasyon yapılandırması
│   ├── screens/            # Uygulama ekranları
│   │   ├── HomeScreen/
│   │   ├── PortfolioScreen/
│   │   ├── WatchlistScreen/
│   │   ├── CoinDetailedScreen/
│   │   └── AddNewAssetScreen/
│   └── services/           # API istekleri ve servisler
├── App.js                  # Ana uygulama dosyası
├── package.json            # Proje bağımlılıkları
└── README.md              # Bu dosya
```

## 🔧 Konfigürasyon

### API Yapılandırması
Uygulama kripto para verilerini almak için harici API'ler kullanır. `src/services/requests.js` dosyasında API endpoint'leri yapılandırılmıştır.

### Tema ve Stiller
Her bileşen kendi `styles.js` dosyasına sahiptir. Global tema ayarları için `App.js` dosyasını kontrol edin.

## 🤝 Katkıda Bulunma

1. Bu repoyu fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 📞 İletişim

Proje Linki: [https://github.com/kullaniciadi/CryptoTracker-main](https://github.com/kullaniciadi/CryptoTracker-main)

---

⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!