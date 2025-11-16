# Simulasi Sistem Sosial (Fixed)

Aplikasi interaktif untuk mensimulasikan interaksi antar komponen sosial dan melihat dampaknya terhadap kesejahteraan, pendidikan, dan stabilitas masyarakat.

## 📋 Deskripsi

**Simulasi Sistem Sosial** adalah simulasi berbasis agent yang menggambarkan dinamika interaksi antara:
- **Keluarga** (Ayah, Ibu, Anak)
- **Sekolah** (Guru, Siswa, Kepala Sekolah, OSIS)
- **Masyarakat** (Tetangga, Pedagang, Polisi, Lembaga Sosial)
- **Pemerintah** (Institusi)

Aplikasi ini dirancang sebagai alat pembelajaran untuk menganalisis bagaimana peran-peran sosial saling mempengaruhi dan berkontribusi pada kesejahteraan umum.

## 🎯 Fitur Utama

### 1. **Visualisasi Real-time**
- Canvas interaktif menampilkan pergerakan agent di setiap komponen sosial
- Warna berbeda untuk setiap komponen (Keluarga=Biru, Sekolah=Pink, Masyarakat=Kuning, Pemerintah=Hijau)
- Animasi smooth dengan proximity collision detection

### 2. **Dashboard Metrik**
- **Grafik Kesejahteraan & Pendidikan**: Menampilkan rata-rata metric per komponen sosial
- **Statistik Komponen**: Jumlah agent dan rata-rata kesejahteraan/pendidikan per komponen
- **Log Aktivitas**: Mencatat setiap aktivitas yang dilakukan agent secara real-time

### 3. **Kontrol Simulasi**
- **Mulai/Pause/Resume**: Kontrol jalannya simulasi
- **Reset**: Kembali ke state awal
- **Pengaruh Global**: Slider untuk mengatur pengali dampak aktivitas (0x - 2x)
- **Interval Interaksi**: Atur kecepatan interaksi antar agent (200ms - 1500ms)

### 4. **Kontrol Agent**
- Atur jumlah agent untuk setiap komponen:
  - Keluarga (default: 15)
  - Sekolah (default: 18)
  - Masyarakat (default: 20)
  - Pemerintah (default: 6)
- Tombol **Apply** untuk menerapkan perubahan
- Tombol **Random** untuk merandomisasi atribut agent

## 👥 Peran & Aktivitas

### Keluarga
- **Ayah**: Pergi ke kantor → +Kesejahteraan (6)
- **Ibu**: Memasak → +Kesejahteraan (4)
- **Anak**: Belajar ujian → +Pendidikan (6)

### Sekolah
- **Guru**: Mengajar → +Pendidikan (7)
- **Siswa**: Belajar → +Pendidikan (5)
- **Kepala Sekolah**: Memantau → +Stabilitas (4)
- **OSIS**: Mengorganisir acara → +Stabilitas (5)

### Masyarakat
- **Tetangga**: Bersosialisasi → +Stabilitas (3)
- **Pedagang**: Berjualan → +Kesejahteraan (6)
- **Polisi**: Menjaga keamanan → +Stabilitas (6)
- **Lembaga Sosial**: Membantu warga → +Kesejahteraan (8)

### Pemerintah
- Institusi yang berinteraksi lintas komponen

## 📊 Metrik Agent

Setiap agent memiliki atribut yang berkembang:
- **Kesejahteraan** (0-150): Tingkat kesejahteraan ekonomi
- **Pendidikan** (0-150): Tingkat pendidikan
- **Stabilitas** (0-150): Tingkat stabilitas sosial
- **Usia** (10-70): Usia agent

## 🎮 Cara Menggunakan

1. **Buka aplikasi** di browser
2. **Klik tombol "Mulai"** untuk memulai simulasi
3. **Observasi** pergerakan agent di canvas dan perubahan metrik di dashboard
4. **Interaksi**:
   - Klik node komponen untuk melihat detail agent terbaik
   - Sesuaikan pengaruh global untuk melihat dampak
   - Ubah interval interaksi untuk kecepatan berbeda
   - Ubah jumlah agent untuk skenario berbeda
5. **Analisis** bagaimana perubahan parameter mempengaruhi sistem

## 🔍 Analisis & Pembelajaran

Aplikasi ini membantu siswa memahami:
- **Interkoneksi Sosial**: Bagaimana peran di berbagai komponen saling mempengaruhi
- **Efek Pengali**: Dampak pengaruh global terhadap kesejahteraan masyarakat
- **Dinamika Sistem**: Perubahan keseimbangan melalui interaksi agent
- **Pengambilan Keputusan**: Bagaimana perubahan jumlah agent/peran mempengaruhi sistem

## 🛠️ Teknologi

- **HTML5 Canvas**: Untuk visualisasi real-time
- **Chart.js 4.4.0**: Untuk grafik metrik
- **JavaScript (Vanilla)**: Logika simulasi dan interaksi
- **CSS3**: Styling dengan variabel custom

## 📱 Responsif

Aplikasi dirancang dengan:
- Layout grid yang responsive
- Canvas yang scale otomatis sesuai ukuran window
- Mobile-friendly controls

## 🎨 Tema

- **Dark Mode**: Theme gelap dengan aksen cyan (#4fd1c5)
- **Warna Komponen**:
  - Keluarga: Blue (#60a5fa)
  - Sekolah: Pink (#f472b6)
  - Masyarakat: Amber (#f59e0b)
  - Pemerintah: Green (#34d399)

## 📝 Catatan

- Setiap tick simulasi merepresentasikan satu interval interaksi
- Cross-component interactions memiliki probabilitas 45% terjadi
- Dampak lintas komponen lebih kecil (15-50%) dari dampak internal
- Agent bergerak dengan attraction ke pusat komponen mereka

## 👨‍💻 Pengembang

**BM 2025**  
GitHub: [@bocahmluis](https://github.com/bocahmluis)

## 📄 Lisensi

Copyright © BM 2025