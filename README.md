# rxy-effects
Katalog efek Render Rxy

Katalog publik untuk pustaka Efek Online pada Render Rxy 1.42.

## Hubungkan ke aplikasi

1. Buka **Image → Setting → Penyimpanan**.
2. Isi **Alamat katalog efek GitHub** dengan:

```text
https://raw.githubusercontent.com/wegadgetdigital-cyber/rxy-effects/main/catalog.json
```

3. Klik **Simpan pengaturan penyimpanan**.
4. Buka **Efek → Efek Online → Perbarui katalog**.
5. Klik tanda **+** pada **Partikel Lembut**. Setelah unduh selesai, klik **Gunakan**.

Efek terpasang tetap di bagian Online dan dapat digunakan tanpa internet selama
file lokalnya tersedia. Katalog terakhir tetap dapat ditampilkan saat offline.

## Koleksi awal

| Efek | Jenis | Versi |
|---|---|---|
| Partikel Lembut | Preset parameter partikel | 1 |

Preset ini mengaktifkan Debu Cahaya dengan jumlah 12 dan opacity 30. Ia mengubah
parameter yang disertakan, bukan mengatur ulang seluruh efek editor. Tidak ada
video, model AI, atau media pihak lain dalam paket contoh ini. Pratinjau berupa
ilustrasi kartu, bukan rekaman hasil render.

## Susunan berkas

- `catalog.json`: daftar efek, versi, alamat paket/pratinjau, ukuran, SHA256.
- `packages/`: paket contoh kecil.
- `previews/`: gambar kartu.

Paket media yang besar dapat ditempatkan di GitHub Releases, lalu alamat asetnya
dicatat di katalog. Render Rxy 1.42 saat ini membatasi satu paket hingga 256 MB.
Jangan mengganti isi paket dengan ID/versi yang sudah diterbitkan; gunakan versi
baru agar proyek dan antrean lama tetap dapat memakai resep sebelumnya.

Format katalog: `rxy-effects-catalog/1`. Format paket: `rxy-effect/1`.
Jenis yang didukung versi ini: `preset`, `rain`, `fire`, dan `particle`.
Jangan unggah data belajar pribadi, hasil render, password, atau token ke sini.

## Batas kemampuan

Repository ini hanya katalog efek; tidak mengaktifkan AI analisis gambar/audio
atau pembelajaran model. Data pribadi pengguna tetap disimpan di komputer.

