
# TUGAS JS (DOM) SKILVUL

Tugas ini adalah tugas yang diberikan oleh kak 
Arief Faltah yang terdiri dari 8 section untuk coba dikerjakan sebagai latihan. 

# Section 2 (getElementById())

Contoh 1: Mengubah isi teks dari elemen HTML
- Dalam contoh 1, getElementById() digunakan untuk mendapatkan elemen dengan id "teks-utama". Kemudian, nilai dari elemen tersebut diubah menggunakan properti innerHTML sehingga teks pada halaman web berubah.

Contoh 2: Menambahkan event listener pada elemen HTML
- Dalam contoh 2, getElementById() digunakan untuk mendapatkan elemen dengan id "tombol". Kemudian, event listener ditambahkan pada elemen tersebut sehingga ketika tombol di-klik, sebuah pesan pop-up akan muncul.

Contoh 3: Mengubah gaya CSS dari elemen HTML
- Dalam contoh 3, getElementById() digunakan untuk mendapatkan elemen dengan id "kotak". Kemudian, gaya CSS dari elemen tersebut diubah menggunakan properti style. Dalam kasus ini, warna latar belakang diubah menjadi biru, dan ukuran lebar dan tinggi elemen diatur menjadi 100 piksel.

# Section 3 (parentElement)

Contoh 1: Menambahkan event listener pada elemen induk
- Dalam contoh 1, parentElement digunakan untuk mendapatkan elemen induk dari elemen button yang dipilih menggunakan querySelector. Kemudian, event listener ditambahkan pada elemen induk sehingga ketika area di sekitar tombol diklik, sebuah pesan pop-up akan muncul.

Contoh 2: Mengubah gaya CSS dari elemen induk
- Dalam contoh 2, parentElement digunakan untuk mendapatkan elemen induk dari elemen span yang dipilih menggunakan querySelector. Kemudian, gaya CSS dari elemen induk tersebut diubah menggunakan properti style. Dalam kasus ini, warna latar belakang diubah menjadi biru, dan ukuran lebar dan tinggi elemen diatur menjadi 100 piksel.

Contoh 3: Menghapus elemen HTML dari dokumen
- Dalam contoh 3, parentElement digunakan untuk mendapatkan elemen induk dari elemen li yang dipilih menggunakan querySelectorAll. Kemudian, elemen li yang dipilih dihapus dari dokumen menggunakan metode removeChild pada elemen induknya. Dalam kasus ini, elemen kedua dari daftar akan dihapus

# Section 4 (createElement())

Contoh 1: Membuat elemen baru dan menambahkannya ke dalam dokumen
- Dalam contoh 1, createElement() digunakan untuk membuat elemen p baru. Kemudian, teks konten dari elemen tersebut diatur menggunakan properti textContent. Akhirnya, elemen p yang baru dibuat ditambahkan ke dalam elemen dengan id kontainer menggunakan appendChild(). Dengan demikian, sebuah paragraf baru akan ditampilkan pada halaman web.

Contoh 2: Menambahkan elemen baru pada suatu elemen HTML yang sudah ada
- Dalam contoh 2, createElement() digunakan untuk membuat elemen li baru. Kemudian, teks konten dari elemen tersebut diatur menggunakan properti textContent. Akhirnya, elemen li yang baru dibuat ditambahkan ke dalam elemen ul yang sudah ada pada elemen dengan kelas daftar menggunakan appendChild(). Dengan demikian, sebuah item baru akan ditambahkan pada daftar yang sudah ada.

Contoh 3: Menambahkan atribut pada elemen HTML yang baru dibuat
- Dalam contoh 3, createElement() digunakan untuk membuat elemen img baru. Kemudian, atribut src dan alt dari elemen tersebut diatur menggunakan properti src dan alt. Akhirnya, elemen img yang baru dibuat ditambahkan ke dalam elemen dengan id gambar menggunakan appendChild(). Dengan demikian, sebuah gambar baru akan ditampilkan pada halaman web.

# Section 5 (setAttribute())

Contoh 1: Menambahkan atribut pada elemen HTML
- Dalam contoh 1, setAttribute() digunakan untuk menambahkan atribut class pada elemen button. Nilai atribut yang ditambahkan adalah tombol-utama. Dengan demikian, elemen button akan memiliki kelas CSS baru yang dapat digunakan untuk menentukan tampilan tombol tersebut.

