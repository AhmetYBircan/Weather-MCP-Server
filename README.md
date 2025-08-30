# Weather MCP Server

Bu proje, Model Context Protocol (MCP) kullanarak hava durumu bilgilerini sağlayan bir sunucudur.

## Kurulum

1. Bağımlılıkları yükleyin:
```bash
npm install
```

2. Environment variables ayarlayın:
```bash
cp env.example .env
```

`.env` dosyasını düzenleyerek OpenWeatherMap API anahtarınızı ekleyin:
```
WEATHER_API_BASE_URL=https://api.openweathermap.org/data/2.5/weather
WEATHER_API_KEY=your_openweathermap_api_key_here
```

## Kullanım

1. Projeyi derleyin:
```bash
npm run build
```

2. Sunucuyu başlatın:
```bash
npm start
```

## API Anahtarı Alma

OpenWeatherMap API anahtarı almak için:
1. https://openweathermap.org/ adresine gidin
2. Ücretsiz hesap oluşturun
3. API Keys bölümünden anahtarınızı alın

## Desteklenen Özellikler

- `get-weather`: Belirtilen şehir için anlık sıcaklık bilgisi
- Türkçe dil desteği
- Celsius sıcaklık birimi
