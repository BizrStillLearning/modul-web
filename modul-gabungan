# Modul Study Club HIMATIFA: Zero to Web (Membuat Website Pertama dari Nol)

**Pemateri:** Abidzar Dzakwan Sahudi  
**Durasi:** 90 Menit  
**Metode:** Ceramah Singkat & Live Coding Interaktif  

---

## 🎯 Tujuan Pembelajaran
Sesuai dengan silabus Study Club HIMATIFA, setelah mengikuti sesi ini peserta diharapkan:
1. Memahami dasar pembuatan website (Klien-Server, HTML, CSS, JS).
2. Mampu mengoperasikan VS Code.
3. Mampu menyusun struktur HTML dan mempercantiknya dengan CSS.
4. Berhasil merampungkan *project* website portofolio pribadi.

---

## 🛠️ Persiapan Alat Tempur
Sebelum memulai, pastikan seluruh peserta sudah menyiapkan:
- Laptop/PC.
- **Visual Studio Code (VS Code)** terinstal.
- Ekstensi **Live Server** terinstal di VS Code (untuk *auto-reload* browser).
- Browser (Google Chrome / Microsoft Edge).

## 💻 Panduan Live Coding (Sintaks Fundamental)

Sesi ini memakan waktu sekitar 60 menit. Pandu peserta mengetik kode berikut secara bertahap.

### 1. HTML (Kerangka Portofolio)
Kenalkan tag semantik dan struktur dasar.

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Portofolio Saya</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigasi -->
    <header>
        <nav>
            <h2>MyWeb</h2>
            <button id="tombol-gelap">Dark Mode</button>
        </nav>
    </header>

    <!-- Konten Utama -->
    <main>
        <section class="profil">
            <img src="foto-profil.jpg" alt="Foto Profil" class="foto">
            <h1>Halo, Saya [Nama Kalian]</h1>
            <p>Saya seorang mahasiswa IT yang sedang belajar Web Development.</p>
            <a href="#" class="btn-kontak">Hubungi Saya</a>
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>
```

### 2. CSS (Styling & Flexbox)
Fokus pada pewarnaan, Box Model (Margin/Padding), dan Flexbox untuk *layouting*.

```css
/* Reset Dasar */
* {
    margin: 0;
    padding: 0;
    font-family: sans-serif;
}

body {
    background-color: white;
    color: #333;
    transition: 0.3s; /* Efek transisi halus untuk dark mode */
}

/* Flexbox pada Navigasi */
header nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
    background-color: #f4f4f4;
}

/* Styling Profil */
.profil {
    text-align: center;
    padding: 50px 20px;
}

.foto {
    width: 150px;
    border-radius: 50%; /* Membuat foto menjadi bulat */
    margin-bottom: 20px;
}

/* Class tambahan untuk JavaScript (Dark Mode) */
.mode-gelap {
    background-color: #1e1e1e;
    color: white;
}

.mode-gelap header nav {
    background-color: #333;
}
```

### 3. JavaScript (DOM & Interaksi Sederhana)
Kenalkan konsep variabel, pencarian elemen, dan Event Listener untuk mengaktifkan fitur *Dark Mode*.

```javascript
// 1. Menangkap elemen HTML
const tombol = document.getElementById("tombol-gelap");

// 2. Menambahkan aksi ketika tombol diklik
tombol.addEventListener("click", function() {
    
    // 3. Menambah/menghapus class 'mode-gelap' pada elemen body
    document.body.classList.toggle("mode-gelap");
    
    // Opsional: Mengubah teks tombol
    if (document.body.classList.contains("mode-gelap")) {
        tombol.innerText = "Light Mode";
    } else {
        tombol.innerText = "Dark Mode";
    }
});
```

---

## 📝 Evaluasi Akhir & Tugas Mandiri

Di akhir sesi (Slide 13 & 14), berikan tugas kepada peserta untuk menguji pemahaman mereka:
1. Ganti foto profil menggunakan foto masing-masing.
2. Ubah teks nama, deskripsi diri, dan warna kesukaan pada CSS.
3. Pastikan tombol *Dark Mode* berfungsi dengan baik.

*Jangan lupa berikan motivasi bahwa error adalah hal yang biasa dalam belajar coding!*
