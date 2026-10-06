# Portal Monitoring Klimatologi Indonesia — BMKG

Prototype website statis untuk kegiatan magang di bidang klimatologi.

## Isi project

- `index.html` — halaman utama.
- `css/style.css` — desain/tampilan website.
- `js/script.js` — filter, gallery, dan popup gambar.
- `assets/plots/map/olr/20261003` — 11 plot OLR Map.
- `assets/plots/map/olr/20261004` — 11 plot OLR Map.
- `assets/plots/map/pwat/20261003` — 11 plot PWAT Map.
- `assets/plots/map/pwat/20261004` — 11 plot PWAT Map.
- `assets/plots/hovmoller/olr/20261003` — 21 plot OLR Hovmöller.
- `assets/plots/hovmoller/olr/20261004` — 21 plot OLR Hovmöller.
- `assets/plots/hovmoller/pwat/20261003` — 7 plot PWAT Hovmöller.
- `assets/plots/hovmoller/pwat/20261004` — 7 plot PWAT Hovmöller.

Total: 100 gambar.

## Cara menjalankan

1. Ekstrak folder project.
2. Buka `index.html` dengan Google Chrome.
3. Coba menu Monitoring dan filter Map/Hovmöller, OLR/PWAT, serta tanggal.
4. Jika sudah sesuai, upload seluruh isi folder ke repository GitHub.
5. Aktifkan GitHub Pages dari Settings → Pages → Deploy from branch.

## Catatan kategorisasi

Kategori dibuat berdasarkan struktur file yang diberikan:
- `map` → Map / Peta
- `hov` → Hovmöller
- `olr.*` → parameter OLR
- `pwat.*` → parameter PWAT
- `20261003` dan `20261004` → tanggal data pada folder sumber

Nama file asli dipertahankan agar mudah dicocokkan kembali dengan data dari pembimbing.
