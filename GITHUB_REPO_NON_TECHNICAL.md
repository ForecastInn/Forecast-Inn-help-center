markdown
# Cara Buat GitHub Repository (Tanpa Coding)

**Estimasi waktu:** 10-15 menit
**Skill yang dibutuhkan:** Bisa buka browser, copy-paste

---

## Langkah 1: Login ke GitHub

1. Buka browser (Chrome, Firefox, Edge, dll)
2. Kunjungi: **https://github.com**
3. Klik tombol **"Sign in"** di pojok kanan atas
4. Masukkan email & password GitHub kamu
5. Klik **"Sign in"**

---

## Langkah 2: Buat Repository Baru

### 2.1. Klik tombol "New"

**Lokasi:**
- Setelah login, lihat pojok kanan atas
- Ada ikon **"+"** (tambah) di dekat foto profil
- Klik → pilih **"New repository"**

### 2.2. Isi Form Repository

**Form yang perlu diisi:**

| Field | Isi Dengan | Catatan |
|-------|-----------|---------|
| **Repository name*** | `docs` | Nama folder untuk dokumentasi |
| **Description** | `ForecastInn Help Center - Customer Documentation` | Opsional, tapi recommended |
| **Public/Private** | Pilih **Public** | Kalau mau bisa diakses siapa saja |

**Yang TIDAK perlu di-checklist:**
- ❌ Add a README file
- ❌ Add .gitignore
- ❌ Choose a license

**Kenapa tidak usah checklist?**
Karena file-file kita sudah siap di komputer, jadi tidak perlu buat file baru.

### 2.3. Klik "Create repository"

- Tombol hijau di bawah form
- Klik dan tunggu beberapa detik

---

## Langkah 3: Siapkan Folder di Komputer

### 3.1. Buka folder `docs`

**Lokasi:**

C:\Users\donni\.openclaw\workspace\docs


**Cara buka:**
1. Tekan **Windows + R** di keyboard
2. Ketik: `C:\Users\donni\.openclaw\workspace\docs`
3. Tekan **Enter**
4. Folder akan terbuka

### 3.2. Pastikan sudah ada file-file ini:

**Wajib ada:**
- ✅ `index.html`
- ✅ `README.md`
- ✅ `QUICK_START.md`
- ✅ `CUSTOMER_GUIDE.md`
- ✅ `TROUBLESHOOTING.md`
- ✅ `_config.yml`
- ✅ `.gitignore`
- ✅ Folder `screenshots/` (berisi 8 gambar)

**Kalau belum ada:**
- Berarti ada yang salah di langkah sebelumnya
- Chat ulang dengan AI assistant

---

## Langkah 4: Upload ke GitHub (Cara Mudah)

### 4.1. Buka GitHub repository yang baru dibuat

**URL format:**

https://github.com/<USERNAME-GITHUB-KAMU>/docs


**Contoh:**

https://github.com/forecastinn/docs


### 4.2. Klik "uploading an existing file"

**Lokasi:**
- Di halaman repository, cari teks kecil:
  > *"or upload an existing file"*
- Klik link **"uploading an existing file"** (warna biru)

### 4.3. Drag & Drop file-file

**Cara upload (pilih salah satu):**

**Cara 1: Drag & Drop**
1. Buka folder `docs` di komputer (Langkah 3.1)
2. Pilih SEMUA file di folder itu (Ctrl + A)
3. Drag (klik tahan & geser) ke area upload di browser
4. Lepaskan mouse

**Cara 2: Choose your files**
1. Klik tombol **"choose your files"**
2. Pilih file pertama
3. Tekan dan tahan **Ctrl**
4. Klik file-file lainnya satu per satu
5. Klik **"Open"**

### 4.4. Tunggu proses upload

- Progress bar akan muncul
- Tunggu sampai semua file terupload (100%)
- Waktu: 1-5 menit tergantung internet

### 4.5. Beri nama commit

**Di bagian bawah halaman:**
- Tulis di kotak "Commit changes":
  
  Initial commit - ForecastInn Help Center v1.0
- Pastikan pilihan: **"Commit directly to the master branch"**

### 4.6. Klik "Commit changes"

- Tombol hijau di bawah
- Tunggu sampai redirect ke halaman repository

---

## Langkah 5: Verifikasi File Terupload

**Cek di GitHub repository:**

**Harusnya ada file-file ini:**
- ✅ `index.html`
- ✅ `README.md`
- ✅ `QUICK_START.md`
- ✅ `CUSTOMER_GUIDE.md`
- ✅ `TROUBLESHOOTING.md`
- ✅ `_config.yml`
- ✅ `.gitignore`
- ✅ Folder `screenshots/`

