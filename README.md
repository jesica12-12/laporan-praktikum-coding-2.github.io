# Laporan Praktikum Coding 2: Website Daftar Mahasiswa Berprestasi

Proyek ini adalah implementasi tugas **Laporan 2 Coding Pend. Bahasa Inggris** yang berfokus pada pembuatan tabel HTML yang kompleks dan menarik. Website ini menampilkan data mahasiswa berprestasi dan wajib memanfaatkan berbagai fitur lanjutan HTML Table (`thead`, `tfoot`, `rowspan`, `colspan`) serta *styling* menggunakan CSS Internal.

## 👤 Informasi Pembuat Proyek

* **Nama:** Jasicha Dwi Restuty
* **NPM:** A1B025106
* **Mata Kuliah:** Coding Pend. Bahasa Inggris
* **Judul Website:** Daftar Mahasiswa Berprestasi Universitas Bengkulu 2025

## 📝 Deskripsi Proyek

File `index.html` memuat tabel data 5 mahasiswa berprestasi dengan desain yang disesuaikan (*matching theme*) dengan warna identitas **Universitas Bengkulu (UNIB)**, yaitu **Biru Tua (#003399)** dan **Kuning Emas (#FFD700)**.

### Fitur Utama Estetika

* **Tema Warna:** Biru Tua dan Kuning Emas, diselaraskan dengan logo UNIB.
* **Desain Modern:** Penerapan *box-shadow*, *border-radius*, dan efek *hover*.
* **Visual Aid:** Perbedaan warna latar pada baris genap dan ganjil (`nth-child(even)`).

## ✅ Kepatuhan Terhadap Spesifikasi Teknis

### 1. Struktur Wajib HTML dan Konten

| Elemen/Atribut | Status | Keterangan |
| :--- | :--- | :--- |
| **Elemen Struktur** | ✔️ | Menggunakan `<caption>`, `<thead>`, `<tbody>`, dan `<tfoot>`. |
| **Data** | ✔️ | Mengandung minimal 5 data mahasiswa. |

### 2. Implementasi Atribut Lanjutan

| Atribut | Status | Keterangan |
| :--- | :--- | :--- |
| **`colspan` (Wajib)** | ✔️ | Digunakan untuk kolom Nama Mahasiswa. |
| **`rowspan` (Wajib)** | ✔️ | Digunakan pada baris *header* (`<th>` kolom No, Prodi, IPK) untuk memenuhi kewajiban `rowspan` minimal 1 kali. |
| **Semantik (`scope`)** | ✔️ | Menggunakan `scope="col"` dan `scope="row"`. |

### 3. Styling dengan CSS Internal

| Kriteria Styling | Status | Keterangan |
| :--- | :--- | :--- |
| **Header/Footer Warna** | ✔️ | Warna berbeda pada `thead` dan `tfoot`. |
| **Border & Font** | ✔️ | `border-collapse: collapse;`, *font sans-serif*, dan *padding*. |
| **Estetika Baris** | ✔️ | Baris genap/ganjil (`:nth-child`) dan efek *hover*. |

## 📦 Struktur Proyek
