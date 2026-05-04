# Project Management System with RBAC (Role-Based Access Control)

Sistem Manajemen Proyek berbasis web yang dirancang untuk mengoptimalkan operasional di **PT. General Software Indonesia**. Sistem ini menggantikan proses pengelolaan proyek manual yang sebelumnya menggunakan spreadsheet dan WhatsApp, guna meningkatkan efisiensi, akurasi data, dan transparansi monitoring proyek secara _real-time_.

## Fitur Utama

Sistem ini mengimplementasikan metode **Role-Based Access Control (RBAC)** untuk memastikan setiap pengguna hanya memiliki akses sesuai dengan tugas dan tanggung jawabnya.

- **Multi-Role Dashboard**: Tampilan dashboard yang dipersonalisasi untuk **Administrator**, **Admin**, dan **Editor**.
- **Manajemen Proyek**: Fitur utama untuk mengelola siklus hidup proyek, mulai dari pembuatan, distribusi tugas ke editor, hingga unggah dokumen hasil kerja.
- **Finance Dashboard**: Visualisasi data keuangan seperti total pendapatan, piutang, dan status pembayaran dalam bentuk grafik interaktif (khusus untuk Administrator & Admin).
- **Monitoring Kinerja**: Pemantauan performa editor dan admin berdasarkan poin aktivitas dan penyelesaian tugas.
- **Manajemen RBAC**: Pengaturan fleksibel untuk _Role_, _Permissions_, dan data pengguna (_User_) dalam sistem.
- **Manajemen Client & Langganan**: Pengelolaan basis data klien serta paket layanan berbasis langganan (_subscription_).

## Teknologi yang Digunakan

Sistem ini dikembangkan menggunakan _stack_ teknologi modern untuk memastikan performa dan skalabilitas:

- **Backend**: Laravel 12 (PHP 8)
- **Frontend**: React.js & TypeScript
- **UI Framework**: Tailwind CSS & Shadcn UI
- **Database**: MySQL
- **Web Server**: Apache

## Struktur Hak Akses (RBAC)

1.  **Administrator**: Memiliki kendali penuh terhadap seluruh fitur sistem, termasuk manajemen role, permission, keuangan, dan monitoring seluruh staf.
2.  **Admin**: Berfokus pada pengelolaan data klien, input data proyek, distribusi pekerjaan, serta akses terbatas pada laporan keuangan.
3.  **Editor**: Hanya dapat mengakses proyek yang ditugaskan, mengunduh instruksi, mengunggah hasil pekerjaan, dan melihat performa pribadi.

## Tentang Proyek

Proyek ini merupakan bagian dari Laporan Kerja Praktik di **Universitas Semarang (USM)**. Pengembangan sistem ini bertujuan untuk memberikan solusi teknologi bagi perusahaan publikasi jurnal ilmiah dan pengolahan data dalam mengelola koordinasi tim secara lebih terstruktur.

**Disusun Oleh:** Ngesthi Farrel Natan Ramadhana (G.231.19.0071)  
Program Studi S1-Teknik Informatika, Universitas Semarang
