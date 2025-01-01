# Lang Assist Design System

Lang Assist platformunun tasarım sistemi ve UI pattern'leri.

## İçerik

- UI Bileşenleri
- Renk Paleti
- Tipografi
- İkonlar
- Animasyonlar
- Responsive Design Kuralları
- Platform-Spesifik Uyarlamalar

## Teknolojiler

- Figma
- Flutter
- Vue.js
- TailwindCSS

## Kullanım

### Flutter Projeleri

```dart
import 'package:lang_assist_design/theme.dart';
import 'package:lang_assist_design/components.dart';
```

### Web Projeleri

```javascript
import "@lang-assist/design/styles/main.css";
import { Button } from "@lang-assist/design/components";
```

## Geliştirme

1. Repository'yi klonlayın:

```bash
git clone https://github.com/lang-assist/design.git
```

2. Bağımlılıkları yükleyin:

```bash
npm install  # Web bileşenleri için
flutter pub get  # Flutter bileşenleri için
```

## Dokümantasyon

- Figma dosyalarına [buradan](https://figma.com/lang-assist) erişebilirsiniz
- Storybook dokümantasyonuna `npm run storybook` komutu ile erişebilirsiniz
- Flutter widget kataloğuna `flutter run -t lib/gallery/main.dart` komutu ile erişebilirsiniz

## Katkıda Bulunma

1. Yeni bir branch oluşturun
2. Değişikliklerinizi yapın
3. Test edin
4. Pull request oluşturun

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.
