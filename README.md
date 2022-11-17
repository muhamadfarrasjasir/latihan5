# latihan5
![WhatsApp Image 2022-11-18 at 05 33 58](https://user-images.githubusercontent.com/115479895/202577992-7810aaf2-677e-4fa8-a723-4dbe051582ba.jpeg)
Berikut adalah tampilan program menggunakan bahasa Python
![Screenshot (56)](https://user-images.githubusercontent.com/115479895/202578231-def253c6-3739-4511-b788-f8e06ac6cdf2.png)

 Muhamad farras jasir: from prettytable import PrettyTable Membuat header table menggunakan prettytable. Variabel import berfungsi untuk memanggil file lain di dalam satu module yang berbeda.

print("Program Input Data Mahasiswa") print() untuk menampilkan kalimat yang di input.

tabelNama = PrettyTable(["No" ,"Nama" ,"NIM" ,"Nilai Tugas" ,"Nilai UTS" ,"Nilai UAS" ,"Nilai Akhir" ])
a = 0
(Deklarasi list)untuk menginput data yang dimasukkan kedalam list. input tabelNama untuk memanggil. sedangkan PrettyTable berfungsi untuk membungkus semua list. Deklarasi a = 0 untuk membuat nomor pada isi table.

Membuat program perulangan menggunakan py while True:

 a += 1
 b = input("Masukkan Nama : ")
 c = input("Masukkan NIM : ")
 d = int(input("Masukkan Nilai Tugas : "))
 e = int(input("Masukkan Nilai UTS : "))
 f = int(input("Masukkan Nilai UAS :" ))
 g = "{:.2f}".format((d*.30) + (e*.35) + (f*.35))
a += 1 untuk menginput nomer pada awal table. deklarasi list dan Memasukkan Input Dengan Fungsi input() untuk menulis nama yang akan kita simpan dalam variabel. int(input()) untuk menginput tipe data interger (bilangan bulat) dalam variabel.

{:.2f}".format((d*.30) + (e*.35) + (f*.35)) untuk menginput Nilai Akhir yang di ambil dari perhitungan 3 komponen nilai.

 tabelNama.add_ro ([a,b,c,d,e,f,g])
 tabelNama.horizontal_char = "="
 tabelNama.junction_char = "="
 variabel di atas adalah untuk membentuk sebuah table.
Program input tanya [y/t], apabila jawaban t atau T, maka program inputan dihentikan statement break dan akan menampilkan data yang sudah diinput.
Output
Bila dijalankan maka program akan menghasilkan output seperti dibawah ini
![Screenshot (55)](https://user-images.githubusercontent.com/115479895/202578285-c31c9ad7-e19d-4dfd-b175-77e600b1f5dc.png)
