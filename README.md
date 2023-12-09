# Tugas PBO 1
## Nama : Ahmad Afif Nurdiantoro
## NPM  : G1F022077

### 1. Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:(https://github.com/randiijulian/randiijulian/assets/81604461/e32b6d92-7e3a-4323-a0e3-711009112c8e)

- **Source Code** :  
```
for i in range(1, 101):
    if i % 10 == 0:
        for _ in range(3):
            print("Ahmad Afif Nurdiantoro")
    else:
        print(i)

```
 - **Output :** 
![alt text](/img/loop.png?raw=true)

 - **Penjelasan :** 

1. ```for i in range(1, 101):```: Inisiasi loop "for" yang akan mengulangi kode sebanyak 100 kali, dimulai dari nilai 1 hingga 100.

2. ```if i % 10 == 0:```: Ini adalah kondisi if yang memeriksa apakah nilai variabel i habis dibagi 10 (memiliki sisa nol).

3. ```for _ in range(3)  print("Ahmad Afif Nurdiantoro")```:  Ini adalah loop for kedua yang akan dijalankan tiga kali (range(3)) jika kondisi ifnya bernilai true. maka akan mencetak Nama saya sebanyak 3x.

4. Jika kondisi pada langkah 2 tidak terpenuhi (nilai i bukan kelipatan 10), maka blok else akan dijalankan: ```print(i)```

## 2 Buatlah program bebas, dengan menerapkan if else pada: a. For Loops b. While Loops
***a. For Loops***

 - **Source Code :** 
```
def cek_nilai(ulangan):
    for nilai in ulangan:
        if nilai >= 70:
            print(f"Nilai {nilai} lulus.")
        else:
            print(f"Nilai {nilai} tidak lulus.")

nilai_ulangan = [65, 80, 45, 90, 60]

cek_nilai(nilai_ulangan)

```

 - **Output :**
 ![alt text](/img/for_loop.png?raw=true)

 - **Penjelasan :**
1. ```def cek_nilai(ulangan):``` : Mendefinisikan fungsi bernama ```cek_nilai``` yang menerima satu parameter yaitu ```ulangan```. 

2. ```if nilai >= 70:``` : Ini adalah kondisi ```if``` yang memeriksa apakah nilai tersebut lebih besar atau sama dengan 70.

3. ```print(f"Nilai {nilai} lulus.")```:Jika nilai lebih besar atau sama dengan 70, maka bernilai true dan mencetak pesan bahwa nilai tersebut lulus.

4. ```print(f"Nilai {nilai} tidak lulus.")```:Jika nilai kurang dari 70, maka bernilai false dan mencetak pesan bahwa nilai tersebut tidak lulus.

5. ```nilai_ulangan = [65, 80, 45, 90, 60]``` : Mendefinisikan list nilai_ulangan yang berisi nilai-nilai ujian.

6. ```cek_nilai(nilai_ulangan)``` : Memanggil fungsi cek_nilai dengan menggunakan list nilai_ulangan sebagai argumen


***b. while Loops***

- **Source Code :**
```
def cek_nilai(ulangan):
    i = 0
    while i < len(ulangan):
        nilai = ulangan[i]
        if nilai >= 70:
            print(f"Nilai {nilai} lulus.")
        else:
            print(f"Nilai {nilai} tidak lulus.")
        i += 1

# Memasukkan beberapa nilai ulangan untuk diuji
nilai_ulangan = [65, 80, 45, 90, 60]

cek_nilai(nilai_ulangan)

```

- **Output :** 
![alt text](/img/while_loop.png?raw=true)

- **Penjelasan :**

1.  ```def cek_nilai(ulangan):``` : Mendefinisikan fungsi bernama ```cek_nilai``` yang menerima satu parameter yaitu ```ulangan```. 

2. ```i = 0``` :Inisiasi variabel i dengan nilai 0. Variabel ini akan digunakan sebagai indeks untuk mengakses nilai dalam list.

3. ```while i < len(ulangan):``` : Memulai loop while yang akan berlanjut selama nilai i lebih kecil dari panjang list ulangan.

3. ```if nilai >= 70:``` : Ini adalah kondisi ```if``` yang memeriksa apakah nilai tersebut lebih besar atau sama dengan 70.

4. ```nilai_ulangan = [65, 80, 45, 90, 60]``` : Mendefinisikan list nilai_ulangan yang berisi nilai-nilai ujian.

5.  ```cek_nilai(nilai_ulangan)``` : Memanggil fungsi cek_nilai dengan menggunakan list nilai_ulangan sebagai argumen


## 3. Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for

- **Source Code :**
```
# Mendefinisikan variabel array (list)
array = ['G', 1, 'F', 0, 2, 2, 0, 7, 7]

for npm in array:
    print(npm)


```

- **Output :**

![alt text](/img/array_npm.png?raw=true)

- **Penjelasan :**

1. ```array = ['G', 1, 'F', 0, 2, 2, 0, 7, 7]```: Inisialisasi variabel array sebagai list yang berisi karakter dan angka NPM "G", 1, "F", 0, 2, 2, 0, 7, 7. List adalah struktur data yang dapat menyimpan beberapa nilai dalam satu variabel.

2. ```for npm in array:``` Menggunakan loop for untuk mengiterasi melalui setiap elemen dalam list array.

3. ```print(npm)``` Mencetak nilai dari variabel npm ke layar pada setiap iteras