Tentu, berikut adalah deskripsi proyek yang terstruktur dan profesional yang bisa Anda gunakan sebagai konten untuk file **`README.md`** di repositori GitHub Anda.

-----

# MyTask Dashboard Admin (Responsive CRUD UI) 🚀

## Deskripsi Singkat

**MyTask Dashboard Admin** adalah *single-page application* (SPA) sederhana yang mensimulasikan antarmuka dashboard manajemen tugas dan proyek. Proyek ini dikembangkan menggunakan **HTML, Bootstrap 5, jQuery, dan JavaScript murni**. Fokus utamanya adalah pada desain UI/UX yang **responsif** penuh di berbagai perangkat (Desktop, Tablet, Mobile) dan implementasi fungsi dasar **CRUD (Create, Read, Update, Delete)** data proyek menggunakan *client-side storage* (array JavaScript).

## ✨ Fitur Utama

  * **Responsif Penuh:** Tata letak disesuaikan secara dinamis menggunakan Bootstrap Grid System, memastikan tampilan yang optimal tanpa *horizontal scroll* yang tidak diinginkan di perangkat *mobile*.
  * **Sidebar Toggle:** Navigasi samping yang dapat disembunyikan/dimunculkan, dengan tombol tutup (`X`) khusus di tampilan *mobile* untuk kemudahan akses.
  * **Simulasi CRUD:** Mengelola data proyek secara langsung di *frontend* (tanpa *database* eksternal):
      * **Create:** Menambahkan proyek baru melalui modal form.
      * **Read:** Menampilkan data di **Info Cards**, **Project Status Cards**, dan **Tabel Proyek**.
      * **Update:** Mengubah detail proyek melalui tombol **Edit**.
      * **Delete:** Menghapus data proyek melalui tombol **Hapus** dengan konfirmasi modal.
  * **Visualisasi Data:**
      * **Task Statistic:** Simulasi *Donut Chart* yang menunjukkan progress tugas (Completed, In Progress, Not Started).
      * **Task Schedule:** Simulasi *Gantt Chart* untuk visualisasi jadwal tugas.
  * **Teknologi Frontend Murni:** Implementasi data dan logika interaksi sepenuhnya ditangani oleh JavaScript dan jQuery.

## 🛠️ Teknologi yang Digunakan

  * **HTML5**
  * **CSS3** (Kustom)
  * **Bootstrap v5.3:** Untuk kerangka kerja *styling* dan komponen dasar.
  * **JavaScript (ES6):** Logika CRUD dan manipulasi DOM.
  * **jQuery:** Untuk manajemen *event* dan manipulasi DOM yang efisien.
  * **Font Awesome:** Untuk ikonografi.

## 📁 Struktur File

```
mytask-dashboard-responsi/
├── index.html          # Struktur Dashboard (Layout Utama)
├── style.css           # Styling dan Media Queries (Responsif)
├── script.js           # Data, Logika CRUD, dan Fungsi Rendering
└── README.md           # File Deskripsi Proyek (Saat ini)
```

## 🖥️ Tampilan Responsif

Proyek ini telah dioptimalkan agar elemen-elemennya menumpuk dengan benar saat berpindah dari tampilan desktop ke mobile (kolom 8/4 menumpuk menjadi 100%):

| Tampilan Desktop | Tampilan Mobile |
| :---: | :---: |
|  |  |

## 🚀 Cara Menjalankan Proyek

1.  **Clone Repositori:**
    ```bash
    git clone https://github.com/USERNAME_ANDA/NAMA_REPOS_ANDA.git
    cd NAMA_REPOS_ANDA
    ```
2.  **Buka File:** Buka file `index.html` langsung di *browser* Anda (`file:///path/to/index.html`).
3.  **Deploy (Opsional):** Proyek ini siap untuk di-deploy menggunakan **GitHub Pages** karena tidak memerlukan *backend*.
