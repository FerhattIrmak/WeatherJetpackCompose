

<img src="https://github.com/user-attachments/assets/f8c76885-21c0-4c24-8052-fc07db18a20a" width="220"/>


<img src="https://github.com/user-attachments/assets/b337c7e9-befd-4246-b528-269b514be09a" width="220"/>


# Weather App

## Proje Açıklaması

Weather App, kullanıcıların şehir ismi girerek anlık hava durumu bilgilerini almasını sağlayan bir Android uygulamasıdır. Kullanıcılar, girdikleri şehre ait sıcaklık, nem oranı ve hava durumu açıklamalarını şık bir arayüzde görüntüleyebilirler.

## Kullanılan Teknolojiler

- **Kotlin**: Android uygulaması geliştirmek için kullanılan ana programlama dili.
- **Jetpack Compose**: Modern UI oluşturmak için kullanılan deklaratif UI kütüphanesi.
- **Material 3**: Şık ve modern kullanıcı arayüzü bileşenleri için kullanıldı.
- **Retrofit**: Hava durumu verilerini almak için API çağrılarında kullanıldı.
- **Coroutines ve Flow**: Asenkron veri işlemleri için kullanıldı.
- **ViewModel**: UI ile iş mantığını birbirinden ayırmak için kullanıldı.

## Kurulum

### Projeyi Klonlayın

`bash
git clone https://github.com/kullaniciadi/weather-app.git
cd weather-app`

## Gerekli Bağımlılıkları Ekleyin
Retrofit, Jetpack Compose, ViewModel gibi bağımlılıkları içeren build.gradle dosyanızı kontrol edin.

## API Anahtarını Güncelleyin
`WeatherScreen` bileşeni içinde bulunan `apiKey` değişkenini kendi OpenWeather API anahtarınızla değiştirin.

## Projeyi Çalıştırın
Android Studio ile açarak bir emulator veya fiziksel cihazda çalıştırabilirsiniz.

## Özellikler
- Şehir Bazlı Hava Durumu Sorgulama: Kullanıcı, bir şehir ismi girerek hava durumu bilgilerine ulaşabilir.
- Canlı Veri Kullanımı: OpenWeather API üzerinden anlık veriler çekilir.
- Modern Arayüz: Jetpack Compose ve Material 3 ile tasarlanmış şık bir kullanıcı arayüzü.
- Asenkron Veri Akışı: Coroutines ve Flow kullanarak API çağrıları ve veri akışı yönetilir.

## API Kullanımı
Bu uygulama, OpenWeather API kullanmaktadır. API'den veri çekmek için aşağıdaki uç noktalar kullanılmaktadır:

`https://api.openweathermap.org/data/2.5/weather?q={city_name}&appid={api_key}&units=metric
`



