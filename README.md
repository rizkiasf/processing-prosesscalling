# processing-prosesscalling

Program tersebut merupakan sebuah sketsa dalam Processing yang menghasilkan animasi sebuah persegi panjang berwarna yang berputar di tengah layar. Berikut adalah kesimpulan dari program tersebut:

* Pengaturan Awal (setup):

- Ukuran kanvas ditetapkan menjadi 200x200 piksel.
- Latar belakang kanvas diisi dengan warna putih (255).
- Aktifkan fitur smooth() untuk membuat tepian gambar lebih halus.
- Nonaktifkan batas (stroke) pada bentuk yang digambar.
* Penggambaran Animasi (draw):

// Pada setiap frame, jika frameCount (jumlah frame yang telah berlalu) adalah kelipatan dari 10, maka:
Warna pengisian (fill) untuk persegi panjang ditentukan oleh nilai frameCount yang dimodulasi dengan 255, sehingga menghasilkan perubahan warna yang dinamis.
- Posisi gambar dipindahkan ke pusat kanvas (100,100).
- Rotasi persegi panjang diatur berdasarkan nilai frameCount yang dimodulasi dengan 360 derajat, sehingga persegi panjang berputar.
- Persegi panjang dengan ukuran 80x20 piksel digambar di posisi (0,0) dalam sistem koordinat yang telah diubah.
- Mengembalikan sistem koordinat ke keadaan semula setelah menggambar persegi panjang dengan menggunakan popMatrix().

# Kesimpulannya, program ini membuat animasi persegi panjang berwarna yang berputar di tengah kanvas, dengan warna dan sudut rotasi yang berubah setiap 10 frame.
