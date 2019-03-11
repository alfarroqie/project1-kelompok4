# B. Basic Mathematical Operations



1. SUM           Fungsi SUM adalah fungsi yang digunakan untuk menjumlahkan data-data dalam jumlah yang banyak sehingga lebih mudah dan cepat. Sintaksnya adalah :

```text
=SUM(cell_awal:cell_akhir)
```

2. PRODUCT  
              Fungsi PRODUCT digunakan untuk mencari hasil dari perkalian dari sederetan bilangan. Bilangan yang dikalikan dapat berupa bilangan yang kita _entry-_kan atau bilangan yang ada dalam range yang kita cantumkan. Sintaksnya adalah : 

```text
=PRODUCT(num1,num2,...,num3)
```

```text
=PRODUCT(cell_awal:cell_akhir)
```

3. POWER  
              Fungsi POWER digunakan untuk mendapatkan hasil dari bilangan yang akan dipangkatkan.

```text
=POWER(number, power)
```

4. SQRT  
             Fungsi SQRT digunakan untuk mendapatkan hasil dari bilangan yang akan diakarkan.

```text
=SQRT(number) atau =SQRT(cell)
```

5. QUOTIENT  
              Fungsi QUOTIENT digunakan untuk mendapatkan hasil integer dari sebuah operasi pembagian. 

```text
=QUOTIENT(pembilang, penyebut)
```

6. MOD  
             Fungsi MOD digunakan untuk mendapatkan sisa hasil bagi integer dari sebuah operasi pembagian.

```text
=MOD(pembilang, penyebut)
```

7. SUBTOTAL  
              Fungsi SUBTOTAL adalah fungsi yang mencakup beberapa fungsi matematik lainnya yaitu : AVERAGE, COUNTA, COUNT, MAX, MIN, PRODUCT,  STDEV.S, STDEV.P, SUM, VAR.S, dan VAR.P. Setiap fungsi yang dicakup, memiliki sebuah nomor identitas untuk menyatakan fungsinya masing-masing. Berikut adalah tabel nomor identitas fungsi yang dicakup subtotal.

| Nama Fungsi | Nomor Identitas | Fungsi |
| :--- | :--- | :--- |
| AVERAGE | 1 | Mendapatkan nilai rata-rata |
| COUNTA | 2 | Menghitung banyaknya data angka |
| COUNT | 3 | Menghitung banyaknya data |
| MAX | 4 | Mencari nilai maksimum |
| MIN | 5 | Mencari nilai minimum |
| PRODUCT | 6 | Menghitung perkalian |
| STDEV.S | 7 | Mencari nilai standar deviasi S |
| STDEV.P | 8 | Mencari nilai standar deviasi P |
| SUM | 9 | Menjumlahkan |
| VAR.S | 10 | Mencari nilai varian S |
| VAR.P | 11 | Mencari nilai varian P |

Sintaksnya adalah :

```text
=SUBTOTAL(nomor_identitas;ref1;ref2;...;refn)
```



