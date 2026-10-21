# AI Memprediksi Angka 3 dan 5

Website sederhana berbasis HTML/CSS/JavaScript untuk menjalankan model gambar Teachable Machine melalui webcam.

## Menjalankan
1. Ekstrak folder proyek dan buka di VS Code.
2. Ekspor model dari Teachable Machine sebagai **TensorFlow.js**.
3. Salin `model.json`, `metadata.json`, dan file `.bin` ke folder `my_model`.
4. Pasang ekstensi VS Code **Live Server**.
5. Klik kanan `index.html` → **Open with Live Server**.
6. Tekan **Mulai kamera** dan izinkan akses kamera.

Kamera biasanya membutuhkan `localhost` atau HTTPS. Jangan membuka `index.html` langsung dengan `file://`.

## Penting
Paket ini tidak menyertakan model AI terlatih. Masukkan model milikmu ke `my_model/`. Pastikan kelas model mencakup angka `3` dan `5`. TensorFlow.js dan library Teachable Machine dimuat melalui CDN, jadi koneksi internet diperlukan.
