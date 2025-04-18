# Format Penulisan Materi

Halo teman-teman! Ini adalah panduan cara menulis materi atau rangkuman di repositori ini. Gak perlu ribet, yang penting mudah dipahami dan konsisten. Yuk, kita mulai!

## 1. Gunakan Templater

Kalau bisa, coba gunakan **Templater** untuk nulis rangkumanmu! Ini akan membantu supaya struktur dan formatnya konsisten, dan kamu gak perlu mikir lagi soal layout atau heading yang perlu ditulis.

Kami bakal kasih folder template yang bisa kamu pakai, jadi kamu tinggal pilih dan sesuaikan dengan preferensimu. Dengan cara ini, tiap orang bisa nulis dengan cara yang mereka suka, tapi tetap terstruktur dengan baik.

## 2. Struktur Dasar

Setiap file itu bakal diatur dengan struktur yang simpel, dan ini dia contohnya:
### Judul dan Subjudul

- Mulai dengan judul yang jelas, misalnya “**Kalkulus 2 - Rangkuman Bab 1**”.
- Gunakan heading (`##`, `###`, dsb.) buat bagian-bagian penting.
```markdown
# Kalkulus 2 - Rangkuman Bab 1
## Deret Konvergen
### Pengantar
Sebelum masuk ke materi inti, tulis pengantar singkat tentang apa yang bakal dibahas. Cukup 2-3 kalimat aja biar orang ngerti tujuan materi ini.
```

### Isi Materi

Ini bagian utamanya! Pisahkan materi ke dalam beberapa bagian menggunakan heading. Kalau perlu, buat poin-poin atau daftar bernomor.
#### Contoh Penulisan:  
```markdown
## Teorema Deret Konvergen  
Deret `$\sum_{n=1}^\infty a_n$` dikatakan konvergen jika memenuhi kriteria tertentu.  

### Contoh Penerapan  
Misalnya, deret berikut konvergen saat `$p > 1$`:  
$$ \sum_{n=1}^\infty \frac{1}{n^p} $$
```

**Tips**:
- Gunakan LaTeX [`latex-guides.md`](./latex-guides.md),
- atau lampirin foto persamaannya aja di kertas.
**Format Rumus**:  
- Gunakan `$...$` untuk rumus inline (e.g., `$e^{i\pi} + 1 = 0$`).  
- Gunakan `$$...$$` untuk rumus terpisah (block).  

**Tips Obsidian**:  
- Install plugin LaTeX Suite untuk fitur autocomplete.  
- Gunakan `Ctrl + M` (Windows) untuk wrap teks dengan `$...$`.
### Penutup

Akhiri dengan kesimpulan singkat atau rangkuman materi. Gak usah panjang-panjang, cukup intinya aja.

```
## Kesimpulan
Deret konvergen adalah konsep dasar yang perlu dikuasai untuk melangkah ke topik-topik lebih lanjut.
```

## 3. Template yang Fleksibel

Kami bakal kasih folder template yang bisa kamu gunakan sesuai preferensimu. Setiap penulis bisa memilih template yang nyaman buat mereka, dan tentu aja, kamu bisa menyesuaikan isi dan struktur sesuai kebutuhan.

## 4. Penulisan yang Santai dan Mudah Dipahami

Gak perlu nulis dengan bahasa yang terlalu kaku. Cukup pakai bahasa yang jelas, dan jangan takut untuk jadi sedikit lebih santai. Yang penting, orang yang baca bisa ngerti dengan mudah.

## 5. Nama File  
- Format: `[topik]-[nama].md` (e.g., `kalkulus-2-andi.md`).  
- Gunakan **huruf kecil** dan **hyphen** (bukan spasi/underscore).  
- Contoh salah: `Kalkulus 2_Andi.md`.

## 6. Tips Nulis

- Gunakan format Markdown yang standar untuk heading, daftar, dan kode.
- Jangan takut untuk menambah penjelasan kalau ada yang perlu dijelaskan lebih lanjut.
- Kalau ada materi yang mirip atau saling berkaitan, kasih catatan di file kamu untuk menghindari duplikasi.

**Tips Commit Message**:  
Gunakan format: `docs: [tambah|perbaiki] [deskripsi]` (e.g., `docs: tambah contoh matriks`).  

---

### 📌 **Reminder**
- Pastikan judul file sesuai dengan materi yang kamu tulis.
- Cek lagi penulisan kamu sebelum di-commit, biar gak ada typo.
- **Metadata**: Pastikan header ada di setiap file.  
- **Nama File**: Gunakan format `[topik]-[nama].md`.  
- **Commit**: Cek pesan commit sebelum push.

---

Terima kasih sudah berkontribusi! Semoga panduan ini memudahkan kamu dalam menulis materi di repositori ini. Happy writing! 🚀
