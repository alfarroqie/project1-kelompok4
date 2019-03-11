# C. Rounding Function



1. CEILING.MATH  
              Fungsi CEILING.MATH adalah fungsi yang digunakan untuk melakukan pembulatan ke beberapa kelipatan diatasnya serta menggunakan salah satu dari dua mode yang ada, yaitu 1 atau -1. Mode 1 artinya pembulatan dilakukan keatas, dan mode -1 artinya pembulatan dilakukan kebawah. Misalnya 2,5 akan dibulatkan ke 1 kelipatan dengan mode 1, maka hasilnya adalah 3. Contoh lainnya, 212,5 akan dibulatkan ke 2 kelipatan dengan mode 1, maka hasilnya adalah 214. Sintaksnya adalah :

```text
=CEILING.MATH(angka;kelipatan;mode)
```

2. EVEN  
             Fungsi EVEN adalah fungsi yang digunakan untuk melakukan pembulatan keatas dengan hasil yang genap. Misalnya 1,5 akan dibulatkan ke 2, sebagai bilangan genap terdekat dari 1,5. Contoh lainnya, 2,5 akan dibulatkan ke 4, sebagai bilangan genap terdekat dari 2,5.

```text
=EVEN(number)
```

3. FLOOR.MATH  
            Fungsi FLOOR.MATH adalah fungsi yang mirip dengan fungsi CEILING.MATH, perbedaannya adalah fungsi ini melakukan pembulatan kebawah. Sebenarnya mode yang ada yaitu 1 atau -1 hanyalah sebuah tambahan.

```text
=FLOOR.MATH(angka;kelipatan;mode)
```

4. INT  
            Fungsi INT adalah fungsi yang sama dengan fungsi FLOOR.Math \(pembulatan kebawah\), namun dalam teknisnya, fungsi INT tidak dapat melakukan pembulatan yang menggunakan kelipatan.

```text
=INT(number)
```

5. MROUND  
            Fungsi MROUND adalah fungsi untuk mendapatkan nilai pembulatan yang mendekati nilai kelipatan yang diminta. Fungsi ini berbeda dengan CEILING.MATH ataupun FLOOR.MATH karena kelipatan yang dimaksud adalah menghasilkan nilai pembulatan yang mendekati **ke** kelipatan angka yang dimasukkan sedangkan CEILING.MATH menghasilkan nilai pembulatan **dengan** kelipatan yang dimasukkan. Contoh, 10 ke 3, akan menghasilkan nilai 9 karena kelipatan 3 terdekat dengan 10 adalah 9.

```text
=MROUND(number;kelipatan)
```

6. ODD  
          Fungsi ODD adalah kebalikan dari fungsi EVEN. Nilai akan dibulatkan ke bilangan ganjil terdekat.

```text
=ODD(number)
```

7. ROUND  
             Fungsi ROUND memerlukan dua parameter. Parameter angka diperlukan dan merupakan angka yang akan dibulatkan ke atas. Parameter jumlah\_angka diperlukan dan merupakan jumlah angka pembulatan yang ingin diterapkan pada nilai. Jumlah angka dibelakang koma yang dapat dicantumkan hanya bisa berfungsi apabila lebih besar sama dengan nol.

```text
=ROUND(angka; jml_angka)
```

8. ROUNDUP  
           Fungsi ROUNDUP hampir sama dengan fungsi ROUND. Namun, apabila jumlah\_angka lebih besar dari 0, maka angka akan dibulatkan ke atas ke sejumlah tempat desimal yang ditetapkan. Jika nilai jumlah\_angka adalah 0, angka dibulatkan ke atas ke nilai integer terdekat. Jika nilai jumlah\_angka lebih kecil dari 0, angka dibulatkan ke atas ke sebelah kiri tanda desimal \(misalkan 2289,678;-3 maka hasilnya adalah 2300, karena 3 angka dibelakang komanya dibulatkan\). Pembulatan dilakukan ke atas.

```text
=ROUNDUP(angka; jml_angka)
```

9. ROUNDDOWN  
           Fungsi ROUNDDOWN adalah fungsi yang sama dengan fungsi ROUNDUP, hanya saja, fungsi ini adalah kebalikan dari fungsi ROUNDUP yaitu pembulatan ke bawah.

```text
=ROUNDDOWN(angka; jml_angka)
```

10. TRUNC  
          Fungsi TRUNC pun sama dengan fungsi-fungsi pembulatan ROUND, namun pada fungsi ini, tidak diperhatikan apakah pembulatan dilakukan ke atas atau ke bawah.

```text
=TRUNC(angka; jml_angka)
```





