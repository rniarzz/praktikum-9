# Nama: Rini Ariza
# NIM: 312210337
# Kelas: TI.22.A3

## PERTEMUAN 13

## **Contoh dan Penjelasan modul praktikum 13**
Contoh dalam bentuk foto dan penjelasan dalam bentuk tulisan
### **Penjelasan Pertama**

<img width="528" alt="ss0" src="https://user-images.githubusercontent.com/115542704/207885053-d32e0c93-2ccc-4348-8a7f-bfa740b49169.png">

Berikut adalah fungsi yang mengubah mengubah suhu suhu dari derajat Kelvin ke derajat Fahrenheit.
Karena nol derajat Kelvin sedingin yang didapat. Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback...AssertionError artinya terjadi error pada pernyataan assert.
### **Penjelasan Kedua**

<img width="536" alt="ss1" src="https://user-images.githubusercontent.com/115542704/207885165-1cbccee1-5b1c-4c43-9466-5f0abf7a5f9f.png">

contoh ini membuka file, menulis konten di file, dan keluar tidak ada masalah, Ini menghasilkan hasil berikut 
```
Written content in the file successfully
```
Dan kenapa hasilnya begitu? karena else akan dijalankan ketika try adalah True
### **Penjelasan Ketiga**

<img width="530" alt="ss2" src="https://user-images.githubusercontent.com/115542704/207885268-906292a4-b656-4b25-b47e-39a13183d136.png">


Mengapa muncul error?
```
Error: can't find file or read data
```
r adalah read - Membuka file untuk membaca, error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya `fh = open("testfile", "r")` tambahkan `print(fh.readline())` dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan

### **Penjelasan Keempat**

<img width="537" alt="ss3" src="https://user-images.githubusercontent.com/115542704/207885325-e6c91be0-e1fa-422a-8fab-bcc6d46a67cd.png">


Menghasilkan output:
```
Error: can\'t find file or read data
```
Ini bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan
### **Penjelasan Kelima**

<img width="474" alt="ss4" src="https://user-images.githubusercontent.com/115542704/207885400-cbad94d1-180e-4893-9bbc-b699de955852.png">

ketika dijalankan, maka muncul error. Hapus `#!/usr/bin/python` dan di `except ValueError, Argument:` ganti koma dengan as seperti `except ValueError as Argument:`agar tidak error. Jika dijalankan akan muncul error lagi
```
The argument does not contain numbers
invalid literal for int() with base 10: 'xyz'
```
kenapa? karena parameter def temp_convert harus mengandung angka
### **Penjelasan Keenam**

<img width="470" alt="ss5" src="https://user-images.githubusercontent.com/115542704/207885450-c0589490-f180-4081-ba9d-0377258ab77d.png">


Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada `raise "Invalid level!", level` ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1
