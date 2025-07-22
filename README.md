# 🏁 Tugas Akhir (TA) - Final Project

**Nama Mahasiswa**: Sandyatama Fransisna Nugraha  
**NRP**: 5025211196  
**Judul TA**: Pengembangan Animasi 3D Realistis Dengan Penerapan Metahuman dan Motion Capture Menggunakan Unreal Engine 5  
**Dosen Pembimbing**: Dr. Eng Darlis Herumurti, S.Kom, M.Kom  
**Dosen Ko-pembimbing**: Dr. Anny Yuniarti, S.Kom., M.Comp.Sc.

---

## 📺 Demo Metahuman

#### Ini adalah video perbandingan hasil video Metahuman sebelum dan sesudah ditraining

[![Demo Aplikasi](/Documentary/Metahuman.png)](https://youtu.be/Z9uznsq9Qak)  
_Klik gambar di atas untuk menonton demo_

---

## 📺 Demo Motion Capture

#### Ini adalah video perbandingan hasil video Motion Capture sebelum dan sesudah ditraining

[![Demo Aplikasi](/Documentary/MotionCapture.png)](https://youtu.be/YObkQtfF2bg)  
_Klik gambar di atas untuk menonton demo_

---

## 📺 Demo Animasi

#### Ini adalah video akhir dari animasi yang dibuat

[![Demo Aplikasi](/Documentary/preview.png)](https://youtu.be/YObkQtfF2bg)  
_Klik gambar di atas untuk menonton demo_

---

## 📺 Behind The Scene

#### Ini adalah behind the scene dari animasi yang dibuat

[![Demo Aplikasi](/Documentary/BehindTheScene.png)](https://youtu.be/kfcv14OmHss)  
_Klik gambar di atas untuk menonton video_

---

## 🛠 Panduan Kebutuhan Software

### Prasyarat

### 💻 Hardware Requirements

1. **Perangkat Mobile (iOS)**  
   Memiliki perangkat mobile dengan sistem operasi **iOS 10 ke atas** yang mendukung **fitur TrueDepth** untuk pengambilan _face capture_.  
   [📄 Lihat Dokumentasi Epic Games](https://dev.epicgames.com/documentation/en-us/metahuman/capture-device-requirements)

2. **Komputer/PC**  
   Komputer dengan spesifikasi yang sesuai untuk menjalankan **MetaHuman Animator** dan **Unreal Engine 5**.  
   [📄 Lihat Dokumentasi Epic Games](https://dev.epicgames.com/documentation/en-us/metahuman/hardware-requirements-for-animator)

3. **Head-Mounted Device (HMD)**  
   Perangkat tambahan berupa **kamera head-mounted** yang digunakan untuk menangkap ekspresi wajah secara real-time, terutama saat dikombinasikan dengan teknologi motion capture.  
   ![HeadMounted Device](/Documentary/HeadMounted.jpg)

4. **Green Screen**  
   Digunakan untuk proses _chroma keying_ saat pengambilan gambar agar hasil lebih profesional dan memudahkan tahap pascaproduksi.  
   ![Green Screen](/Documentary/GreenScreen.jpg)

### 🧠 Software Requirements

1. **Unreal Engine 5**  
   Merupakan _game engine_ utama yang digunakan untuk membangun animasi 3D. Unreal Engine 5 menyediakan dukungan terhadap teknologi **MetaHuman** dan **Live Link**, memungkinkan proses produksi animasi menjadi lebih realistis dan efisien.

   - 🌐 [Unreal Engine 5 - Official Page](https://www.unrealengine.com/en-US/unreal-engine-5)
   - 📄 [MetaHuman Documentation - Epic Games](https://dev.epicgames.com/documentation/en-us/metahuman/metahuman-documentation)

2. **Move AI**  
   Aplikasi berbasis AI yang memungkinkan pengambilan **gerakan tubuh (body motion capture)** tanpa menggunakan sensor atau marker. Move AI dapat digunakan melalui perangkat iOS dan menghasilkan data animasi yang bisa diintegrasikan ke Unreal Engine.

   - 📲 [Move AI – App Store (iOS)](https://apps.apple.com/us/app/move-ai-3d-motion/id6448635527)

3. **Live Link Face**  
   Aplikasi iOS resmi dari Epic Games yang digunakan untuk menangkap **ekspresi wajah** secara real-time menggunakan kamera **TrueDepth** di iPhone. Aplikasi ini mengirimkan data wajah ke Unreal Engine melalui protokol **Live Link** untuk diterapkan langsung ke karakter MetaHuman.
   - 📲 [Live Link Face – App Store (iOS)](https://apps.apple.com/us/app/live-link-face/id1495370836)

---

### Langkah-langkah

1. **Clone Repository**
   ```bash
   git clone https://github.com/Informatics-ITS/TA.git
   ```
2. **Instalasi Dependensi**
   ```bash
   cd [folder-proyek]
   pip install -r requirements.txt  # Contoh untuk Python
   npm install  # Contoh untuk Node.js
   ```
3. **Konfigurasi**

- Salin/rename file .env.example menjadi .env
- Isi variabel lingkungan sesuai kebutuhan (database, API key, dll.)

4. **Jalankan Aplikasi**
   ```bash
   python main.py  # Contoh untuk Python
   npm start      # Contoh untuk Node.js
   ```
5. Buka browser dan kunjungi: `http://localhost:3000` (sesuaikan dengan port proyek Anda)

---

## 📚 Dokumentasi Tambahan

- [![Dokumentasi API]](docs/api.md)
- [![Diagram Arsitektur]](docs/architecture.png)
- [![Struktur Basis Data]](docs/database_schema.sql)

---

## ✅ Validasi

Pastikan proyek memenuhi kriteria berikut sebelum submit:

- Source code dapat di-build/run tanpa error
- Video demo jelas menampilkan fitur utama
- README lengkap dan terupdate
- Tidak ada data sensitif (password, API key) yang ter-expose

---

## ⁉️ Pertanyaan?

Hubungi:

- Penulis: sandyatamafransisna45404@gmail.com
- Pembimbing Utama: darlis@if.its.ac.id
