# 🛒 Django Product Management System

Sistem manajemen produk sederhana menggunakan Django. Aplikasi ini memungkinkan pengguna untuk menambahkan, melihat, mengedit, dan menghapus data produk.

## 🚀 Fitur

- ✅ Tambah Produk
- 📋 Lihat Daftar Produk
- ✏️ Edit Produk
- 🗑️ Hapus Produk
- 💬 Pesan notifikasi sukses setiap aksi
- 📄 Menggunakan Django Model, Form, dan Template

## 🛠️ Teknologi yang Digunakan

- Python 3.x
- Django 4.x
- HTML (Template Django)

## 🧑‍💻 Instalasi dan Menjalankan Proyek

1. **Clone repository ini**
```bash
git clone https://github.com/NaufalAqil18/Tugas-8-PPL.git
cd django-product-manager
````

2. **Aktifkan virtual environment (opsional tapi disarankan)**

```bash
python -m venv env
source env/bin/activate  # Linux/macOS
env\Scripts\activate     # Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt  # Jika ada
# Jika belum dibuat, install Django langsung:
pip install django
```

4. **Migrasi database**

```bash
python manage.py migrate
```

5. **Jalankan server**

```bash
python manage.py runserver
```

6. **Buka di browser**

```
http://localhost:8000
```

## 📁 Struktur Proyek Singkat

```
├── product_manager/        # Folder utama Django project
├── products/               # Aplikasi produk
│   ├── models.py           # Model produk
│   ├── views.py            # Logic tampilan (CRUD)
│   ├── urls.py             # Routing internal
│   ├── templates/
│   │   └── products/       # Template HTML
├── db.sqlite3              # Database lokal
├── manage.py
└── README.md
```

## 📄 License

Proyek ini open-source dan bebas digunakan untuk pembelajaran.

---

## 🙋‍♂️ Kontribusi

Silakan fork dan pull request jika ingin berkontribusi atau menambahkan fitur lain.
