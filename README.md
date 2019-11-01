# labspy2tio
- Pengertian Kondisi If Else If Bahasa Python

  kondisi If Else If adalah sebuah struktur logika program dengan menyambung beberapa kondisi If Else menjadi sebuah kesatuan.
Jika kondisi pertama tidak terpenuhi atau bernilai False, 
maka kode program akan lanjut ke kondisi If di bawahnya. 
Jika ternyata tidak juga terpenuhi, akan lanjut lagi ke kondisi If di bawahnya
dst hingga blok Else terakhir atau terdapat kondisi If yang bernilai True.

yang pertama kita akan membuat contoh bilangan yang memasukin bilangan satu sampai tiga
Bilangan1 = int(input("Masukkan Bilangan 1:")) Bilangan2 = int(input("Masukkan Bilangan 2:")) Bilangan3 = int(input("Masukkan Bilangan 3:"))


![Bilangan](https://user-images.githubusercontent.com/56244106/68000435-63cad880-fc1d-11e9-88ef-84d78c25706b.PNG)


Berikutnya kita juga bisa membuat kondisi if int(Bilangan1) and (Bilangan1 > Bilangan3): seperti dibawah ini :
print("Nilai terbesarnya adalah :", Bilangan1) Terbesar = Bilangan1 NomBil = "Bilangan 1"


![Print terbesarnya bilangan 1](https://user-images.githubusercontent.com/56244106/68000946-4ac32700-fc1f-11e9-8f81-1a5e9814ee1d.PNG)



Selanjutnya kita juga bisa membuat kondisi elif (Bilangan2 > Bilangan3) and (Bilangan2 > Bilangan1): Seperti dibawah ini:
print("Nilai terbesarnya adalah :", Bilangan2) Terbesar = Bilangan2 NomBil = "Bilangan 2"
else: Terbesar = Bilangan3 NomBil = "Bilangan 3"


![elif bil 2](https://user-images.githubusercontent.com/56244106/68001104-e0f74d00-fc1f-11e9-9195-d620dd4109e5.PNG)

Selanjutnya kita mengetahui setelah RUN yang benar:


![200,400,600](https://user-images.githubusercontent.com/56244106/68001583-db026b80-fc21-11e9-88e8-a3e37865148b.PNG)


Pada if segment diatas memiliki ketentuan nilai if pertama harus bernilai true barulah nilai if yang berikutnya yang akan di proses atau dieksekusi, namun jika nilai if pertama bernilai false maka nilai if yang berikutnya tidak akan di proses, namun jika nilai if yang pertama bernilai true sedangkan nilai if yang kedua bernilai false maka yang akan di proses hanyalah if yang pertama. Berikut hasilnya jika if segment yang kita masukan bernilai true 

selanjutnya kita juga bisa menambahkan is dan is not pada if segment seperti dibawah ini :

Pada Bahasa pemrograman python untuk membuat sebuah kondisi sama halnya dengan Bahasa pemgraman yang lain yaitu sama-sama menggunakan if, pada setiap pemrograman if berisi sebuah ekspresi logika menggunakan sebuah data yang telah dibandingkan seperti alur flowchart dibawah ini.

Contoh:
![flowchart](https://user-images.githubusercontent.com/56244106/68001730-8ca19c80-fc22-11e9-9570-bb39c195b53d.PNG)
