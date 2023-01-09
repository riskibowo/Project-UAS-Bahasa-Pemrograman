## Nama     : Riski probo asadewo
## kelas    : TI.22.A2
## Nim      : 312210191
# Project-UAS-Bahasa-Pemrograman
# Module & Package
di Praktikum 6 ini saya akan mempraktikan Module & Package
# Module
# Pengertian Module
- Modul merupakan bagian dari program yang berisi fungsi-fungsi yang dibuat pada file terpisah.

- Dengan adanya modul-modul yang terpisah, dapat dikelompokkan sesuai dengan fungsinya dan memudahkan dalam mengelola kode program.

- Modul dapat dipanggil sesuai dengan kebutuhannya.
# Membuat Module
untuk membuat Module pada python cukup mudah
- Buat sebuah file kode program python (ekstensi .py)

- Buat fungsi pada file tersebut
contoh:
```
# Python Module example 
   def add(a, b):
        """This program adds two   numbers and return the result"""
  
  result = a + b   
  return result
  ```
  # Menggunakan Module
- Untuk menggunakan modul yang telah dibuat cukup menggunakan perintah import

contoh:
```
 >>> import example
   >>> example.add(4,5.5)
   9.5
```
# Package
# Pengertian Package
- Package merupakan namespace yang berisi banyak modul dan paket.

- Package merupakan sebuah direktory yang berisi banyak file-file modul.

- Setiap package pada Python, harus ada file khusus yang bernama _ _ i n i t _ _ . p y

- File tersebut merupakan file kosong, atau bisa juga diisi dengan sesuatu.
# Membuat Package
Untuk membuat package pada Python cukup mudah.
- Buat sebuah directory (folder), dan tambahkan file kosong dengan nama _ _ i n i t _ _ . p y

- Buat sejumah file kode program python (ekstensi .py) pada folder tersebut yang berisi fungsi-fungsi (modul program)
# Menggunakan Package
- Untuk menggunakan package yang telah dibuat cukup menggunakan perintah import

contoh:
```
import nama_package.nama_module
  atau 
  from nama_package import nama_module
```
# Membuat package dan modul berdasarkan tugas praktikum sebelumnya dengan struktur seperti berikut:
- daftar_nilai.py berisi modul untuk: tambah_data, ubah_data, hapus_data, dan cari_data

- view_nilai.py berisi modul untuk: cetak_daftar_nilai, cetak_hasil_pencarian

- input_nilai.py berisi modul untuk: input_data yang meminta pengguna memasukkan data.

- main.py berisi program utama (menu pilihan yang memanggil semua menu yang ada)
# Package & Module
![image](https://user-images.githubusercontent.com/115862112/211322133-4571a1d4-50c4-48c7-9f85-c4e8eb550501.png)
# daftar_nilai
![image](https://user-images.githubusercontent.com/115862112/211322307-1d9d9501-91b7-46de-bcc6-af14e30655b3.png)

![image](https://user-images.githubusercontent.com/115862112/211322383-313b5b61-d4c8-4a5f-8fd2-9f69d8c0f9ac.png)
# input_nilai
![image](https://user-images.githubusercontent.com/115862112/211322527-6635cfa6-73e7-40a1-bd11-64598c76b091.png)

![image](https://user-images.githubusercontent.com/115862112/211322616-f242e7f9-e1ac-477b-b9a8-dab3f7c894c2.png)
# view_nilai
![image](https://user-images.githubusercontent.com/115862112/211322789-e35c846b-90b1-4839-bed1-cb29300b3544.png)

![image](https://user-images.githubusercontent.com/115862112/211322957-76b9ce0a-9d10-4e5a-a110-c4fdfe542c52.png)
# main
![image](https://user-images.githubusercontent.com/115862112/211323115-44843035-b4d2-406e-a416-f4e893541513.png)
# Output
![image](https://user-images.githubusercontent.com/115862112/211323527-2a869b62-c299-4cdf-80f9-2cb2a616f244.png)
![image](https://user-images.githubusercontent.com/115862112/211323626-064c7012-725c-458c-9a51-18d922fca3eb.png)
### Demikian untuk praktikum saya hari ini saya ucapkan terimakasih Wassalamu'alaykum Wr, Wb
