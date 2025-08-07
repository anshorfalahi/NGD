# Love Universe 🌌

Sebuah project kecil untuk menampilkan halaman web personal yang berisi pesan, foto, dan musik untuk orang terkasih. Dibuat dengan teknologi Three.js untuk menciptakan efek partikel yang indah di luar angkasa.

## Kustomisasi

Anda dapat dengan mudah mengubah konten halaman ini sesuai keinginan Anda. Semua perubahan dilakukan di dalam file `index.html`.

### 1. Mengganti Teks ✍️

Teks utama yang ditampilkan di tengah layar dapat diubah.

1.  Buka file `index.html`.
2.  Cari baris kode berikut (sekitar baris 80):
    ```javascript
    const textToRender = 'Happy National Girlfriend Day Iaaku♡';
    ```
3.  Ganti tulisan di dalam tanda kutip (`'...'`) dengan pesan yang Anda inginkan.

### 2. Mengganti Foto 🖼️

Anda bisa menambahkan satu atau lebih foto untuk ditampilkan secara acak di antara partikel.

1.  **Tambahkan file foto Anda:** Salin file gambar Anda (misalnya, `foto.jpg`, `gambar.png`) ke dalam folder utama project ini, sejajar dengan `index.html`.
2.  **Ubah kode:** Buka file `index.html` dan cari baris kode berikut (sekitar baris 98):
    ```javascript
    const photoUrls = [
        'iaa.jpg',
    ];
    ```
3.  Ganti `'iaa.jpg'` dengan nama file foto Anda. Jika Anda punya lebih dari satu foto, tambahkan seperti ini:
    ```javascript
    const photoUrls = [
        'foto1.jpg',
        'foto2.png',
        'gambar_lain.gif'
    ];
    ```

### 3. Mengganti Audio 🎵

Musik latar belakang juga dapat diganti dengan lagu pilihan Anda.

1.  **Tambahkan file audio Anda:** Salin file audio Anda (misalnya, `lagu.mp3`) ke dalam folder utama project.
2.  **Ubah kode:** Buka file `index.html` dan cari baris kode berikut (sekitar baris 53):
    ```html
    <audio id="background-music" loop src="Ed Sheeran - Perfect.mp3 "></audio>
    ```
3.  Ganti `Ed Sheeran - Perfect.mp3` dengan nama file audio Anda.

---

Selamat mencoba dan semoga orang terkasih Anda menyukainya! ❤️
