REVISI DATA AMAN + PRINT FULL

1. Data transaksi baru tidak lagi memakai nomor dari jumlah data lokal.
2. Kode transaksi dibuat unik memakai tanggal + jam + milidetik + kode acak.
3. Simpan transaksi baru memakai proteksi create/no-overwrite ke Firestore.
4. Jika ID sudah ada, sistem otomatis membuat ID baru, sehingga data lama tidak tertimpa.
5. Jika Firebase gagal, data baru tidak dianggap tersimpan agar tidak menimbulkan data lokal yang bisa menimpa data lama.
6. Setelah data berhasil masuk Firestore, realtime akan memperbarui tampilan.
7. Filter tanggal dibuat otomatis: saat tanggal awal/akhir dipilih, preset berubah ke Custom dan tampilan dirender ulang.
8. Data hasil filter disortir ulang otomatis dari yang terbaru berdasarkan updatedAt, createdAt, tanggal, jam, lalu ID.
9. Print/JPG data masing-masing dibuat lebih penuh, teks lebih besar, dan lebih jelas.
10. Template tetap A5 landscape di halaman A4 portrait, dengan garis potong tanpa tulisan.
11. Firebase config, project, dan collection/path tidak diubah.
12. Login tetap Staff 789 dan Operator 123.
