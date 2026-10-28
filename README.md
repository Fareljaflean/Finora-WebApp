# Finora - Financial Management Web App

Finora adalah aplikasi web manajemen keuangan personal modern yang dirancang responsif untuk desktop dan mobile, terintegrasi dengan database cloud **Supabase**.

## 🚀 Fitur Utama
- **Dashboard Ringkasan Saldo**: Menampilkan saldo total real-time, status keuangan, dan navigasi cepat.
- **Pencatatan Transaksi**: Tambah pemasukan dan pengeluaran dengan kategori spesifik.
- **Budgeting & Goals Finansial**: Atur anggaran bulanan dan pantau progres pencapaian target tabungan secara interaktif.
- **Analisis & Grafik**: Statistik visual arus kas menggunakan Chart.js (Mingguan, Bulanan, Tahunan).
- **Integrasi Supabase Cloud**: Sinkronisasi database cloud untuk tabel `transactions` dan `goals` serta fitur real-time sync.
- **Desain Responsif**: Tampilan desktop dengan sidebar navigasi dan tampilan mobile dengan header serta bottom navigation bar.

## 🛠️ Teknologi
- **HTML5 & CSS3** (Tailwind CSS CDN)
- **JavaScript Modern (ES6+)**
- **Supabase JS Client (@supabase/supabase-js v2)**
- **Chart.js** & **Font Awesome 6**

## 🗄️ Menyiapkan Database Supabase
Jalankan skrip SQL di file [`supabase_schema.sql`](supabase_schema.sql) pada menu **SQL Editor** di dashboard project Supabase Anda untuk membuat tabel `transactions` dan `goals` beserta policy RLS yang diperlukan.

## 📦 Menjalankan Secara Lokal
Cukup buka file `index.html` di browser favorit Anda.
