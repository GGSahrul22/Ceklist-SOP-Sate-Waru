# Form Pemeriksaan Operasional Restoran

Website statis HTML/CSS/JavaScript dengan 8 posisi dan 80 checklist SOP.

## Fitur
- Checklist SOP untuk Kasir, Waiter/Runner, Head Floor, Chef, Helper, Steward, Bakaran Sate, dan Bar.
- Status OK / Tidak sesuai / N/A.
- Kolom temuan dan tindakan perbaikan.
- Simpan riwayat pada browser lokal.
- Ekspor Excel (.xlsx), CSV, serta cetak / simpan PDF.
- Responsif untuk desktop dan ponsel.

## Upload ke GitHub Pages
1. Buat repository baru di GitHub.
2. Unggah `index.html` (README opsional) ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu deployment selesai; GitHub akan menampilkan URL publik website Anda.

## Catatan
- Tidak membutuhkan backend atau API key.
- Riwayat disimpan di localStorage browser/perangkat yang digunakan, bukan dibagikan antarperangkat.
- Ekspor XLSX memerlukan koneksi internet untuk memuat pustaka SheetJS dari CDN. Ekspor CSV dan cetak PDF memakai fungsi browser.