Contoh 2: Mengubah nilai atribut yang sudah ada
- Dalam contoh 2, setAttribute() digunakan untuk mengubah nilai atribut src pada elemen img. Nilai atribut yang baru adalah https://www.example.com/gambar2.jpg. Dengan demikian, gambar yang ditampilkan pada halaman web akan berubah dari gambar1.jpg menjadi gambar2.jpg.

# Section 6 (getComputedStyle())

Contoh 1: Mendapatkan nilai properti CSS
- Dalam contoh 1, getComputedStyle() digunakan untuk mendapatkan nilai dari properti gaya CSS pada elemen div dengan id kotak. Properti yang dipilih adalah background-color, width, dan height. Kemudian, nilai properti tersebut ditampilkan pada konsol dengan menggunakan metode console.log(). Dengan demikian, kita dapat mengetahui nilai dari properti CSS pada suatu elemen dengan lebih akurat.

Contoh 2: Menggunakan nilai properti CSS yang didapatkan
- Dalam contoh 2, getComputedStyle() digunakan untuk mendapatkan nilai dari properti gaya CSS pada elemen div dengan id kotak. Kemudian, nilai properti background-color, width, dan height digunakan untuk mengubah properti CSS pada elemen yang sama menggunakan properti style. Properti background-color diambil dari nilai yang didapatkan menggunakan getComputedStyle(), sedangkan properti width dan height dinaikkan sebesar 50 piksel dari nilai yang didapatkan. Dengan demikian, elemen div dengan id kotak akan memiliki warna latar belakang biru, lebar 250 piksel, dan tinggi 150 piksel.

# Section 7 (JavaScript events)

Contoh 1: Menggunakan event click
- Dalam contoh 1, event click digunakan untuk memberikan respons saat tombol dengan id tombol diklik. Ketika tombol tersebut diklik, fungsi yang ditentukan akan dijalankan, yaitu menampilkan kotak pesan yang berisi teks "Tombol telah diklik". Dengan demikian, pengguna akan mendapatkan umpan balik bahwa tombol tersebut berhasil diklik.

Contoh 2: Menggunakan event scroll
- Dalam contoh 2, event scroll digunakan untuk memberikan respons saat pengguna menggulir halaman. Ketika pengguna menggulir halaman, fungsi yang ditentukan akan dijalankan, yaitu mencetak pesan di konsol yang menunjukkan seberapa jauh halaman telah digulir, dan mengubah warna latar belakang elemen div dengan id halaman berdasarkan seberapa jauh halaman telah digulir. Jika halaman telah digulir lebih dari 500 piksel, warna latar belakang akan berubah menjadi biru muda. Jika tidak, warna latar belakang akan kembali ke warna putih. Dengan demikian, pengguna akan mendapatkan umpan balik visual mengenai posisi mereka dalam halaman.

# Section 8 (Checkbox)

Contoh 1: Membuat daftar tugas dengan checkbox
- Dalam contoh 1, checkbox digunakan untuk membuat daftar tugas yang dapat ditandai sebagai selesai atau belum selesai. Ketika checkbox dicentang, event change akan terpicu dan menjalankan fungsi yang menambahkan kelas "selesai" ke elemen li yang memuat checkbox tersebut. Ketika checkbox dicentang kembali untuk membatalkan pilihan, kelas "selesai" akan dihapus. Dengan demikian, pengguna dapat memantau kemajuan mereka dalam menyelesaikan tugas dengan melihat tugas yang telah ditandai sebagai selesai.

Contoh 2: Filter konten dengan checkbox
- Dalam contoh 2, checkbox digunakan untuk membuat filter konten yang dapat diatur dengan checkbox. Ketika checkbox dicentang, event change akan terpicu dan menjalankan fungsi yang mengambil jenis konten dari id checkbox dan menampilkan konten yang sesuai dengan kelas yang sama dengan jenis konten tersebut. Ketika checkbox dicentang kembali untuk membatalkan pilihan, konten yang ditampilkan akan disembunyikan kembali. Dengan demikian, pengguna dapat menyaring konten berdasarkan jenis konten yang mereka pilih.