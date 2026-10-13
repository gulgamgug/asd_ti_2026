# 📘 Proyek 1 — Analisis dan Strategi Algoritma (ASD)

<p align="center">
  <strong>Penambahan Fungsionalitas Linked List</strong><br>
  Implementasi dan Pengujian Singly Linked List & Doubly Linked List
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-01-blue?style=for-the-badge" alt="Project 01">
  <img src="https://img.shields.io/badge/Course-ASD-orange?style=for-the-badge" alt="ASD">
  <img src="https://img.shields.io/badge/Language-Java-red?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
</p>

---

## 👥 Identitas Kelompok

**Kelas:** TI-D

| No. | Nama | NIM |
|:---:|---|---|
| 1 | Rivaldo Rizky Habibie | `255150707111046` |
| 2 | Raihan Lazuardi Ahmad | `255150700111034` |

## 📖 Deskripsi Proyek

Proyek ini merupakan tugas **Proyek 1 mata kuliah Analisis dan Strategi Algoritma (ASD)** yang berfokus pada penambahan dan penyempurnaan fungsionalitas struktur data *Linked List* menggunakan bahasa pemrograman Java.

Implementasi dilakukan pada dua jenis struktur data, yaitu **Singly Linked List** dan **Doubly Linked List**, dengan memperbaiki implementasi method yang sebelumnya masih berupa *dummy implementation*.

Melalui proyek ini, mahasiswa mempelajari pengelolaan node, penelusuran data, pencarian indeks, penghapusan elemen, traversal terbalik, serta konversi data *Linked List* menjadi array.

## 🎯 Tujuan

- Memahami cara kerja dan karakteristik Singly Linked List dan Doubly Linked List.
- Mengimplementasikan operasi pencarian, pengambilan, dan penghapusan data.
- Melakukan traversal dari head ke tail maupun dari tail ke head.
- Mengonversi elemen Linked List menjadi array secara berurutan.
- Menguji kebenaran implementasi menggunakan program pengujian yang disediakan.

## 🛠️ Fungsionalitas

Setiap method berikut diimplementasikan pada Singly Linked List maupun Doubly Linked List.

| No. | Method | Deskripsi |
|:---:|---|---|
| 1 | `get(int index)` | Mengembalikan data pada indeks tertentu, dengan indeks head dimulai dari `0`. |
| 2 | `indexOf(Object targetData)` | Mencari kemunculan pertama data dan mengembalikan indeksnya. Mengembalikan `-1` jika data tidak ditemukan. |
| 3 | `printReverse()` | Mencetak elemen Linked List dengan urutan terbalik, dari tail ke head. |
| 4 | `remove(Object targetData)` | Mencari dan menghapus node pertama yang memiliki data sesuai target. Mengembalikan `true` jika berhasil dan `false` jika tidak ditemukan. |
| 5 | `toArray()` | Mengembalikan seluruh data dalam bentuk array, berurutan dari head hingga tail. |

## 🧩 Struktur Data yang Digunakan

### 1. Singly Linked List

Singly Linked List merupakan struktur data linear yang setiap node-nya menyimpan data dan referensi ke node berikutnya.

`Head → Node → Node → Node → null`

Karakteristik utama:
- Traversal dilakukan dari head menuju tail.
- Setiap node memiliki satu referensi ke node berikutnya.
- Traversal terbalik memerlukan pendekatan khusus karena tidak tersedia referensi langsung ke node sebelumnya.

### 2. Doubly Linked List

Doubly Linked List merupakan struktur data linear yang setiap node-nya memiliki referensi ke node sebelumnya dan node berikutnya.

`null ← Node ⇄ Node ⇄ Node → null`

Karakteristik utama:
- Traversal dapat dilakukan ke depan maupun ke belakang.
- Setiap node memiliki referensi `prev` dan `next`.
- Traversal terbalik dapat dilakukan dengan memulai dari tail dan bergerak melalui referensi `prev`.

## 🧪 Pengujian

Pengujian dilakukan menggunakan file pengujian yang disediakan dalam instruksi proyek:

- `testSinglyLinkedList`
- `testDoublyLinkedList`

Pengujian ditujukan untuk memeriksa kebenaran hasil setiap method, termasuk perilaku ketika data ditemukan, data tidak ditemukan, serta penanganan node pada posisi head dan tail.

Aspek yang perlu diperhatikan selama pengujian:

- Ketepatan indeks yang dikembalikan oleh `get()` dan `indexOf()`.
- Urutan elemen yang dicetak oleh `printReverse()`.
- Keberhasilan penghapusan node oleh `remove()`.
- Kesesuaian isi array yang dihasilkan oleh `toArray()`.
- Konsistensi hubungan antarnode setelah operasi penghapusan.

## 💻 Teknologi

- **Bahasa Pemrograman:** Java
- **Struktur Data:** Singly Linked List dan Doubly Linked List
- **Version Control:** Git
- **Repository Hosting:** GitHub

## 📂 Struktur Repository

Struktur direktori mengikuti file dan package yang tersedia pada repository proyek.

```text
Proyek-1-ASD/
├── README.md
├── Kelompok.md
└── source-code/
    ├── LinkedList.java
    ├── SinglyLinkedList.java
    ├── DoublyLinkedList.java
    ├── testSinglyLinkedList.java
    └── testDoublyLinkedList.java
```

> **Catatan:** Struktur `source-code/` di atas merupakan ilustrasi. Sesuaikan nama direktori, file, dan package dengan struktur repository yang sebenarnya.

## 🚀 Cara Menjalankan

1. Clone repository proyek ke komputer lokal.
2. Buka proyek menggunakan IDE Java atau editor yang mendukung Java.
3. Pastikan seluruh source code dan file pengujian tersedia sesuai struktur repository.
4. Jalankan pengujian Singly Linked List dan Doubly Linked List.
5. Periksa hasil keluaran dan pastikan seluruh method berjalan sesuai spesifikasi.

Contoh perintah Git:

```bash
git clone <URL-REPOSITORY>
cd <NAMA-DIREKTORI-PROYEK>
```

## 📚 Referensi

- Modul dan instruksi tugas Proyek 1 ASD: **Penambahan Fungsionalitas Linked List**.
- Repository sumber proyek: [asd_tif_2026](https://bitbucket.org/adinu/asd_tif_2026/).

---

<p align="center">
  <strong>Proyek 1 ASD — Kelas TI-D</strong><br>
  <sub>Implementasi Struktur Data • Java • Linked List</sub>
</p>
