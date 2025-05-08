# ✅ Keuntungan Menggunakan Virtual Environment (venv)

Menggunakan `venv` sangat disarankan dalam proyek machine learning dan computer vision karena:

- ✅ Menghindari konflik versi library saat menguji banyak algoritma (YOLOv8, CornerNet, SSD, RetinaNet, Deformable DETR, dll).
- ✅ Membuat proyek lebih terorganisir dan mudah direplikasi (misalnya saat diunggah ke GitHub atau digunakan dalam kerja tim).

---

# 🚀 Cara Cepat Membuat dan Mengaktifkan venv

Buka **Command Prompt** atau **Terminal** di folder root proyekmu, lalu jalankan:

`python -m venv venv`

## 🔄 Aktifkan Environment-nya

### Untuk **Windows**:

`venv\Scripts\activate`

### Untuk **Linux / Mac**:

`source venv/bin/activate`

---

> Setelah aktif, kamu bisa mulai menginstal library yang dibutuhkan menggunakan `pip install ...`.
> Misalnya: `pip install opencv-python torch torchvision` dll.
