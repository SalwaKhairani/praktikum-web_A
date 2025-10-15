TAILWIND
1. Jelaskan keputusan grid-cols/gap di tiap breakpoint — kenapa begitu?
 Grid-cols/gap di tiap breakpoint
Dipilih sesuai ukuran layar: di HP pakai 1–2 kolom dengan gap kecil, di tablet 3–4 kolom, di PC bisa lebih besar dengan gap lebar. Tujuannya biar tampilan tetap rapi dan nyaman dilihat di semua perangkat.

2. Bagaimana kamu memanfaatkan utility responsive Tailwind untuk memecahkan masalah layout yang muncul di mobile?
Utility responsive Tailwind di mobile
Gunakan prefix seperti sm:, md:, lg: untuk menyesuaikan layout otomatis. Contoh: grid-cols-1 sm:grid-cols-2 md:grid-cols-3 biar grid berubah sesuai lebar layar tanpa bikin CSS tambahan.

3. Jelaskan trade-off antara memakai banyak utility classes vs membuat component CSS tersendiri!
Trade-off utility classes vs component CSS
Utility classes lebih cepat dan praktis, tapi bikin HTML panjang. Component CSS lebih rapi dan reusable, tapi butuh waktu ekstra untuk dibuat.

penjelasan:
Kode HTML di atas adalah sebuah tampilan halaman profil Instagram versi sederhana yang dibuat menggunakan Tailwind CSS untuk styling modern dan responsif. Struktur halaman dimulai dengan header berisi foto profil berbentuk lingkaran, username, tombol follow yang responsif di berbagai ukuran layar, bio singkat, serta informasi jumlah postingan, followers, dan following yang tersusun rapi menggunakan flexbox. Di bawahnya terdapat section bio tambahan yang memuat kutipan panjang bergaya estetis dengan teks abu-abu agar terlihat lembut. Bagian utama menampilkan feed foto dalam bentuk grid responsif dengan 12 gambar, di mana jumlah kolom menyesuaikan ukuran layar (1 kolom di HP, 2 di tablet kecil, 3 di tablet besar, dan 4 di desktop), serta setiap gambar dibuat seragam dengan tinggi tetap, penuh, dan sedikit rounded agar mirip dengan tampilan Instagram asli. Terakhir, halaman ditutup dengan footer sederhana berisi teks hak cipta dan keterangan bahwa halaman dibuat menggunakan Tailwind CSS. Desain ini ringan, clean, dan tetap terlihat mirip Instagram dengan memanfaatkan utilitas kelas Tailwind sepenuhnya tanpa file CSS tambahan.