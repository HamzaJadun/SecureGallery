# SecureGallery
Ultra-secure private gallery Android app built with Kotlin + Jetpack Compose.
## Features
- AES-256-GCM per-file encryption with Android Keystore-backed vault key
- Biometric unlock + PIN authentication, auto-lock
- SQLCipher encrypted metadata database
- FLAG_SECURE (blocks screenshots and recents preview), zero permissions, no cloud backup
## Build
Import the project into Android Studio to build the APK.
