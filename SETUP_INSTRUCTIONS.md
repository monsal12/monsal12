# Setup GitHub Profile README

Ikuti langkah-langkah di bawah untuk mengaktifkan Profile README di GitHub:

## Langkah 1: Buat Repository Khusus

1. Buka GitHub: https://github.com/new
2. Repository name: **monsal12** (harus sama dengan username!)
3. ✅ Centang "Public"
4. ✅ Centang "Add a README file"
5. Klik **Create repository**

## Langkah 2: Upload README.md

### Cara A: Via Web (Mudah)

1. Buka repository: https://github.com/monsal12/monsal12
2. Klik file `README.md`
3. Klik icon pensil (Edit) di kanan atas
4. Hapus semua isi, lalu copy-paste isi dari `README.md` ini
5. Scroll ke bawah, klik **Commit changes**

### Cara B: Via Git (Command Line)

```powershell
cd d:\gpt\monsal12
git init
git add README.md
git commit -m "Initial commit: Add profile README"
git branch -M main
git remote add origin https://github.com/monsal12/monsal12.git
git push -u origin main
```

## Langkah 3: Sesuaikan Info

Edit `README.md` dan ganti:

- ❌ `https://linkedin.com/in/monsal12` → ✅ Link LinkedIn kamu (atau hapus)
- ❌ `https://twitter.com/monsal12` → ✅ Link Twitter kamu (atau hapus)
- ❌ `your.email@example.com` → ✅ Email kamu
- ❌ `https://buymeacoffee.com/monsal12` → ✅ Link Buy Me A Coffee (atau hapus)

## Langkah 4: Cek Profil

Buka: https://github.com/monsal12

**README akan muncul otomatis di profil kamu!** 🎉

---

## Customization (Optional)

### Ganti Theme Stats

Ganti `theme=tokyonight` dengan:
- `dark`, `radical`, `merko`, `gruvbox`, `dracula`, `monokai`, `vue`, `onedark`, `cobalt`, `synthwave`, `highcontrast`, `nightowl`, `algolia`, `calm`, `github_dark`, dll.

### Tambah/Hapus Tech Icons

Edit bagian ini di README.md:
```
https://skillicons.dev/icons?i=js,ts,python,java
```

Hapus atau tambah icons sesuai skill kamu. Lihat daftar lengkap: https://skillicons.dev

---

**Selamat! Profile GitHub kamu sekarang keren! 🚀**