**Kalau belum ada semua:**
- Ulangi Langkah 4 untuk file yang missing
- Atau upload ulang semua file

---

## Langkah 6: Aktifkan GitHub Pages

### 6.1. Buka Settings

**Lokasi:**
- Di halaman repository, klik tab **"Settings"** (di atas)
- Scroll ke bawah sampai menemukan **"Pages"** di menu kiri

### 6.2. Konfigurasi GitHub Pages

**Di halaman "Pages":**

| Setting | Pilih | Keterangan |
|---------|-------|-----------|
| **Source** | `Deploy from a branch` | Ambil dari branch repository |
| **Branch** | `master` (atau `main`) | Branch default |
| **Folder** | `/ (root)` | Folder utama |

**Setelah diisi:**
- Klik tombol **"Save"** (hijau)
- Tunggu beberapa detik

### 6.3. Tunggu proses deploy

**Status akan muncul:**
- ⏳ "Your site is being deployed"
- Tunggu 1-5 menit

**Setelah selesai:**
- ✅ Status berubah jadi: **"Your site is live"**
- Link website akan muncul, misal:
  
  https://forecastinn.github.io/docs/
  

---

## Langkah 7: Test Website

### 7.1. Buka link website

**Klik link di bagian atas halaman Pages:**

https://forecastinn.github.io/docs/


### 7.2. Apa yang harus muncul:

**Homepage harus menampilkan:**
- ✅ ForecastInn logo
- ✅ Judul: "ForecastInn Help Center"
- ✅ Search box
- ✅ Cards: Quick Start, Customer Guide, Troubleshooting
- ✅ FAQ section
- ✅ Contact info (WhatsApp, Email)

**Kalau tidak muncul:**
- Refresh browser (F5)
- Tunggu 1-2 menit lagi (masih deploying)
- Cek apakah file `index.html` sudah terupload

---

## Tambahan: Custom Domain (Opsional)

**Kalau mau pakai domain sendiri:**
- Misal: `help.forecastinn.com` (bukan `.github.io`)

### 8.1. Buat CNAME file

**Di komputer, buka folder `docs`:**
1. Buka Notepad
2. Ketik:
   
   help.forecastinn.com
3. Save sebagai: `CNAME` (tanpa .txt)
   - File type: All Files
   - Encoding: UTF-8

### 8.2. Upload CNAME ke GitHub

- Upload file `CNAME` ke repository (sama kayak Langkah 4)
- Commit: "Add custom domain"

### 8.3. Setup DNS

**Buka dashboard DNS provider (Cloudflare, Namecheap, dll):**

| Type | Name | Target |
|------|------|--------|
| CNAME | help | forecastinn.github.io |

**Simpan dan tunggu:**
- DNS propagation: 5-60 menit
- Setelah itu, `help.forecastinn.com` akan aktif

---

## Checklist Final ✅

**Sebelum selesai, pastikan:**

- [ ] GitHub repository sudah dibuat
- [ ] Semua file berhasil diupload
- [ ] GitHub Pages sudah diaktifkan
- [ ] Website bisa diakses via browser
- [ ] Tampilan website benar (logo, menu, content)
- [ ] Links berfungsi (Quick Start, Customer Guide, dll)
- [ ] Screenshots muncul dengan benar

---

## Troubleshooting

### Problem: "Page not found"

**Solution:**
1. Cek apakah `index.html` sudah terupload
2. Tunggu 5 menit lagi (masih deploying)
3. Refresh browser

### Problem: "Screenshots tidak muncul"

**Solution:**
1. Cek folder `screenshots/` sudah terupload
2. Pastikan nama file sama persis (case-sensitive)
3. Cek path di `index.html`

### Problem: "GitHub Pages stuck in deploying"

**Solution:**
1. Tunggu 10 menit
2. Cek tab "Actions" di GitHub (lihat error log)
3. Pastikan tidak ada file yang corrupt

---

## Butuh Bantuan?

**Kalau stuck di langkah mana pun:**

1. **Screenshot error** → Kirim ke team tech
2. **Chat AI assistant** → Jelaskan langkah mana yang bermasalah
3. **Cek GitHub Status** → https://www.githubstatus.com (kalau GitHub sedang down)

---

**Selamat!** 🎉

Website ForecastInn Help Center sudah online dan bisa diakses customer!

**Next Steps:**
- Share link ke customer
- Update content kalau ada fitur baru
- Tambah FAQ kalau ada pertanyaan recurring