# 🎹 TABKLUNG V13.0 - Dual-Highway Chord Companion

**TABKLUNG** adalah aplikasi web interaktif berbasis musik yang dirancang untuk visualisasi nada dan latihan instrumen (seperti Angklung atau instrumen lainnya) dengan sistem *Dual-Highway*.

## 🚀 Fitur Utama
* **Dual-Highway System**: Menampilkan visualisasi nada jatuh (*Highway*) sekaligus aliran chord (*Chord Stream*) di Layer 6.
* **Transpose & Key Detection**: Deteksi kunci otomatis dari file JSON dan fitur transpose nada secara real-time.
* **Audio Engine**: Menggunakan Web Audio API untuk pemrosesan suara berkualitas tinggi dengan kontrol gain dan analyzer.
* **Screen Recording**: Fitur bawaan untuk merekam sesi latihan langsung dari browser (Output: .webm).
* **Metronome & Loop**: Dilengkapi dengan metronom visual dan mode looping untuk latihan yang konsisten.

## 🛠️ Cara Penggunaan
1.  **Load MP3**: Klik tombol `📂 LOAD MP3` untuk memasukkan sampel suara instrumen Anda.
2.  **Load JSON**: Masukkan file data lagu format `.json` yang kompatibel.
3.  **Play**: Tekan `▶ PLAY` atau tombol `Space` untuk memulai.
4.  **Recording**: Gunakan tombol `🎥 REC SCREEN` untuk mulai merekam, dan `Esc` untuk berhenti.

## 💻 Teknologi yang Digunakan
* **HTML5 Canvas**: Untuk rendering grafis 60 FPS pada highway nada dan chord.
* **Web Audio API**: Menangani pemutaran sampel dan modulasi nada.
* **PeerJS**: Untuk dukungan konektivitas P2P.
* **CSS3**: UI modern dengan tema gelap (*dark mode*) dan efek neon glow.

---
*Dibuat dengan ❤️ oleh Kang Putra.*
