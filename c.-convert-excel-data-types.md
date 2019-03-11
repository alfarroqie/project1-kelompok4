# C. Convert Excel Data Types

1. BAHTTEXT  
          Fungsi BAHTTEXT digunakan untuk merubah angka menjadi sebuah teks, namun disini tidak menggantinya dengan text biasa, melainkan dengan format mata uang ß \(baht\). Baht ini perlu anda ketahui adalah sebuah text berbahasa Thailand. Sintaksnya adalah :

```text
=BAHTTEXT(text)
```

2. DOLLAR  
          Fungsi DOLLAR digunakan untuk merubah angka menjadi teks dengan ditambahkan simbol dari mata uang dan juga menentukan berapa banyak angka di belakang koma. Untuk mata uang sendiri bisa berbeda-beda sesuai dengan settingan pada komputer masing-masing. number berisi angka/sel yang akan diubah, decimal berisi jumlah angka di belakang koma. Sintaksnya adalah :

```text
=DOLLAR(number;[decimals])
```

3. FIXED  
          Fungsi FIXED digunakan untuk membulatkan angka ke jumlah desimal yang ditentukan.  
- number berisi angka yang akan dibulatkan/sel yang berisi angka yang akan dibulatkan  
- decimals berisi jumlah angka dibelakang koma  
- no\_commas berisi 1 atau 0, di mana 1 tanpa koma dan 0 dengan koma  
Sintaksnya adalah :

```text
=FIXED(number;[decimals];[no_commas])
```

4. TEXT  
          Fungsi TEXT  digunakan untuk mengkonversi nilai angka \(numeric\) menjadi teks \(string\) dalam format yang ditentukan.  Fungsi TEXT memungkinkan Anda untuk mengubah cara angka muncul dengan menerapkan pemformatan ke dalamnya dengan kode format. Sintaksnya adalah :

```text
=TEXT(value;format_text)
```

5. VALUE  
          Fungsi VALUE  digunakan untuk mengonversi string teks yang menyatakan angka menjadi angka. Sintaksnya adalah :

```text
=VALUE(text)
```

6. NUMBERVALUE  
          Fungsi NUMBERVALUE digunakan untuk mengonversi teks menjadi angka secara lokal independen. 

* **Text**    Diperlukan. Teks yang akan dikonversi menjadi angka.
* **Decimal\_separator**    Opsional. Karakter yang digunakan untuk memisahkan bilangan bulat dan bagian pecahan dari hasil.
* **Group\_separator**    Opsional. Karakter yang digunakan untuk memisahkan pengelompokan angka, seperti ribuan dari ratusan dan jutaan dari ribuan.

Sintaksnya adalah :

```text
=NUMBERVALUE(text;[decimal_separator];[group_separator])
```

