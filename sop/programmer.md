# SOP: Programmer

## 1. Tujuan
Menyediakan pedoman standar bagi programmer dalam melaksanakan tugas pengembangan sistem informasi internal, pemeliharaan aplikasi, dan dukungan teknis kepada tim lain secara efisien, terstruktur, dan terdokumentasi.

---

## 2. Tanggung Jawab Utama
- Membangun, mengembangkan, dan memelihara sistem informasi internal.
- Melakukan debugging, troubleshooting, dan perbaikan sistem.
- Menyediakan dukungan teknis dan solusi teknologi untuk tim lain.
- Menyusun dokumentasi teknis untuk setiap sistem dan fitur yang dikembangkan.

---

## 3. Workflow Kerja

### 3.1. Penerimaan Tugas
- Terima tugas secara resmi dari Project Manager (PM) atau Koordinator melalui Trello / Notion.
- Tinjau ruang lingkup tugas, spesifikasi teknis, dan deadline.

### 3.2. Perencanaan & Pembagian Tugas
- Buat perencanaan teknis (arsitektur, teknologi, estimasi waktu).
- Bagi modul atau sub-tugas jika bekerja dalam tim.
- Susun dokumentasi awal (technical spec) jika diperlukan.

### 3.3. Pengembangan & Pengujian
- Kembangkan sistem secara modular sesuai standar penulisan kode.
- Gunakan Git (GitHub) untuk version control.
- Lakukan testing (unit/integration) secara rutin.
- Komit kode secara berkala dengan pesan commit yang jelas.

### 3.4. Code Review & Integrasi
- Ajukan pull request untuk ditinjau oleh tim.
- Tanggapi masukan reviewer dan lakukan revisi jika perlu.
- Merge ke branch utama setelah review disetujui.

### 3.5. Deployment
- Lakukan deployment ke staging/production (manual atau CI/CD).
- Uji fungsi dasar pasca-deploy (smoke testing).

### 3.6. Dokumentasi
- Dokumentasikan:
  - Modul/fitur baru
  - API endpoint (Swagger/Postman/Markdown)
  - Struktur dan logika kode penting

---

## 4. Tools & Teknologi

| Kategori         | Tools                                      | Fungsi                                       |
|------------------|---------------------------------------------|----------------------------------------------|
| Version Control   | Git, GitHub                                | Kolaborasi kode & versioning                 |
| Editor            | Visual Studio Code (VS Code)               | Lingkungan pengembangan                      |
| Manajemen Tugas   | Trello, Notion                             | Pengelolaan dan pelacakan progres tugas      |
| Dokumentasi       | Notion, GitHub Wiki, Markdown              | Penyimpanan dokumentasi teknis               |
| Testing           | Postman, Jest, Pytest, PHPUnit, dll.       | Pengujian unit/integrasi/API                 |
| Deployment        | Vercel, Netlify, Docker, GitHub Actions    | Deployment manual atau otomatis (CI/CD)      |

---

## 5. Standar Kode
- Gunakan penamaan variabel yang jelas dan deskriptif.
- Tambahkan komentar untuk logika kompleks.
- Terapkan konsistensi gaya penulisan (Prettier, ESLint, dsb.).
- Hindari data hardcoded, gunakan file konfigurasi.

---

## 6. Lain-lain
- Jaga komunikasi aktif antar anggota tim.
- Lakukan backup sebelum perubahan besar.
- Terapkan praktik secure coding.
- Ikuti retrospective meeting untuk evaluasi kerja jika tersedia.

