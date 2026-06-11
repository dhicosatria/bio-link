# Bio Link

Bio Link pribadi yang ringan, responsif, dan siap deploy ke GitHub Pages.

## Kustomisasi

Edit `index.html` untuk mengganti:

- Nama, bio, dan inisial avatar
- URL GitHub, LinkedIn, portfolio, dan email
- Judul serta deskripsi setiap tautan

Warna utama dapat diganti melalui variabel `--accent` di `styles.css`.

## Jalankan secara lokal

Buka `index.html` langsung di browser, atau jalankan server lokal:

```bash
python3 -m http.server 8000
```

Lalu buka `http://localhost:8000`.

## Deploy Bio Link ke GitHub Pages

1. Buat repository baru di GitHub.
2. Push isi folder ini ke branch `main`.
3. Buka **Settings > Pages** pada repository.
4. Pada **Build and deployment > Source**, pilih **GitHub Actions**.

Setiap push ke `main` akan otomatis men-deploy versi terbaru.

Alamat publik yang direkomendasikan:

`https://USERNAME.github.io/bio-link/`
