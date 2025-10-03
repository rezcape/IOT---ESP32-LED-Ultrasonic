
Dari halaman My Channels, kami menekan tombol "New Channel" (dilingkari merah) untuk memulai konfigurasi stream data baru.

<img width="941" height="936" alt="image" src="https://github.com/user-attachments/assets/7e3ce73e-0efe-4d19-9d6d-455ce1e8bff9" />
Nama: Channel diberi identitas "Tugas 2 IOT 085 & 097". Field 1: Diberi label "Distance" dan diaktifkan. Ini memastikan channel siap menerima data jarak pada Field 1.

<img width="1600" height="550" alt="image" src="https://github.com/user-attachments/assets/9bb3c009-e2ab-42c2-931f-f0b07b1779c4" />
Kami mengakses tab API Keys untuk mengambil Write API Key (contoh: ZHJ69INTGMMQCW6). Kunci ini sangat penting; ia dimasukkan ke dalam kode perangkat untuk mengautentikasi setiap pengiriman data.
  
<img width="1600" height="687" alt="image" src="https://github.com/user-attachments/assets/541cb28a-5979-49ce-a5c5-9c02dfde55c4" />
Halaman Channel Stats mengonfirmasi proses berjalan lancar: 25 Entries tercatat, dan entri terakhir masuk "less than a minute ago". Grafik Field 1 Chart menampilkan visualisasi data Distance, dengan nilai stabil di antara 5.00 dan 6.00, memverifikasi keberhasilan integrasi sistem.
# Laporan Konfigurasi Channel dan Pengiriman Data IoT ke ThingSpeak

## 1. Membuat Channel Baru

Pada halaman **My Channels**, klik tombol **"New Channel"** (seperti yang dilingkari merah pada gambar). Langkah ini digunakan untuk memulai konfigurasi stream data baru.
<img width="619" height="302" alt="image" src="https://github.com/user-attachments/assets/12d7cefc-55eb-4b51-92fc-26e2cf7fd7e7" />

## 2. Pengaturan Channel

Isi konfigurasi sebagai berikut:

- **Nama Channel**: `Tugas 2 IOT 085 & 097`
- **Field 1**:
  - Label: `Distance`
  - Status: Diaktifkan

Pengaktifan Field 1 memastikan bahwa channel siap menerima data jarak pada kolom tersebut.
<img width="1600" height="550" alt="image" src="https://github.com/user-attachments/assets/9bb3c009-e2ab-42c2-931f-f0b07b1779c4" />

## 3. Mengambil Write API Key

Buka tab **API Keys** untuk mendapatkan **Write API Key**.  
Contoh kunci yang digunakan: `ZHJ69INTGMMQCW6`

Write API Key ini berfungsi sebagai autentikasi agar perangkat dapat mengirim data ke channel yang telah dibuat.
<img width="1600" height="550" alt="image" src="https://github.com/user-attachments/assets/9bb3c009-e2ab-42c2-931f-f0b07b1779c4" />

## 4. Status Channel dan Data Masuk

Setelah perangkat mengirimkan data:

- **Jumlah Entri**: 25 entries tercatat
- **Waktu Entri Terakhir**: Kurang dari satu menit yang lalu
- **Grafik Field 1 (Distance)**:
  - Menampilkan data jarak dengan nilai yang stabil di rentang **5.00 hingga 6.00**
  - Visualisasi ini menjadi bukti bahwa integrasi perangkat dan ThingSpeak berhasil
<img width="1600" height="687" alt="image" src="https://github.com/user-attachments/assets/541cb28a-5979-49ce-a5c5-9c02dfde55c4" />

## 5. Kesimpulan

Konfigurasi channel, penggunaan API Key, dan pengiriman data dari perangkat telah berjalan sesuai rencana. Data berhasil terekam, dan grafik pada Field 1 memverifikasi bahwa sistem berfungsi dengan baik tanpa error.

