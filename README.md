# Al Hamma Garden App

Flutter app prototype for the staff of the **Jardin d'Essai du Hamma**, the botanical
garden of Algiers, built for the AgriChallenge idea-generation challenge. It gathers the
garden's daily plant-care work in one place. The interface is in French.

## Features

| Area | Screens |
|---|---|
| Plant care | Irrigation (mark trees as watered), maintenance tasks, propagation, flowering |
| Greenhouses | Live greenhouse dashboard: temperature, humidity, light (kLux), CO₂ (ppm) |
| Production | Production management, batch reception, seed bank, inventory |
| Field work | Garden map (`flutter_map`), plant scanner, photo gallery, issue reporting |
| Follow-up | Monitoring and analysis, reports, notifications and alerts |
| Assistant | Chat screen for the garden assistant bot (UI prototype) |

## Running it

```bash
flutter pub get
flutter run
```

## Stack

Flutter · Dart · flutter_map · Google Fonts

## Project layout

```
lib/
  main.dart
  screens/    one file per screen (irrigation, greenhouses, seed bank, ...)
  widgets/    navigation bars and shared cards
assets/       icons and images
```

---

Released under the [MIT License](LICENSE).
