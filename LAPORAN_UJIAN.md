# Laporan UTS Web Software Tools

**Nama:**
**Nomor Induk Mahasiswa:**
**Kelas:**
**Tanggal:**

## A. Bukti pemeriksaan masalah
| Masalah | Alat yang digunakan | Bukti pemeriksaan | Perkiraan penyebab | Perbaikan | Hasil setelah perbaikan |
|---|---|---|---|---|---|
| Produk | daftar produk tidak muncul|console |app.js:56
 Gagal mengambil daftar produk: Error: Permintaan gagal dengan status 404
    at loadProducts (app.js:49:29) |karena penulisan path yang salah  | path yang sebeumnya /api/barang menjadi /api/products setelah diganti daftar produknya jadi muncul|
| Tombol keranjang |tombol button tidak beraksi | console|document.querySelectorAll(".add-to-cart").length |.add-to-cart di ubah menjadi .add-button | button jadi bereaksi saat di klik |
| Total belanja |total harga yang belum sesuai | console sources | karena perhitungan sebelumnya hanya menjumlahkan harga satu barang per baris dan mengabaikan jumlahnya. | yang dimana code sebelumnya itu total+ite.price,0| code setelah perbaikan total + item.price * item.quantity, 0, jadinya perhitungan totalharga sudah sesuai|

## B. Hasil pengujian
- Jumlah pengujian sebelum perbaikan:
- Jumlah pengujian berhasil setelah perbaikan:
- Catatan perubahan pada fungsi yang diperiksa:

## C. Kualitas kode
- Temuan sebelum perbaikan:
- Perbaikan yang dilakukan:
- Hasil pemeriksaan ulang:

## D. Git
- Branch (jika membuat):
- Ringkasan commit:
- Hasil pemeriksaan `git status`:

## E. Pemakaian kecerdasan buatan (jika digunakan)
- Nama alat:
- Pertanyaan/instruksi yang diberikan:
- Bagian jawaban yang diterapkan:
- Cara memeriksa apakah saran tersebut benar:

## F. Refleksi singkat
- Satu pelajaran paling penting dari ujian ini:
