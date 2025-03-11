# 🚀 Odoo Maintenance - Age Replacement Method

## 📌 Deskripsi Proyek

Proyek ini adalah implementasi **penjadwalan preventive maintenance** menggunakan **metode Age Replacement** di **ERP Odoo**.  
Modul ini dirancang untuk membantu dalam **mengelola jadwal penggantian komponen mesin** berdasarkan data historis kegagalan.

## ✅ Fitur Utama

- 📊 **Manajemen Mesin & Komponen**: Input dan pemantauan data mesin & komponen.
- 🔢 **Perhitungan TTF & TTR**: Menghitung *Time to Failure (TTF)* dan *Time to Repair (TTR)*.
- 📉 **Estimasi MTTF & MTTR**: Prediksi interval penggantian komponen berdasarkan metode Age Replacement.
- 📈 **Dashboard & Laporan**: Visualisasi analisis maintenance.
- 🔔 **Notifikasi Penggantian**: Pengingat otomatis jika waktu penggantian sudah mendekati.

## ⚙️ Cara Kerja Modul

1. **Input Data** → Pengguna memasukkan data mesin & komponen.
2. **Perhitungan TTF & MTTR** → Sistem menghitung waktu antar kegagalan dan waktu perbaikan.
3. **Analisis Preventive Maintenance** → Menggunakan metode Age Replacement untuk menentukan interval penggantian optimal.
4. **Laporan & Dashboard** → Menampilkan hasil analisis dalam bentuk grafik & tabel.

## 📸 Screenshot Tampilan

Berikut adalah beberapa tampilan dari sistem:

### **1 Form Input Komponen & Mesin**
📌 Menunjukkan bagaimana data mesin dan komponen dikelola dalam sistem.  
![input komponen](screenshots/komponen.png)
![input mesin](screenshots/mesin.png)

### **2 Perhitungan TTF & TTR**
📌 Inti dari metode Age Replacement, di mana sistem menghitung *Time to Failure* dan *Time to Repair*.  
![Perhitungan TTF TTR](screenshots/ttf_ttr.png)

### **3 History Kerusakan & Frekuensi Kegagalan**
📌 Data historis kegagalan yang digunakan sebagai dasar analisis maintenance.  
![History Kerusakan](screenshots/history.png)

### **4 Prediksi Pergantian Komponen**
📌 Sistem menentukan interval penggantian optimal berdasarkan metode Age Replacement.  
![Prediksi Pergantian](screenshots/prediksi.png)

### **5 penjadwalan pergantian komponen**
📌 Sistem menentukan kapan penggantian optimal berdasarkan metode Age Replacement.  
![Prediksi Pergantian](screenshots/penjadwalan.png)

## 🛠️ Teknologi yang Digunakan

- **Odoo ERP** (Python, XML)
- **PostgreSQL** (Database Management)
- **ORM Odoo** (Object-Relational Mapping)
- **Analisis Data** (MTTF, MTTR, Reliability Function)

## 📜 Lisensi
Proyek ini dikembangkan untuk keperluan akademik dan pengembangan lebih lanjut.  
Lisensi: 

## 📩 Kontak

📧 Email: irmanskhan785@gmail.com
