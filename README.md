# Buka-Scribd

Panduan sederhana untuk menyusun URL *embed* dokumen Scribd menggunakan ID dokumen.

## Tentang proyek

**Buka-Scribd** menyediakan contoh format tautan *embed* Scribd. Panduan ini menjelaskan bagian URL yang dapat disesuaikan berdasarkan ID dokumen.

> **Catatan:** Tautan *embed* tidak menjamin akses ke semua dokumen. Ketersediaan konten tetap bergantung pada pengaturan akses, kebijakan, dan mekanisme autentikasi Scribd. Panduan ini bukan cara untuk melewati pembatasan akses atau hak cipta.

## Format URL

```text
https://www.scribd.com/embeds/xxxxxxxxx/content?start_page=1&view_mode=scroll&access_key=ACCESS_KEY
```

bisa coba gunakan ini, tinggal ganti xxxxx dengan format ID pada dokumen yang sedang anda kunjungi dan terkunci aksesnya
https://www.scribd.com/embeds/xxxxxxxxx/content?start_page=1&view_mode=scroll&access_key=key-fFexxf7r1bzEfWu3HKwfI

## Cara penggunaan

1. Buka halaman dokumen Scribd yang ingin Anda lihat dan pastikan Anda memiliki hak akses.
2. Temukan ID dokumen pada URL Scribd.
3. Ganti `xxxxxxxxx` pada format di atas dengan ID dokumen tersebut.
4. Parameter `access_key` pada contoh adalah **placeholder**, bukan kunci universal. Gunakan hanya nilai yang sah dan disediakan untuk dokumen terkait jika memang diperlukan.
5. Buka tautan hasilnya di peramban. Jika konten tidak tersedia, gunakan mekanisme akses resmi Scribd.

### Penjelasan parameter

| Bagian | Keterangan |
| --- | --- |
| `xxxxxxxxx` | ID dokumen Scribd yang ingin ditampilkan. |
| `start_page=1` | Memulai tampilan dari halaman pertama. |
| `view_mode=scroll` | Meminta mode tampilan gulir. |
| `access_key=ACCESS_KEY` | Placeholder untuk kunci akses yang sah jika dibutuhkan. |

## Batasan dan tanggung jawab

- Contoh URL ini tidak menjamin bahwa parameter masih didukung oleh Scribd.
- Jangan menggunakan panduan ini untuk mengakses atau menyebarkan konten tanpa izin.
- Hak cipta dokumen tetap dimiliki oleh masing-masing pemegang hak.
- Proyek ini tidak berafiliasi dengan atau didukung oleh Scribd.

## Kredit

- **Nama proyek:** Buka-Scribd
- **Dokumentasi:** Disusun berdasarkan panduan awal proyek Buka-Scribd.
- **Pengembang/pemilik proyek:** Belum dicantumkan. Silakan tambahkan nama atau akun GitHub pemilik yang sebenarnya.
- **Scribd:** Merek dan layanan milik pemegang hak masing-masing; penyebutan hanya untuk menjelaskan kompatibilitas tautan.

## Lisensi

Dokumentasi dan kode orisinal proyek ini dapat didistribusikan dengan **MIT License**, apabila Anda adalah pemegang hak yang berwenang untuk melisensikannya. Lihat [`LICENSE`](LICENSE).

Lisensi ini **tidak** mencakup dokumen pihak ketiga yang ditampilkan melalui Scribd.
