# Latihan1.-Py
digunakan untuk mengerjakan python

# PERTEMUAN KE 6 - Bahasa Pemrograman
**Repository ini dibuat untuk memenuhi tugas bahasa pemrograman pertemuan ke-6**

 **==================================================** <br>
**Nama      : Farhan Ariansyah Saputra**<br>
**NIM       : 312010414**<br>
**Kelas     : TI.20.B2**<br>
 **==================================================**

DAFTAR ISI <br>
| No | Description | Link |
| ----- | ----- | ---- |
| 1 | Tugas pertemuan 5 | [Click Here](#pertemuan-5---tugas-bahasa-pemrograman)
| 2 | Tugas pertemuan 6 Lab 1 | [Click Here](#pertemuan-6---lab-1)
| 3 | Tugas pertemuan 6 Lab 1.2 | [Click Here](#pertemuan-6-lab-12)
| 4 | Tugas pertemuan 6 Lab 2 | [Click Here](#pertemuan-6---lab-2)
<br>

# PERTEMUAN 5 - TUGAS BAHASA PEMROGRAMAN

     
Pada pertemuan ke-5 Bahasa pemrograman, saya diberi tugas oleh dosen untuk membuat aplikasi biodata dengan Python (seperti dibawah ini)

![input gambar](picture/tugas5.PNG)<br>

Saat ini saya akan menjelaskan hasil dari tugas tersebut <br>
Berikut *source code* nya atau klik link berikut ( [tugas-ke-5](p5_tugas.py) ): <br>

```python
print("Please enter full name : ")
fullname=input()

print("please insert your Nickname : ")
nickname=input()

print("please enter your NPM : ")
NPM=input()

print("please enter your Born place : ")
bornplace=input()

print("please insert your age : ")
age=input()

print("please enter your home address : ")
address=input()

print("please enter your phone number : ")
phonenumber=input()

print("\nAssalamualaikum Wr, Wb.")
print(f"\nLet me introduce my self. My name is {fullname}, but you can call me {nickname}. My NPM is {NPM}. I was Born in {bornplace} and i am {age} years old. I am very glad if you want to invite my house in {address}. So, don't forget to call me before with the number {phonenumber}.")
print("\nThank you.")
print("\n") 
``` 
<br>
Berikut penjelasanya : <br>

```python
print("Please enter full name : ")
```
Source Code ini berfungsi untuk mencetak hasil atau output berupa ***"Please enter full name"*** seperti gambar dibawah ini :<br>

Untuk menampilkan output String, saya menggunakan *tanda petik dua*, contohnya :

```python
print("Nama saya adalah ...")
print(12345)
```

![input gambar](picture/fullname1.PNG)<br>

* Untuk source kode berikutnya adalah inputan atau membuat variabel, seperti syntax dibawah ini

```python
Fullname=input()
```
Keterangan<br>
1. Variabel adalah sebuah penyimpanan data pada program yang akan digunakan selama program ini berjalan. Yang berfungsi sebagai variabel dalam source code diatas adalah **Fullname**. <br>
2. Fungsi **input()** adalah untuk memasukan nilai dari layar consol di command prompt, lalu kemudian mengembalikan nilai saat kita menekan tombol Enter
 *(newline)*<br>

![input gambar](picture/fullname2.PNG)<br>

Pada gambar diatas, hasil dari inputan tersebut berwarna *hijau*<br>

* Untuk perintah masukan yang lain seperti *nickname, NPM, ... dst, masukan perintah yang sama seperti memasukan *fullname*

* Langkah kali ini saya akan menampilkan output yang diminta oleh Dosen,<br>
output pertama yang diminta Dosen adalah menampilkan salam, yaitu dengan mengetikan syntax/ source code dibawah ini :

```python
print("\nAssalamualaikum Wr, Wb.")
```
Keterangan :<br>
1. Fungsi ***\n*** pada source code diatas adalah untuk memberi barisan baru / Enter / *newline*
2. Fungsi print(), seperti dijelaskan pada point *output* diatas<br>

Hasil dari source code diatas adalah seperti gambar dibawah ini : 

* Langkah terakhir adalah untuk menampilkan semua inputan diatas dengan mengetikan source code berikkut :

```python
print("\nAssalamualaikum Wr, Wb.")
print(f"\nLet me introduce my self. My name is {fullname}, but you can call me {nickname}. My NPM is {NPM}. I was Born in {bornplace} and i am {age} years old. I am very glad if you want to invite my house in {address}. So, don't forget to call me before with the number {phonenumber}.")
print("\nThank you.")
print("\n")
```
Keterangan :<br>
1. Fungsi huruf    ***f***  pada perintah ***print(f"...)*** adalah fungsi print yang dapat memudahkan programer untuk mencetak statement dalam satu baris dibandingkan dengan metode lama yaitu memisahkan string dan variabel dengan tanda koma ( , ) atau ( + ) <br>
2. Sedangkan fungsi {} pada output tersebut adalah untuk menampilkan hasil dari variabel<br>

Hasil dari output tersebut adalah :

![input gambar](picture/Hasil.PNG)<br>

<br>
<br>
<br>

# Pertemuan 6 - Lab 1

Pada tugas pertemuan ke-6 lab 1 saya diberikan tugas oleh Dosen yaitu mempelajari Aritmatika menggunakan bahasa pemrograman python. Berikut source code yang diberikan oleh dosen :

![input gambar](picture/lab1.PNG)

```python
#penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('z')

#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='.....')
```
<br>
Kali ini saya akan menjelaskan materi yang diterima dari Dosen. <br><br>

* Penggunaan End <br>
Penggunaan End digunakan untuk menambahkan karakter yang dicetak di akhir baris. Secara default penggunan End adalah untuk garis baris.

```python
print('A', end='')
print('B', end='')
print('C', end='')
```
> Penggunaan print() digunakan untuk mencetak output, seperti syntax dibawah ini :

```python
print('X')
print('Y')
print('z')
```
<br>
Hasil dari source code tersebut seperti gambar dibawah ini : <br><br>

![input gambar](picture/abc.PNG)

* Penggunaan Separator<br>
Esparator adalah pemisah yang berfungsi sebagai tanda pemisah antara objek yang dicetak. <br><br>

Default nya adalah tanda seperti :<br>
> Pendeklarasian beberapa variabel beserta nilainya

```python
print(w, x, y, z)
```
<br>

> Menampilkan hasil dari tiap-tiap variabel dengan menggunakan pemisah (koma)

```python
print(w, x, y, z, sep=',')
```
<br>

> Menampilkan hasil dari tiap-tiap variabel tanpa menggunakan pemisah

```python
print(w, x, y, z, sep='')
```
<br>

> Menampilkan hasil dari tiap-tiap variabel dengan menggunakan pemisah (titik dua)

```python
print(w, x, y, z, sep=':')
```
<br>

> Menampilkan hasil dari tiap-tiap variabel dengan menggunakan pemisah (titik-titik)

```python
print(w, x, y, z, sep='.....')
```

Hasil dari syntax / source code diatas adalah sebagai berikut : <br>

![input gambar](picture/oke.PNG)

# Pertemuan 6 Lab 1.2

* String format 
String formating atau pemformatan string memungkinkaan kita memasukan item kedalam string dari pada kita mencoba menggabungkan string menggunakan koma atau string concatenation.<br>

Penggunaa source code yang diberikan oleh Dosen seperti berikut : <br>

![input gambar](picture/lab1.2.PNG)

```python
#string format 1
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

#string format 2
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
```
<br>

Selanjutnya saya akan menjelaskan satu persatu kegunaan syntax tersebut. <br>

1. String format 1<br>
Pada syntax / source code string format 1 akan menampilkan berupa 2 output. <br>
* Akan menampilkan angka Urut dari angka 0 hingga angka 10
* Akan menampilkan Operasi Aritmatika Pangkat.

Dengan ketentuan sebagai berikut, operasi pangkat dengan angka kiri sebagai pokok (Rumus : ** [bintang dua]).<br><br>
Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10. dengan output sebagai berikut :

![input gambar](picture/string1.PNG)

2. String format 2<br>
Pada syntax atau source code string format 2 akan menampilkan output berupa 2 output'an juga (seperti String Format 1, yaitu kanan dan kiri).<br>
Dengan ketentuan sebagai berikut :

> Alignment, padding, dan precesion dengan **.format()** dalam kurung kurawal kita dapat menetapkan panjang bidang, rata kanan/kiri, parameter pembulatan dan banyak lagi. Contoh lain seperti berikut :

```python
print('{0:8} | {1:9}'.format('Buah','Jumlah'))
print('{0:8} | {1:9}'.format('Apel', 3.))
print('{0:8} | {1:9}'.format('Jeruk',10))
```
Hasil dari source code contoh diatas akan seperti berikut :<br>

![input gambar](picture/string2.PNG)

> Secara Default, **.format()** menggunakan rata teks ke kiri, angka ke kanan. Kita dapat menggunakan opsi opsional <, ^, atau > untuk mengatur perataan kiri, tengah, atau kanan. Contoh lain dalam penggunaan **.format()** sebagai berikut :
<br>

```python
print('{:<30}{:^30}{:>30}'.format('Kiri','Tengah','Kanan'))
print('{:<30}{:^30}{:>30}'.format(12,34,56))
```
Hasil dari source code contoh diatas akan muncul seperti ini :<br>

![input gambar](picture/string2juga.PNG)

Untuk hasil String format 2 sebagai berikut :
<br>

![input gambar](picture/string2lagi.PNG)

## Pertemuan 6 - lab 2

* Konversi nilai variabel
Untuk pembahasan terakhir, kali ini akan menyelesaikan tugas lab 2 dari Dosen, yaitu konvers nilai variabel <br>
tugas yang diberikan dosen adalah seperti gambar dibawah ini atau bisa diakses ke link [Pertemuan 6 - Lab 2](p6_lab2.py) : <br>

![input gambar](picture/lab2.PNG)

```python
a=input("masukkan nilai A : ")
b=input("masukkan nilai B : ")
print("variable A=",a)
print("variable B=",b)
print("hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#konversi nilai variable
a=int(a)
b=int(b)
print("hasil pejumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
```

Setelah saya menjalankan source code tersebut terdapat error, seperti gambar dibawah ini :

![input gambar](picture/lab2lagi.PNG)

Selanjutnya kita akan menyelesaikan error yang telah terdeteksi.<br>

> ***TypeError: %d format: a number is required, not str*** <br>

Pada error tersebut terbaca bahwa variable a adalah string, yang seharusnya dibaca oleh system adalah Number / Interger. <br>

***Bagaimana cara memperbaiki error tersebut?***<br>

Kita lihat pada baris ke 5 (di notifikasi terbaca bahwa error terletak pada baris ke 5), yaitu pada pemformatan .format() adalah interger, Sedangkan jika berupa string maka akan ada tanda petik dua ("..") pada pemformatan .format()
Kita akan terfokus pada variable a dan b.

Pada line 1 tertulis syntax : a=input("Masukkan Nilai A : ")
Sedangkan pada line 2 tertulis sytax : b=input("Masukkan Nilai B : ")

Untuk membuat inputan berupa interger/angka harus ditambahkan syntax int() pada format input(). Yang seharusnya ditulis adalah :

```python
a=int(input("masukkan nilai A : "))
b=int(input("masukkan nilai B : "))
print("variable A=",a)
print("variable B=",b)
print("hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#konversi nilai variable
a=int(a)
b=int(b)
print("hasil pejumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
```
Kita akan coba lagi untuk ***run*** file tersebut, maka akan muncul seperti gambar dibawah ini :

![input gambar](picture/runlab2.PNG)

Setelah semua file berhasil disimpan dan dijalankan berhasil, maka selesai sudah Tugas Pertemuan 6 - Bahasa Pemrograman kali ini.

<hr><hr>
================================ GOOD LUCK ===================================
<hr><hr>