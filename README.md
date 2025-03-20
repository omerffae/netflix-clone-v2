# Kullanılan Kütüphaneler

- axios
- millify
- react-router-dom
- react-icons
- react-player
- react-redux
- redux
- redux-thunk
- tailwind
- splide-slice

## 🎬 Film Projesi - TMDB API Entegrasyonu

### 📜 Proje Açıklaması
TMDB API kullanılarak geliştirilen bu proje, popüler film ve dizi bilgilerini sunan dinamik bir web uygulamasıdır. Kullanıcılar film detaylarına ulaşabilir, fragman izleyebilir ve içerikleri kategorilere göre filtreleyebilir.

### 🌟 Öne Çıkan Özellikler
- Gerçek zamanlı film/dizi verileri
- Responsive ve modern UI tasarım
- Detaylı içerik sayfaları
- Video fragman oynatıcı entegrasyonu
- Gelişmiş arama ve filtreleme
- Redux ile state yönetimi
- Optimize edilmiş performans

### 🛠 Kullanılan Teknolojiler
**Frontend:**
- **State Management:** React-Redux, Redux-Thunk
- **Routing:** React-Router-DOM v6
- **Styling:** Tailwind CSS + Özel Animasyonlar
- **Utilities:** Axios, Millify, React-Icons
- **Slider:** Splide.js

**Backend Entegrasyon:**
- TMDB API v3
- JWT Auth ile güvenli bağlantı

### 🚀 Kurulum
1. Repoyu klonlayın:
```bash
git clone [https://github.com/omerffae/netflix-clone-v2.git]
```
2. Bağımlılıkları yükleyin:
```bash
npm install
```
3. Ortam değişkenlerini ayarlayın:
```bash
VITE_API_KEY="TMDB_API_KEYINIZ"
```

### 🖥 Çalıştırma
```bash
npm run dev
```

### 📂 Proje Yapısı
```
src/
├── components/  # Reaktif UI bileşenleri
├── utils/       # API config ve yardımcı fonksiyonlar
├── redux/       # Store, actions ve reducers
├── assets/      # Static dosyalar
└── routes/      # Sayfa routing yapılandırması
```

### 🤝 Katkıda Bulunma
1. Fork'layın ve branch oluşturun (`git checkout -b feature/fooBar`)
2. Değişikliklerinizi commit'leyin (`git commit -am 'Add some fooBar'`)
3. Push yapın (`git push origin feature/fooBar`)
4. Pull Request açın
