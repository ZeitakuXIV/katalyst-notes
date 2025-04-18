<%*
// 1. GET USER INPUT (Hanya Judul & Penulis)
const title = await tp.system.prompt("Judul Materi (contoh: 'Deret Konvergen')");
const author = await tp.system.prompt("Nama Penulis");
const today = tp.date.now("DD-MM-YYYY");

// 2. AUTO-GENERATE FILENAME & METADATA
const filename = `${title.toLowerCase().replace(/[^\w\s-]/g, "").replace(/\s+/g, "-")}-${author}`;
await tp.file.rename(filename);
%>
## date: <% today %>
## tags: [#default] //edit kalau perlu
---

# 🎓 <% title %>
**Tanggal:** <% today %> \| **Author:**  <% author %>

## 🎯 Kompetensi Yang Didapatkan  
_(Apa yang berhasil dikuasai setelah belajar ini?)_  
1.  
2.  

## 🚀 Pengantar
{masukin pengantar materi disini kalau ada, mungkin sebagai lanjutan dari materi apa}

## 📚 Materi Inti 
//ini engga strict, silahkan nulis sesuka hati guys
### 📝 Definisi
- 
### 📌 Teorema/Persamaan Kunci
- 
### 🛣️ Langkah-langkah
- 
## ⚠️ Hal yang harus diperhatikan
- 
## ✍️ Contoh Soal


**Materi Terkait**:
- [[tambahkan disini]]