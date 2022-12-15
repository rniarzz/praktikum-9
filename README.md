# Nama: Rini Ariza
# NIM: 312210337
# Kelas: TI.22.A3

## PERTEMUAN 13

## **Contoh dan Penjelasan modul praktikum 13**
Contoh dalam bentuk foto dan penjelasan dalam bentuk tulisan
### **Penjelasan Pertama**

![ss0](foto_modul_ss/ss0.png)

Berikut adalah fungsi yang mengubah mengubah suhu suhu dari derajat Kelvin ke derajat Fahrenheit.
Karena nol derajat Kelvin sedingin yang didapat. Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback...AssertionError artinya terjadi error pada pernyataan assert.
### **Penjelasan Kedua**

![ss1](foto_modul_ss/ss1.png)

contoh ini membuka file, menulis konten di file, dan keluar tidak ada masalah, Ini menghasilkan hasil berikut 
```
Written content in the file successfully
```
Dan kenapa hasilnya begitu? karena else akan dijalankan ketika try adalah True
### **Penjelasan Ketiga**

![ss2](foto_modul_ss/ss2.png)

Mengapa muncul error?
```
Error: can't find file or read data
```
r adalah read - Membuka file untuk membaca, error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya `fh = open("testfile", "r")` tambahkan `print(fh.readline())` dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan
### **Penjelasan Keempat**

![ss3](foto_modul_ss/ss3.png)
Menghasilkan output:
```
Error: can\'t find file or read data
```
Ini bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan
### **Penjelasan Kelima**

![ss4](foto_modul_ss/ss4.png)
ketika dijalankan, maka muncul error. Hapus `#!/usr/bin/python` dan di `except ValueError, Argument:` ganti koma dengan as seperti `except ValueError as Argument:`agar tidak error. Jika dijalankan akan muncul error lagi
```
The argument does not contain numbers
invalid literal for int() with base 10: 'xyz'
```
kenapa? karena parameter def temp_convert harus mengandung angka
### **Penjelasan Keenam**

![ss5](foto_modul_ss/ss5.png)
Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada `raise "Invalid level!", level` ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1
