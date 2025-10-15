# Penjelasan 4.3:

Pada kode awal (seperti di gambar pertama), baris 5 berisi:
<title>Latihan 2</title>

Setelah diubah sesuai perintah, baris itu menjadi:
<link rel="stylesheet" type="text/css" href="#">

## Artinya kita menambahkan link ke file CSS eksternal.
rel="stylesheet" → menandakan ini adalah file stylesheet (CSS).
type="text/css" → mendefinisikan jenis file (CSS).
href="#" → menunjukkan lokasi file CSS yang ingin dipakai.
Masalahnya, tanda # bukan file CSS yang valid, hanya placeholder/tanda kosong. Jadi browser tidak menemukan file CSS eksternal untuk dipanggil.

## Hasil di Browser:
Semua style yang ada di dalam atribut inline (style="..." )
tetap akan muncul, karena itu tidak bergantung pada file CSS eksternal.
Namun style dari file eksternal tidak berpengaruh sama sekali, sebab href="#" tidak menunjuk ke file apapun.
Akhirnya tampilan tetap sama seperti hanya menggunakan inline CSS, tanpa tambahan aturan lain dari file eksternal.

## Jadi Kesimpulannya:
1. Perubahan kode membuat browser mencari file CSS eksternal, tetapi tidak menemukannya karena href="#" tidak valid.
2. Akibatnya, tidak ada tambahan styling dari luar, dan tampilan hanya bergantung pada inline CSS yang ada.
3. Jadi hasil yang terlihat di browser tidak berbeda dengan sebelum baris itu diubah.