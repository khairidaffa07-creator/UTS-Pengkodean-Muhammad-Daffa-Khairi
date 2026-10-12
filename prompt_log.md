# Log Prompt AI — Purwarupa Voucher Entri Transaksi Kas Keluar

**Proyek:** Purwarupa aplikasi web Voucher Entri Transaksi Kas Keluar  
**AI tool:** Gemini Canvas  
**Tujuan:** Membuat purwarupa formulir entri jurnal dan rancangan integrasi Supabase/PostgreSQL.

## Prompt yang terdokumentasi

> Buat purwarupa aplikasi web Voucher Entri Transaksi Kas Keluar untuk sistem akuntansi perusahaan menggunakan HTML, Tailwind CSS, dan JavaScript.
>
> Persyaratan:
> 1. Formulir berisi tanggal transaksi, nomor voucher, deskripsi, dan tabel jurnal dinamis.
> 2. Tabel jurnal memiliki kolom akun, debit, dan kredit serta fitur tambah dan hapus baris.
> 3. Hitung total debit, total kredit, dan selisih secara otomatis ketika pengguna mengubah nominal.
> 4. Tampilkan indikator Balanced jika total debit sama dengan total kredit dan selisihnya nol. Jika tidak seimbang, tampilkan Unbalanced.
> 5. Tombol Submit hanya boleh aktif jika terdapat minimal dua baris jurnal yang valid, setiap baris hanya memiliki salah satu nilai debit atau kredit yang positif, seluruh akun valid, dan total debit sama dengan total kredit.
> 6. Gunakan validasi frontend untuk pengalaman pengguna, tetapi lakukan validasi ulang di backend/database sebelum transaksi disimpan atau diposting.
> 7. Rancang integrasi Supabase PostgreSQL dengan tabel chart_of_accounts, journal_headers, journal_lines, dan audit_logs.
> 8. Catat created_by, created_at, aksi pengguna, identitas transaksi, serta hash_checksum untuk pemeriksaan integritas.
> 9. Jurnal yang telah berstatus POSTED tidak boleh diubah atau dihapus; koreksi harus dilakukan melalui reversing entry.
> 10. Buat tampilan responsif, pesan error yang jelas, dan dokumentasikan cara konfigurasi Supabase.
>
> Sertakan kode lengkap, struktur file, skema SQL, alur validasi, serta skenario pengujian untuk jurnal seimbang, jurnal tidak seimbang, nominal negatif, dan percobaan mengubah jurnal yang sudah diposting. Jangan menyatakan aplikasi telah terhubung atau diuji jika pengujian tersebut belum benar-benar dilakukan.

## Catatan transparansi

- Prompt di atas disalin dari dokumentasi jawaban UTS yang disiapkan.
- Jika selama pengerjaan benar-benar digunakan prompt tambahan atau revisi prompt, tambahkan prompt tersebut di bawah ini sesuai riwayat penggunaan yang sebenarnya.
- Jangan mengklaim seluruh skenario pengujian berhasil sebelum pengujian benar-benar dijalankan.
- File ini merupakan dokumentasi prompt, bukan bukti bahwa integrasi Supabase atau seluruh kontrol keamanan sudah berhasil diuji.
