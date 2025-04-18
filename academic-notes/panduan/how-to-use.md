# How to Use This Repository

Selamat datang di repositori materi kuliah! Berikut adalah panduan tentang bagaimana cara berkontribusi dan menggunakan repositori ini.

## 1. Cloning Repository

Untuk mulai menggunakan repositori ini, kamu perlu **clone** repositorinya ke komputer kamu. Gunakan perintah berikut di terminal:

~~~bash
git clone https://github.com/username/katalyst-notes.git
~~~

Gantilah `username` dengan nama pengguna GitHub kamu.

## 2. Struktur Folder

Repositori ini diorganisasi dengan struktur folder berdasarkan **semester** dan **topik**. Setiap semester atau topik memiliki subfolder tersendiri. Berikut contoh struktur folder:

```
academic-notes/
├── semester-1/
│   ├── [nama-matkul]/
│   │   ├── materi/
│   │   ├── uts/
│   │   └── uas/
│   └── README.md
│
├── semester-2/
│   ├── [nama-matkul]/
│   │   ├── materi/
│   │   ├── uts/
│   │   └── uas/
│   └── README.md
│
├── panduan/
│   ├── how-to-use.md
│   ├── kontribusi.md
│   └── format-penulisan.md
│
├── assets/
│   └── gambar/
│
├── README.md
└── CONTRIBUTING.md
```

Dalam setiap folder semester, kamu akan menemukan subfolder yang berisi materi atau rangkuman yang relevan dengan mata kuliah atau topik tersebut.

## 3. Menambahkan Materi Baru

Jika kamu ingin menambahkan materi kuliah atau rangkuman, cukup ikuti langkah-langkah berikut:

1. Pilih folder yang sesuai dengan **semester** dan **topik** yang kamu ingin tambahkan materinya.
2. Buat file baru dengan format **Markdown (.md)**.
3. Berikan nama file sesuai dengan **topik** dan **nama kamu** atau **tanggal** jika perlu. Misalnya:
   - `kalkulus-2-andi.md`
   - `kalkulus-2-2025-04-18.md`
4. Tulis materi atau rangkuman yang ingin kamu bagi.

## 4. Mengedit Materi yang Ada

Jika kamu ingin mengedit materi yang sudah ada, lakukan hal-hal berikut:

1. **Clone** repositori jika belum.
2. Temukan file yang ingin kamu edit dalam folder yang relevan.
3. Buat **modifikasi** yang diperlukan dalam file tersebut.
4. Simpan perubahan dan pastikan nama file tetap konsisten.

Jika ada versi baru dari file yang sama, cukup beri **penanda** dengan menambahkan angka versi atau nama kamu pada nama file (misalnya, `kalkulus-2-budi-v2.md`).

## 5. Commit dan Push Perubahan

Setelah selesai mengedit, lakukan commit dan push perubahanmu:

1. Tambahkan file yang telah kamu edit atau buat:

~~~bash
git add .
~~~

2. Commit perubahanmu dengan pesan yang jelas:

~~~bash
git commit -m "Menambahkan rangkuman kalkulus-2 oleh Andi"
~~~

3. Push perubahanmu ke repositori:

~~~bash
git push origin main
~~~

## 6. Kolaborasi dengan Pengguna Lain

Repositori ini memungkinkan **kolaborasi** yang mudah:

- **Menambahkan materi baru**: Kamu bisa langsung membuat file baru sesuai dengan topik dan semester.
- **Mengedit materi**: Jika ada materi yang perlu revisi, cukup edit file tersebut dan push perubahanmu.
- **Melihat materi orang lain**: Semua orang dapat melihat materi yang ditambahkan oleh kontributor lain dalam folder yang sesuai.

## 7. Review dan Merge

- Setiap perubahan akan langsung di-push ke repositori dan dapat langsung dilihat oleh kontributor lain.
- Pastikan untuk **menjaga konsistensi** dalam nama file dan format Markdown.
  
---

### 🔧 **Tips**
- Gunakan struktur folder dan penamaan file yang konsisten untuk memudahkan navigasi.
- Berikan komentar di dalam file Markdown jika ada bagian yang perlu diperjelas.
- Pastikan file tidak berisi duplikasi materi untuk menjaga kejelasan dan kemudahan akses.

---

Terima kasih telah berkontribusi! Jika ada pertanyaan, jangan ragu untuk menghubungi kami!
>- Tim Katalystic
