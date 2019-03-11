# CUBE Functions

Di dalam Cube Functions, terdapat 7 fungsi yang terdapat dalam Microsoft Excel. antara lain:

* CUBEMEMBER
* CUBEVALUE
* CUBESET
* CUBERANKEDMEMBER
* CUBEMEMBERPROPERTY
* CUBEKPIMEMBER
* CUBESETCOUNT

## CUBEMEMBER

CUBEMEMBER adalah salah satu fungsi cube yang digunakan untuk mengembalikan anggota atau rangkap dari kubus.

sintaks fungsi CUBEMEMBER adalah sebagai berikut :

CUBEMEMBER\(connection, member\_expression, \[caption\]\)



* **Connection**    Diperlukan. String teks nama koneksi ke kubus.
* **Member\_expression**    Diperlukan. Sebuah string teks ekspresi multidimensi \(MDX, multidimensional expression\) yang mengevaluasi anggota unik dalam kubus. Alternatifnya, member\_expression dapat berupa rangkap, yang ditentukan sebagai rentang sel atau konstanta array.
* **Keterangan**    Opsional. Sebuah string teks akan ditampilkan dalam sel sebagai ganti keterangan, jika ada, dari kubus. Bila rangkap dikembalikan, keterangan yang digunakan adalah keterangan untuk anggota terakhir dalam rangkap.



* Bila fungsi CUBEMEMBER mengevaluasi, fungsi ini sementara akan menampilkan pesan "\#GETTING\_DATA…" dalam sel sebelum semua data diambil.
* Bila Anda menggunakan CUBEMEMBER sebagai argumen untuk fungsi CUBE lainnya, ekspresi MDX yang mengidentifikasi anggota atau rangkap akan digunakan oleh fungsi CUBE tersebut, bukan nilai yang ditampilkan dalam sel fungsi CUBEMEMBER.
* Jika nama koneksi bukan merupakan koneksi buku kerja valid yang disimpan dalam buku kerja, CUBEMEMBER akan mengembalikan nilai \#NAME?. Jika server Pemrosesan Analitik Online \(OLAP, Online Analytical Processing\) tidak bekerja, tidak tersedia, atau mengembalikan pesan kesalahan, maka CUBEMEMBER akan mengembalikan nilai kesalahan \#NAME?.
* Jika setidaknya satu elemen dalam rangkap tidak valid, CUBEMEMBER akan mengembalikan nilai \#VALUE!.
* Jika member\_expression lebih panjang dari 255 karakter, yang merupakan batasan untuk argumen bagi sebuah fungsi, maka CUBEMEMBER akan mengembalikan nilai kesalahan \#VALUE! . Untuk menggunakan string teks yang lebih panjang dari 255 karakter, masukkan string teks dalam sel \(dengan batasan 32.767 karakter\), lalu gunakan referensi sel sebagai argumen.
* CUBEMEMBER mengembalikan nilai kesalahan \#N/A bila:
  * Sintaks member\_expression salah.
  * Anggota yang ditentukan oleh string teks MDX tidak ada di dalam kubus.
  * Rangkap tidak valid karena tidak terdapat irisan untuk nilai-nilai yang ditentukan. \(Ini dapat terjadi pada beberapa elemen dari hierarki yang sama.\)
  * Set berisi setidaknya satu anggota dengan dimensi yang berbeda dibandingkan anggota lainnya.
* CUBEMEMBER dapat mengembalikan nilai kesalahan \#N/A jika Anda mereferensikan objek berbasis sesi, seperti anggota terhitung atau set bernama, dalam PivotTable saat berbagi koneksi, dan PivotTable tersebut dihapus atau Anda mengonversi PivotTable ke rumus. \(Pada tab **Opsi**, di grup **Alat**, klik **Alat OLAP**, lalu klik **Konversi ke Rumus**.\)







