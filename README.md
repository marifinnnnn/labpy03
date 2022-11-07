# NAMA : Muhammad arifin

# NIM  : 312210330

# KELAS : TI.22.A3

# labspy02

# praktikum 2

# Program sederhana dengan input tiga buah bilangan lalu tampilkan bilangan terbesarnya

# A.algoritma program untuk menampilkan bilangan terbesar dari tiga buah bilangan

1. mulai
2. input bil1,bil2,dan bil3 sebagai integer
3. baca bil1
4. baca bil2
5. baca bil3
6. Jika bil1 > bil2 dan bil1 > bil3 maka kerjakan langkah 8, selain itu
7. Jika bil2 > bil1 dan bil2 > bil3 maka kerjakan langkah 9, selain itu kerjakan langkah 10.
8. print "blangan terbesar bilangan pertama"
9. print "bilangan terbesar bilangan kedua"
10. print "bilangan terbesar bilangan ketiga"
11. selesai

# B.flowchart program

![200127222-263db6a8-6a0d-4842-a078-4af40a30c298](https://user-images.githubusercontent.com/115518274/200255208-821fbe19-f527-460e-89eb-b23797363ebb.png)

# D.Hasil

![Screenshot (20)](https://user-images.githubusercontent.com/115518274/200257615-02cacf0e-646d-4a4a-bbc2-d00523917971.png)

# labspy03

# latihan1

# Program sederhana untuk menampilkan N bilangan acak yang lebih kecil dari 0,5

# A.algoritma program untuk menampilkan N bilangan acak yang lebih kecil dari 0,5

1. Masukkan jumlah N perulangan
2. proses perulangan sesuai jumlah perulangan yang diinputkan
3. tampilkan perulangan dengan nilai dibawah 0,5
4. selesai

# B.flowchart program

![200127252-15e9543a-44e8-4f7c-b83a-1972c23cada2](https://user-images.githubusercontent.com/115518274/200259328-09bba52e-0e65-4ee4-b2c2-d65acca09265.png)

# C.program untuk menampilkan N pada bilangan acak yang lebih kecil dari 0,5

# > penjelasan alur program

1. <i> print ('Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5')</i> untuk menampilan atau mencetak kalimat tampilkan N bilangan acak yang lebih kecil dari 0,5

2. <i> jumlah=int(input("Masukan Jumlah N : "))</i> untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat

3. <i> import random</i> 

4. <i> for i in range (jumlah)</i> : untuk pengulangan dengan range jumlah

5. <i> print"(Data ke", 1+i,"=>", (random.uniform(0.1,0.5)))</i> untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan hasil dibawah 0.5

# D.Hasil

![Screenshot (21)](https://user-images.githubusercontent.com/115518274/200270232-770dc82f-8de5-43f8-bc69-e461bd2481e4.png)

# Latihan2
 
# Program sederhana untuk menampilkan bilangan terbesar dari N buah data yang di inputkan

# A.algoritma program untuk menampilkan bilanga terbesar dari N buah data yang di inputkan

1. mulai
2. input bilangan N
3. jika max < a maka akan lanjut pengulangan 4.jika a==0 maka akan berhenti proses pengulangan
4. dan mencetak hasil nilai maximum dari N yang di isikan
5. selesai

setelah anda mengetahui algoritma dalam sebuah program maka langkah berikutnya kita membuat flowchartnya.
berikut ini flowchart program

# B.flowchart program

![200127365-89dcd3c1-c7d1-428c-ba2a-658b2e1b83cb](https://user-images.githubusercontent.com/115518274/200272977-870fe116-646c-4b13-88a6-2c8ace3e1952.png)

# C.program untuk menampilkan bilangan terbesar dari N buah data yang di inputkan

# > penjelasan alur program

1.<i> print('menampilkan bilangan terbesar N buah data yang di inputkan')</i> untuk menampilkan kalimat <i> menampilkan bilangan terbesar dari N buah data yang diinputkan</i>

2.<i> max= 0</i> kode max disini menentukan nilai max nya adalah 0

3.<i> while true</i> : untuk perulangan hingga waktu yang tidak ditentukan atau selamanya

4.<i> a=int(input("masukkan bilangan : "))</i> a untuk menginput tipe data interger (bilangan bulat)

5.<i> if max < a max=a</i> jika max kurang dari a maka max = a

6.<i> if a==0: break</i> jika a = 0 maka akan berhenti dengan syarat break yang terpenuhi

7.<i> print("bilangan terbesar adalah :",max)</i> menampilkan bilangan terbesar adalah : Nilai maximum nya

# D.Hasil
![Screenshot (22)](https://user-images.githubusercontent.com/115518274/200284502-1849260d-737a-417a-b910-70c917c4462f.png)

# program1

# Program sederhana untuk menghitung jumlah laba hasil investasi seorang pengusaha selama 8 bulan

# A.algoritma program untuk mengitung jumlah laba hasil investasi seorang pengusaha selama 8 bulan

1. input modal misalkan x = 20.000.000 (deklarasikan)
2. input presentase untung a=0x, b=0x, c=0,01x, d=0,01x, e=0,05x, g=0,05x, h=0,03x
3. for i in range (len (t)) pengulangan
4. print ("laba bulan ke-",i+1,"sebesar:" ,t[i])
5. menghitung jumlah laba keseluruhan u=(a+b+c+d+e+f+g+h)
6. print ("total laba adalah :")

# Flowchart program1
![200127353-508830f7-7b43-4c85-b022-79dd2b9c308a](https://user-images.githubusercontent.com/115518274/200288196-ffe0539b-af54-493c-8cfa-08f04cb94a95.png)

# C.program untuk menghitung jumlah laba hasil investasi seorang pengusaha selama 8 bulan

# > Penjelasan alur program

1. <i> print ('Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan')</i> Untuk Menampilkan kalimat <i> Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan</i>

2. <i> x=20000000</i> Dengan pemisalan atau dideklarasikan x adalah 20000000

3. <i> print (" Modal Awal:",x)</i> Menampilkan kalimat <i> Modal Awal : dan data yang berisi di x yaitu 20000000</i>

4. <i> a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x</i> Untuk Mendeklarasikan presentase laba tiap bulan dan di kali dengan x atau data inputan modal investasi yaitu 20000000

5. <i> t=[a,b,c,d,e,f,g,h]</i> untuk menentukan syarat t= yang berisi a,b,c,d,e,f,g,h

6. <i> For i in range (len (t)) Print (“laba bulan ke-“,i+1,”sebesar:” ,t[i])</i> untuk perulangan data dengan isi data yaitu tdengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke untukan yang di inpput dari data t

7. <i> u= (a+b+c+d+e+f+g+h) Print (“total laba adalah:”)</i> u berisi data penjumlahan data angka yang ada didalam kode a,b,c,d,e,f,g,h yang akan di tampilakan atau dicetak di jumlah laba selama 8 bulan

# D.Hasil
![Screenshot (23)](https://user-images.githubusercontent.com/115518274/200291512-a012d0f5-1a6e-416c-bb79-2c8b9f23448e.png)

# <b> Hatur nuhun
