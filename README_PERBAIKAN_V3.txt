PERBAIKAN V3 - FIREBASE FIXX REALTIME CHECKED

Masalah yang ditemukan:
- Error login: gradingData is not defined.
- Penyebab: renderOfficerDatalist memakai variabel gradingData/tdData yang tidak ada, sehingga proses login Firebase sudah berhasil tetapi tampilan gagal render dan muncul sebagai gagal Firebase.

Perbaikan:
- renderOfficerDatalist sekarang memakai state.grading dan state.td.
- Cache busting index.html dinaikkan ke app.js?v=fixx-refresh-v3-checked-20260619.
- Firebase config tetap project baru grading-fixx.
- Login tetap Operator 123456 dan Staff 456789.
- Data tetap memakai Cloud Firestore.
- Tombol Refresh Data Firebase tetap tersedia.

Pastikan deploy ke Firebase Hosting dan buka dari grading-fixx.web.app atau grading-fixx.firebaseapp.com.
