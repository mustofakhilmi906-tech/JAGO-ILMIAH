# JagoIlmiah 🎓

Platform Perpustakaan Digital Akademik untuk Mahasiswa Indonesia.

**Stack:** Next.js 14 · TypeScript · Tailwind CSS · Prisma ORM · SQLite · NextAuth.js

---

## ⚡ Cara Menjalankan

```bash
# 1. Install dependencies
npm install

# 2. Pastikan .env.local sudah ada (sudah disertakan)
# DATABASE_URL="file:./dev.db"
# NEXTAUTH_SECRET="jagoilmiah-secret-key-change-in-production"
# NEXTAUTH_URL="http://localhost:3000"

# 3. Setup database
npx prisma db push

# 4. Seed data contoh
npm run db:seed

# 5. Jalankan server
npm run dev
```

Buka **http://localhost:3000**

---

## 🔑 Akun Demo

| Role        | Email                         | Password  |
|-------------|-------------------------------|-----------|
| Mahasiswa   | siti@jagoilmiah.id            | mhs123    |
| Mahasiswa   | budi@jagoilmiah.id            | mhs123    |
| Pustakawan  | ibu.ratna@jagoilmiah.id       | pakar123  |
| Pustakawan  | pak.hendra@jagoilmiah.id      | pakar123  |
| Pakar/Dosen | prof.anisa@jagoilmiah.id      | pakar123  |
| Admin       | admin@jagoilmiah.id           | admin123  |

---

## 📁 Fitur Utama

### 1. 📚 Repositori Digital (`/repository`)
- Katalog e-book, jurnal, paper, video tutorial, tesis
- Filter berdasarkan tipe, bidang ilmu, dan bahasa
- Open access & premium content
- Detail halaman dengan abstrak lengkap

### 2. 📝 Format Sitasi Otomatis (`/repository/[id]`)
- Generate sitasi APA, MLA, Chicago, Vancouver, IEEE
- Salin ke clipboard satu klik
- Simpan ke koleksi sitasi pribadi

### 3. 💬 Layanan Referensi Virtual (`/konsultasi`)
- Pilih pustakawan atau pakar bidang studi
- Ajukan pertanyaan via chat, video, atau email
- Riwayat konsultasi dengan status real-time

### 4. 🎓 Pelatihan Literasi Digital (`/pelatihan`)
- Webinar, workshop, modul self-paced
- Topik: Scopus/WoS, Mendeley, Zotero, Academic Writing, Systematic Review
- Daftar gratis, tracking status keikutsertaan

### 5. 🔬 Pendampingan Riset (`/pendampingan`)
- 6 tahap: Pemilihan Topik → Proposal → Data → Penulisan → Revisi → Publikasi
- Milestone tracker per sesi
- Pilih mentor pakar atau pustakawan embedded

### 6. 👤 Profil & Manajemen Referensi (`/profil`)
- Koleksi referensi tersimpan
- Daftar sitasi dengan format berbeda
- Statistik aktivitas akademik

---

## 🗺️ Halaman

| URL                  | Deskripsi                         |
|----------------------|-----------------------------------|
| `/`                  | Landing page                      |
| `/repository`        | Katalog repositori digital        |
| `/repository/[id]`   | Detail + sitasi otomatis          |
| `/konsultasi`        | Layanan referensi virtual         |
| `/pelatihan`         | Program pelatihan literasi digital|
| `/pendampingan`      | Pendampingan riset jangka panjang |
| `/dashboard`         | Dashboard pengguna                |
| `/profil`            | Profil & koleksi referensi        |
| `/login`             | Halaman masuk                     |
| `/register`          | Halaman daftar                    |

---

## 🎨 Design System

- **Tema:** Academic editorial — parchment background, teal & amber accents
- **Font display:** Lora (serif elegan)
- **Font body:** Source Sans 3
- **Warna:** Ink `#1a1a2e` · Teal `#0d7377` · Amber `#c8923a` · Parchment `#faf8f3`
