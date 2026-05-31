# 🗺️ Smart City Navigator — Şehir Rota Planlayıcı

Kullanıcı tercihlerine göre optimize edilmiş şehir içi rota planlama uygulaması.

## 📱 Android APK İndir

**[⬇️ APK'yı İndir (v1.0.0)](https://github.com/Sygemre/smart-city-navigator/releases/download/v1.0.0/application-23bfba12-31c0-4a55-97ad-61de7e3623af.apk)**

> APK'yı Android cihazınıza indirin, "Bilinmeyen kaynaklardan yükleme" iznini verin ve kurun.

---

## 🏗️ Proje Yapısı

| Klasör | Açıklama | Teknoloji |
|--------|----------|-----------|
| `prototip-1/` | İlk web prototipi | HTML, CSS, JavaScript |
| `prototip-2/` | Mobil uygulama prototipi | React Native, Expo, TypeScript |
| `sehir-rota-planlama/` | Final mobil uygulama | React Native, Expo, TypeScript, Firebase |

---

## 🚀 Özellikler

- 📍 GPS ile otomatik konum tespiti (81 il desteği)
- 🎯 Kategori bazlı rota oluşturma (Sanat, Tiyatro, Müzik, Gastronomi, Tarih, Doğa)
- ⏱️ Süre kaydırıcısı (1 saat – Tam Gün)
- 🗺️ Optimize edilmiş rota algoritması
- 🎭 Etkinlik.io ile güncel kültür-sanat etkinlikleri
- 🧭 Google Maps / Apple Maps ile yol tarifi

---

## 🛠️ Kurulum (Geliştirici)

```bash
cd sehir-rota-planlama
npm install --legacy-peer-deps
npx expo start --clear
```

---

## 🔌 Kullanılan API'ler

| API | Kullanım Amacı |
|-----|----------------|
| **Google Places API** | Konum tabanlı mekan araması, puan, fotoğraf |
| **Etkinlik.io API** | Şehre özel güncel kültür-sanat etkinlikleri |
| **Overpass API (OSM)** | Açık kaynak mekan ve coğrafi veri |
| **Firebase Firestore** | 81 il veritabanı, kullanıcı ve rota yönetimi |
| **Firebase Auth** | Kullanıcı kimlik doğrulama |

---

## 👥 Ekip

| İsim | GitHub |
|------|--------|
| Emre Saygı | [@Sygemre](https://github.com/Sygemre) |
| Sude Nisa Kahraman | [@sudekhrmn](https://github.com/sudekhrmn) |
| Berfin Karakoç | [@berfinkkarakoc](https://github.com/berfinkkarakoc) |
| Sümeyra Melike Aslan | [@smelikeaslan](https://github.com/smelikeaslan) |
| Cansu Ayakbasan | [@cansuaykbsn](https://github.com/cansuaykbsn) |

---

## 🔗 Linkler

- 📦 [Expo Build Dashboard](https://expo.dev/accounts/sygemre/projects/sehir-rota-planlayici)
- 📋 [Jira Proje Yönetimi](https://routeplanner-proje1.atlassian.net/jira/software/projects/SCRUM/summary)
