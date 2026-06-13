# 🎲 Dice Roller App

Aplikasi **Dice Roller** adalah aplikasi Android sederhana yang mensimulasikan pelemparan dadu. Dibuat menggunakan **Kotlin** dan **Jetpack Compose** sebagai bagian dari tugas kuliah.

## 📱 Fitur

- Tekan tombol **Roll** untuk melempar dadu
- Menampilkan gambar dadu secara acak dari sisi 1 sampai 6
- Desain responsif dengan Material 3

## 🛠 Tech Stack

| Teknologi            | Versi  |
| -------------------- | ------ |
| Kotlin               | 2.1.0  |
| Android Gradle Plugin| 8.8.0  |
| Gradle               | 8.12   |
| Compose BOM          | 2024.12.01 |
| Material 3           |        |
| minSdk               | 24     |
| targetSdk            | 35     |

## 🏗 Struktur Proyek

```
app/
├── src/main/
│   ├── java/com/example/diceroller/
│   │   ├── MainActivity.kt          # Entry point & UI utama
│   │   └── ui/theme/
│   │       ├── Color.kt             # Palet warna
│   │       ├── Theme.kt             # Tema Material 3
│   │       └── Type.kt              # Tipografi
│   ├── res/
│   │   ├── drawable/                # Vector drawable dadu (dice_1 - dice_6)
│   │   ├── mipmap-*/                # Launcher icons
│   │   └── values/
│   │       ├── colors.xml
│   │       ├── strings.xml
│   │       └── themes.xml
│   └── AndroidManifest.xml
├── build.gradle.kts
└── proguard-rules.pro
build.gradle.kts          # Root build config
settings.gradle.kts       # Project settings
gradle/                   # Gradle wrapper
```

## 🚀 Cara Menjalankan

1. Buka folder proyek di **Android Studio**
2. Tunggu sinkronisasi Gradle selesai
3. Klik **Run** atau jalankan via terminal:
   ```bash
   ./gradlew assembleRelease
   ```
4. APK akan tersedia di `app/build/outputs/apk/release/app-release.apk`

## 📦 APK

APK rilis tersedia di [halaman Release](https://github.com/jaweed3/TI_452024611047_DiceRoller/releases).

- **Nama file**: `DiceRollerApp-v1.0.0.apk`
- **Minimal Android**: Nougat (API 24)

## 📸 Screenshot

| Tampilan Awal                                       | Setelah Roll                                         |
| --------------------------------------------------- | ---------------------------------------------------- |
| ![Screenshot](https://via.placeholder.com/360x640) | ![Screenshot](https://via.placeholder.com/360x640)  |

> **Catatan**: Tambahkan screenshot dengan meletakkan file `.png` di folder `screenshots/` dan perbaruhi path di atas.

## 📝 Tugas

- **Mata Kuliah**: Pemrograman Mobile
- **Kelas**: TI
- **NIM**: 452024611047
- **Aplikasi**: Tugas 2 — Dice Roller App

## 📚 Referensi

- [Codelab: Create an interactive Dice Roller app](https://developer.android.com/codelabs/basic-android-kotlin-compose-build-a-dice-roller-app)
- [Official solution code](https://github.com/google-developer-training/basic-android-kotlin-compose-training-dice-roller)
