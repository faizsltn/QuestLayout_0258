<div align="center">

# 📱 QuestLayout_0258

**Aplikasi Android Sederhana Berbasis Jetpack Compose**

![Kotlin](https://img.shields.io/badge/Kotlin-100%25-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)

---

</div>

## 📌 Deskripsi Proyek
Proyek ini merupakan tugas latihan pembuatan antarmuka pengguna (*User Interface*) pada platform Android menggunakan **Jetpack Compose**. Aplikasi ini menampilkan kartu informasi profil mahasiswa lengkap dengan logo, program studi, universitas, dan alamat secara responsive.

---

## 🛠️ Teknologi & Komponen Utama

- **Bahasa Pemrograman:** Kotlin
- **Toolkit UI:** Jetpack Compose (Material3)
- **Komponen UI yang Digunakan:**
  - `Column` & `Row` untuk tata letak vertikal & horizontal
  - `Box` untuk pemosisian elemen copyright di bagian bawah
  - `Card` & `CardDefaults` untuk kontainer profil berlatar belakang khusus
  - `Image` & `painterResource` untuk menampilkan logo/gambar
  - `Text` & `Spacer` untuk penyusunan teks serta jarak antar elemen

---

## 📁 Struktur Kode

```text
com.example.composablelayout2/
├── MainActivity.kt           # Entry point utama yang memanggil composable screen
└── ActivitasPertama.kt        # Layout UI utama berbasis Jetpack Compose
