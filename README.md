# Praktikum3

# Program python Menghitung Luas dan Keliling lingkaran

Kesempatan kali ini saya akan menghitung Luas dan Keliling Lingkarangn menggunakan python disertakan dengan Flowchart menghitung Luas dan Keliling lingkaran.

Saat akan mehitung Luas dan Keliling lingkaran hal pertama yang harus kita ketahui adalah rumus Luas dan Keliling dari lingkaran

**RUMUS LUAS DAN KELILING LINGKARAN**

`Luas       = pi*r*r`

`Keliling   = 2*pi*r`

* Nilai pi yang akan kita gunakan adalah 22/7

* r merupakan jari-jari lingkaran

**pi** merupakan nilai konstanta dimatekatika dalam sebuah lingkaran 

**jari-jari** merupakan jarak antara titik tengah\pusat dengan tepi lingkaran.

Sebenarnya ada rumus lain dalam menghitung kelililng lingkaran dengan menggunakan diameter, tapi pada kasus ini saya akan menggunakan jari-jari saja.


**FLOWCHART MENGHITUNG LUAS DAN KELILING LINGKARAN**

Berikut ini adalah contoh flowchart dari mulai hingga selesai

`Mulai > Masukan jari-jari > hitung luas & keliling > Tampilkan luas dan keliling lingkaran > selesai`


![image](https://user-images.githubusercontent.com/115475348/198184195-3939a506-0eda-42e5-94c3-516a5ffc0ab0.png)


**PROGRAM PYTHON MENGHITUNG LUAS & KELILING LINGKARAN**

**Input**

`print("Program python Menghitung Luas dan Keliling Lingkaran")`

`print("=====================================================\n")`


`pi      = 22/7`

`jari    = float(input("Masukan Jari-jarinya : "))`

`luas    = pi*(jari*jari)`

`keliling = 2*pi*jari`


`print("\n-----------------------Hasilnya------------------------")`

`print ("Luas Lingkaran \t\t= ",luas)`

`print ("Keliling lingkaran\t= ",keliling)`


Hasilnya seperti gambar berikut ini: 


<img width="487" alt="2022-10-26 input 1" src="https://user-images.githubusercontent.com/115475348/198186745-1502ef4b-e6cd-47aa-ad36-93c10b696445.png">



**Output**

`Program Python Menghitung Luas Dan Keliling Lingkaran`

`=====================================================`

`Masukan Jari-jarinya : 27`

`-----------------------Hasilnya------------------------`

`Luas Lingkaran          =  2291.142857142857`

`Keliling lingkaran      =  169.71428571428572`

Hasilnya seperti gambar berikut ini:

<img width="699" alt="2022-10-27" src="https://user-images.githubusercontent.com/115475348/198186927-938d2c9d-0ec8-4d7f-8d9f-31976e0cf9c8.png">


Ketika kita sudah mendapatkan nilai **pi** dan **jari-jari** selanjutnya kita bisa menghitung Luas dan Keliling dengan rumus masing-masing

Jika dilihat hasil luas dan keliling lingkaran mempunyai angka pecahan yang cukup banyak, untuk mengambil dua pecahan saja dibelakang koma(,) kita pakai fungsi **format()** seperti berikut:

**Input**

`print("\n-----------------------Hasilnya------------------------")`

`print("Luas Lingkaran =","{:.2f}".format(luas))`

`print("Keliling Lingkaran =","{:.2f}".format(keliling))`

Hasilnya seperti gambar berikut ini:

<img width="478" alt="2022-10-26 input 2" src="https://user-images.githubusercontent.com/115475348/198187936-1d46e013-0c15-489f-9d65-2991df6967ac.png">

**Output**

`-----------------------Hasilnya------------------------`

`Luas Lingkaran = 2291.14`

`Keliling Lingkaran = 169.71`

Hasilnya seperti gambar berikut ini:

<img width="405" alt="2022-10-27 2" src="https://user-images.githubusercontent.com/115475348/198188205-363454ea-ff17-4178-ae9d-b5218250da06.png">

Dengan menggunakan fungsi **format(luas,'.2')** maka akan menghasilkan 2 angka pecahan saja di belakang koma.

Sekian dulu pembahasan kali ini mengenai contoh program python untuk menghitung luas dan keliling lingkaran. Kurang lebihnya mohon maaf.

Terimakasih.


