# Rezha Anugrah Putra — Personal Portfolio

Website portofolio pribadi yang dirancang untuk menampilkan perjalanan akademik, proyek, dan pengalaman organisasi sebagai mahasiswa Sistem Informasi Universitas Brawijaya dengan fokus karier sebagai Product Manager.

🔗 Live Site: [rezha-portfolio.vercel.app](https://rezha-portfolio.vercel.app) *(ganti dengan URL aktual kamu)*

## Deskripsi

Website ini dibuat sebagai portofolio personal yang diirancang dengan memperhatikan prinsip-prinsip UI/UX, mulai dari konsistensi visual, hierarki informasi, navigasi yang intuitif, serta responsivitas pada berbagai ukuran layar.

Target pengguna: Recruiter, dosen, rekan mahasiswa, atau siapa pun yang ingin mengenal lebih dalam terkait perjalanan dan karya yang dihasilkan oleh Rezha Anugrah Putra.

## Fitur

- Hero Section: Pengenalan singkat dengan foto, tagline, dan tombol navigasi cepat ke tiap bagian
- Tentang Saya: Empat kartu yang memuat latar belakang pendidikan, kemampuan, pengalaman proyek, dan tujuan karier
- Portofolio: Delapan proyek ditampilkan dalam card grid yang bersih: NUS7NTARA, NutriBuddy, MEETRA, PathEarn (Mobile), PathEarn (Web), WisNu, SolarPlan, dan TaskMate
- Pengalaman: Kartu pengalaman organisasi dan kepanitiaan dari SMA hingga kuliah
- Kontak: Footer dengan tautan langsung ke WhatsApp, Email, LinkedIn, dan Instagram
- Navigasi responsif: Hamburger menu untuk mobile dengan toggle buka/tutup
- Smooth scroll: Navigasi antar section yang halus dengan highlight aktif di navbar
- Scroll animation: Elemen muncul bertahap saat di-scroll ( menggunakan fade in berbasis Intersection Observer)

## Teknologi

Teknologi dan kegunaan

HTML5 = Digunakan untuk menyusun kerangka dan konten portofolio 
CSS3 = Digunakan untuk styling, animasi, dan responsivitas
[Tailwind CSS](https://tailwindcss.com/) (CDN) = Digunakan untuk menyusun kerangka kerja utility-first agar layout dan pewarnaan lebih efisien
[Font Awesome 6](https://fontawesome.com/) (CDN) = Digunakan untuk menampilkan ikon media sosial dan UI
[Google Fonts](https://fonts.google.com/) = Digunakan untuk mengatur tipografi dengan font Syne pada heading serta font Inter pada body
Vanilla JavaScript = Digunakan untuk membuat interaktivitas seperti menu, animasi, dan scroll behavior

## Struktur Proyek

portofolio-rezha/
├── index.html          # Halaman utama
├── style.css           # Stylesheet kustom
├── script.js           # JavaScript interaktivitas
├── CV/
│   └── CV Rezha.pdf    # CV yang bisa diunduh
└── Image/
    ├── LB 3 1.png
    ├── Profil awal.png
    ├── NUS7NTARA.png
    ├── NutriBuddy.png
    ├── MEETRA.png
    ├── PathEarn (Mobile).png
    ├── PathEarn (web).png
    ├── WisNu.png
    ├── Rectangle 42.png
    ├── TaskMate.png
    ├── Debat.png
    ├── MPK.png
    ├── RNK.png
    ├── Raion.png
    └── Ascend.png

## Prinsip UI/UX yang Diterapkan

Konsistensi desain = Dalam desain portofolio saat ini, digunakan satu palet warna (oranye + putih + krem), dua tipografi (Syne untuk heading, Inter untuk body), serta sebuah komponen kartu yang konsisten pada seluruh section.

Hierarki visual = Ukuran font berbasis `clamp()` untuk heading yang proporsional di semua layar. Section label berbentuk pill kecil yang membedakan judul dari konten.

Navigasi yang jelas = Sticky navbar dengan highlight aktif saat scroll. Pada mobile, navigasi navbar terdapat pada hamburger menu dengan ikon yang berubah menjadi ✕ saat terbuka.

Feedback interaksi = Setiap kartu dan tombol memiliki efek hover (`translateY`, perubahan shadow, perubahan warna) sebagai respons visual terhadap aksi pengguna.

Responsivitas = Layout menyesuaikan dari 1 kolom (mobile) hingga 2–5 kolom (desktop) menggunakan Tailwind responsive prefix (`sm:`, `md:`, `lg:`, `xl:`).

Aksesibilitas = Atribut `aria-label` dan `aria-expanded` pada navigasi mobile. Gambar dekoratif menggunakan `alt=""` dan `role="presentation"`. Animasi dinonaktifkan untuk pengguna dengan `prefers-reduced-motion`.

## Hosting

Website di-deploy menggunakan GitHub Pages dan dapat diakses secara publik selama periode Semester Genap 2025–2026.

## Kontak

| Platform | Tautan |
|---|---|
| WhatsApp | [+62 895-0804-4747](https://wa.me/6289508044747) |
| Email | [rezhaap2007@gmail.com](https://mail.google.com/mail/?view=cm&fs=1 to=rezhaap2007@gmail.com) |
| LinkedIn | [rezha-anugrah-putra](https://www.linkedin.com/in/rezha-anugrah-putra) |
| Instagram | [@rezha_ptra](https://www.instagram.com/rezha_ptra) |