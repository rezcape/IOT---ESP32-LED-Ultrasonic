# Laporan Konfigurasi Channel dan Pengiriman Data IoT ke ThingSpeak

| Nama | NRP       |
|-------|-----------|
| Ahmad Syauqi Reza | 5027241085   |
| S. Farhan Baig | 5027241097  |
---

## 📌 Overview Project

Program ini melakukan hal berikut:

- **Mengukur Jarak** menggunakan sensor ultrasonik (misalnya HC-SR04) untuk mendeteksi jarak objek.
- **Memberi Peringatan** dengan menyalakan LED jika objek berada pada jarak ≤ 10 cm.
- **Mengirim Data** hasil pengukuran ke platform IoT **ThingSpeak** melalui koneksi Wi-Fi setiap 20 detik.

---

## 1. Membuat Channel Baru

Pada halaman **My Channels**, klik tombol **"New Channel"** untuk memulai konfigurasi stream data baru.

<img width="450" alt="image" src="https://github.com/user-attachments/assets/12d7cefc-55eb-4b51-92fc-26e2cf7fd7e7" />

---

## 2. Pengaturan Channel

Isi konfigurasi sebagai berikut:

- **Nama Channel**: `Tugas 2 IOT 085 & 097`
- **Field 1**:
  - Label: `Distance`
  - Status: Diaktifkan

Pengaktifan Field 1 memastikan bahwa channel siap menerima data jarak pada kolom tersebut.
Lalu tekan save pada bagian bawah halaman.

<img width="500" alt="image" src="https://github.com/user-attachments/assets/7e3ce73e-0efe-4d19-9d6d-455ce1e8bff9" />

---

## 3. Mengambil Write API Key

Buka tab **API Keys** untuk mendapatkan **Write API Key**.  
Contoh kunci: `ZHJ69INTGMMQCW6`

Write API Key ini digunakan di dalam program untuk autentikasi saat pengiriman data.

<img width="500" alt="image" src="https://github.com/user-attachments/assets/9bb3c009-e2ab-42c2-931f-f0b07b1779c4" />

---

## 4. Status Channel dan Data Masuk

Setelah perangkat mengirimkan data:

- **Jumlah Entri**: 25 entries
- **Entri Terakhir**: Less than a minute ago
- **Grafik Field 1 (Distance)**:
  - Nilai stabil di rentang **5.00 hingga 6.00**
  - Membuktikan integrasi perangkat dan ThingSpeak berhasil

<img width="500" alt="image" src="https://github.com/user-attachments/assets/541cb28a-5979-49ce-a5c5-9c02dfde55c4" />

---

## 5. Kesimpulan

Konfigurasi channel, penggunaan API Key, dan pengiriman data dari perangkat telah berjalan dengan baik. Data berhasil direkam, dan grafik pada Field 1 memverifikasi bahwa sistem berfungsi tanpa error.

