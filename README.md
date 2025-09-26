# Chinook Project

Proyek ini dibuat untuk menyelesaikan tugas *Data Wrangling* pada database **Chinook** menggunakan PostgreSQL dan Python (pandas + SQLAlchemy).

## 📌 Pertanyaan Bisnis

1. Track manakah yang paling banyak menghasilkan pendapatan?
2. Genre musik apa yang paling populer berdasarkan jumlah pembelian?
3. Artist mana yang memberikan kontribusi pendapatan paling besar?

## 📂 Struktur Project

```
project-folder/
├── .venv             # Virtual environment
├── notebook.ipynb    # Jupyter Notebook utama
├── .env              # Konfigurasi koneksi database 
└── README.md         # Dokumentasi
```

---

## ⚙️ Panduan Virtual Environment

### Membuat Virtual Environment

Ada dua cara:

1. **Lewat VS Code**

   * Tekan `Ctrl + Shift + P`
   * Ketik `Python: Create Environment`
   * Pilih `venv`
   * Pilih versi Python yang tersedia

2. **Lewat Command Prompt (Windows) / Terminal (Mac/Linux)**

   ```bash
   cd <directory_project>
   python -m venv .venv
   ```

   Jika berhasil, akan muncul folder baru bernama `.venv`.

---

### Mengaktifkan Virtual Environment

* **Windows**

  ```bash
  .venv\Scripts\activate.bat
  ```
* **Mac/Linux**

  ```bash
  source .venv/bin/activate
  ```

Untuk menonaktifkan:

```bash
deactivate
```

---

### Mengecek Library Terinstall

Semua library yang terinstall ada di:

```
.venv/Lib/site-packages
```

---

### Menjalankan Project

1. Buka `notebook.ipynb` di VS Code.
2. Klik **Select Kernel** (pojok kanan atas).
3. Pilih environment dari:

   * `.venv\Scripts\python.exe` (Windows), atau
   * `.venv/bin/python.exe` (Mac/Linux).
4. Jalankan cell di notebook.

---

## 📦 Instal Dependency

Jika sudah aktif di `.venv`, install library:

```bash
pip install pandas sqlalchemy python-dotenv matplotlib seaborn plotly psycopg2-binary nbformat
```

---

## 🔑 File `.env`

Buat file `.env` di root project untuk menyimpan kredensial PostgreSQL: Sudah dikirim by wa ya man-teman