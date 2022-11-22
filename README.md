# Tugas_list

## Program Menambahkan Data Pada Sebuah List

![1](https://user-images.githubusercontent.com/115676957/203261283-9f5a3bbe-ec82-4116-ada6-ffe1f28796f3.jpeg)


1. Memasukkan atau menambahkan data pada sebuah list, kita bisa menggunakan perintah append(), extend() tapi untuk program kali ini kita menggunakan perintah append(), karna kita akan menambahkan data satu persatu.
Pertama saya membuat sebuah variabel list kosong yang terdiri dari: nama=[], nim=[], tugas[], uts[], uas[], dan akhir[]. variabel list itu nanti yang akan kita isi dengan menggukan perintah append(), dan juga jangan lupa untuk membuat variabel lanjut = 'y' untuk perulangan while dan no = 0 untuk nomor pada output an nantinya

![2](https://user-images.githubusercontent.com/115676957/203261339-80625d97-bc8d-4990-b32f-a39a0fd97145.jpeg)


2. Cara untuk melakukan penambahan data pada variabel list yang sudah kita buat tadi adalah dengan menggunakan perulangan while supaya kita bisa menambahkan lebih dari satu kali atau satu data dan perulangan tersebut akan berakhir ketika kita mengetikkan tidak sama dengan y atau !='y' dalam program (while lanjut == 'y'), tetapi sebelum itu kita harus membuat inputan sebuah variabel agar nanti proses perhtungan nilai akhir tidak eror, karena kita tidak bisa membuat operator aritmatika pada data list. kode programnya sebagai berikut:
na = str(input('Nama: '))
ni= int(input('NIM: '))
tug= int(input('Nilai tugas: '))
ut = int(input('Nilai UTS: '))
us= int(input('nilai uas: ')) 

![3](https://user-images.githubusercontent.com/115676957/203261407-0810bd5b-e893-4864-a03d-c9a3340b5e65.jpeg)


Kode program untuk proses perhitungan pada nilai akhir yang di ambil dari tugas 30%, uts 35% dan uas 35%, jika ditulis dalam kode program menjadi : - akhir=(tugas0.3)+(uts0.35)+(uas*0.35) lalu kita akan gunakan perintah append() agar nanti nilai yang di inputkan bisa masuk kedalam variabel list yang tadi sudah kita buat: - nama.append(na) - nim.append(ni) - tugas.append(tug) - uts.append(ut) - uas.append(us) - akhir.append(akh)

![4](https://user-images.githubusercontent.com/115676957/203261641-a8d05e1c-43e3-48b6-9a05-f08a72ee9c83.jpeg)


kita juga menggunakan operator assigment pada variabel no, yang berfungsi agar nanti menjadi batas atau range pada perulangan for - no+=1

![5](https://user-images.githubusercontent.com/115676957/203261686-d4d97502-d3d4-49fb-a9ac-ebec15e8a643.jpeg)


terakhir kita input 'lanjut (y/t)? tadi sudah kita bahas soal fungsi lanjut ini yakni untuk mengulangi perulangan while, jika 'y' maka akan melanjutkan perulangan nya tetapi, jika selain 'y' maka perulangan akan berhenti.

3. Menampilkan atau output dari program yang sudah kita buat disini kita menggunakan perulangan for
for i in range(no) print(nama[i], nim[i], tugas[i], uts[i], uas[i], akhir[i]) di output an ini kalian bebas berkreasi agar tampilan lebih menarik.
Contoh Program

![6](https://user-images.githubusercontent.com/115676957/203261764-6cde6708-2247-4013-9ae7-9dc803ca9291.jpeg)
![7](https://user-images.githubusercontent.com/115676957/203261806-2b8ff7d5-b330-4376-90ff-999f832d41bd.jpeg)

