# CSS Float - Proyek Pembelajaran Properti Float CSS

Selamat datang! 👋 Proyek ini dirancang untuk membantu Anda memahami bagaimana properti **`float`** bekerja dalam CSS dengan cara yang praktis dan interaktif.

---

## 📚 Apa Itu Proyek Ini?

Proyek **CSS Float** adalah latihan koding yang mendemonstrasikan penggunaan properti `float` untuk mengatur tata letak elemen HTML. Anda akan belajar bagaimana membuat gambar dan teks berekor (text wrapping) menggunakan CSS, sekaligus memahami pentingnya properti `clear` untuk mengatur aliran elemen.

---

## 📁 Struktur Folder

Berikut penjelasan setiap file dalam proyek ini:

### **File HTML**

| File | Tujuan |
|------|--------|
| `index.html` | File HTML utama yang **belum lengkap**. Di sini Anda akan menemukan TODO list yang berisi tugas-tugas yang perlu diselesaikan. |
| `solution.html` | File HTML **solusi lengkap**. Gunakan file ini sebagai referensi jika Anda ingin melihat bagaimana hasilnya seharusnya terlihat. |

### **Gambar**

| File | Deskripsi |
|------|-----------|
| `cat.jpeg` | Gambar kucing dalam kotak yang digunakan di bagian "CatCSS". |
| `dog.jpeg` | Gambar anjing dalam kotak yang digunakan di bagian "DogCSS". |

### **File Tambahan**

| File | Tujuan |
|------|--------|
| `goal.png` | Tangkapan layar yang menunjukkan hasil akhir yang diharapkan. Gunakan ini sebagai panduan visual. |
| `.git/` | Folder Git untuk melacak versi kode Anda. |

---

## 🎯 Tujuan Pembelajaran

Setelah menyelesaikan proyek ini, Anda akan memahami:

1. **Properti `float`** - Cara menggunakan `float: left` dan `float: right` untuk memindahkan elemen ke sisi halaman
2. **Text Wrapping** - Bagaimana teks secara otomatis membungkus gambar yang di-float
3. **Properti `clear`** - Cara menggunakan `clear` untuk mengontrol elemen mana yang akan membungkus elemen float, dan elemen mana yang tidak
4. **Aliran Dokumen** - Pemahaman dasar tentang bagaimana browser mengatur elemen di halaman

---

## 🚀 Cara Memulai

### Langkah 1: Buka File `index.html`
Buka file `index.html` di browser favorit Anda (Chrome, Firefox, Safari, Edge, dll.). Anda akan melihat layout yang belum sempurna.

### Langkah 2: Lihat TODO List
Di dalam file `index.html`, ada komentar TODO yang berisi 3 tugas:

```html
<!-- TODO
1. Make both paragraph elements wrap around the image.
2. Use Float to move the cat div to the left and the dog div to the right.
3. Use clear to make the footer go below both the cat and dog div. -->
```

### Langkah 3: Edit CSS
Buka `index.html` dengan editor teks favorit Anda (VS Code, Sublime Text, Notepad++, dll.) dan edit bagian `<style>` untuk menyelesaikan ketiga tugas tersebut.

### Langkah 4: Verifikasi Hasil
Bandingkan hasil pekerjaan Anda dengan `solution.html` untuk memastikan layout Anda sudah benar.

---

## 📖 Penjelasan Konsep Utama

### Apa itu `float`?

Properti `float` dalam CSS digunakan untuk memindahkan elemen ke kiri atau kanan dari aliran dokumen normal. Elemen lain akan membungkus (wrap) di sekitar elemen yang di-float.

**Contoh:**
```css
.cat {
  float: left;      /* Gambar kucing bergerak ke kiri */
}

.dog {
  float: right;     /* Gambar anjing bergerak ke kanan */
}
```

### Apa itu `clear`?

Properti `clear` digunakan untuk membuat elemen "tidak membungkus" di sekitar elemen float. Elemen dengan `clear` akan pindah ke bawah elemen float.

**Contoh:**
```css
footer {
  clear: both;      /* Footer pindah ke bawah kedua elemen float */
}
```

---

## 💡 Tips Belajar

1. **Buka browser dev tools** (F12 atau Ctrl+Shift+I) untuk mengecek elemen dan style secara real-time
2. **Eksperimen** - Coba ubah nilai `float` dan `clear` untuk melihat apa yang terjadi
3. **Bandingkan** - Lihat perbedaan antara `index.html` dan `solution.html` untuk belajar
4. **Tidak ada kesalahan** - Bermain dengan kode adalah cara terbaik untuk belajar! 🎨

---

## 🔍 Catatan Penting

- **Browser Support** - Properti `float` didukung oleh semua browser modern. Namun, untuk layout kompleks, `flexbox` atau `CSS Grid` adalah pilihan yang lebih baik.
- **Layout Modern** - Di proyek profesional, `float` jarang digunakan untuk layout utama. Gunakan ini sebagai fondasi pembelajaran, kemudian pelajari `flexbox` dan `grid`.

---

## ❓ Pertanyaan yang Sering Diajukan

**Q: Apakah saya harus menggunakan `float` untuk semua layout?**
A: Tidak. `Float` berguna untuk kasus tertentu seperti membungkus teks di sekitar gambar. Untuk layout kompleks, gunakan `flexbox` atau `CSS Grid`.

**Q: Apa perbedaan antara `clear: left`, `clear: right`, dan `clear: both`?**
A: 
- `clear: left` - Elemen tidak membungkus elemen float di sisi kiri
- `clear: right` - Elemen tidak membungkus elemen float di sisi kanan
- `clear: both` - Elemen tidak membungkus elemen float di kedua sisi

**Q: Bagaimana jika saya terjebak?**
A: Lihat `solution.html` untuk melihat CSS yang benar, atau buka dev tools untuk menginspeksi elemen.

---

## 🎓 Langkah Berikutnya

Setelah menguasai `float`, Anda siap untuk mempelajari:
- ✅ **Flexbox** - Cara modern mengatur layout (lebih mudah dari float!)
- ✅ **CSS Grid** - Sistem layout dua dimensi yang powerful
- ✅ **Positioning** - `position: absolute`, `relative`, `fixed`, dll.
- ✅ **Responsive Design** - Membuat layout yang responsif di berbagai ukuran layar

---

## 📝 Lisensi & Kredit

Proyek ini dibuat untuk tujuan pembelajaran. Silakan gunakan, ubah, dan bagikan sesuai kebutuhan Anda!

---

**Selamat belajar! Ingat: setiap expert pernah menjadi pemula. Keep coding! 💻✨**
