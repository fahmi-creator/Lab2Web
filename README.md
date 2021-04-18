# Lab2Web
# Praktikum 2 - pemrograman web (CSS Dasar)
```
Fahmi Abdul Muthi
311910463
TI.19.A2
```
# Langkah 1
membuat sebuah dokumen sebagai berikut.
![21](https://user-images.githubusercontent.com/56380765/114503465-8efd8800-9c57-11eb-8bcf-83e8bc016c85.png)
# Langkah 2
mendeklarasikan CSS internal dalam bagian ```<head>``` dokumen
![22](https://user-images.githubusercontent.com/56380765/114503688-e6035d00-9c57-11eb-856c-eee8bd027389.png)
# Langkah 3
mendeklarasikan inline CSS pada paragraf atau tag ```<p>```
![23](https://user-images.githubusercontent.com/56380765/114503887-3084d980-9c58-11eb-8961-9aab14272ca0.png)
# Langkah 4
Membuat CSS eksternal dan menambahkan tag ```<link>``` pada bagian ```<head>``` dalam dokumen html untuk memuat dokumen css eksternal tersebut
![24](https://user-images.githubusercontent.com/56380765/114504081-78a3fc00-9c58-11eb-94c5-add4b704d111.png)
# Langkah 5
Menambah CSS Selector dengan menggunakan ID dan Class Selector pada dokumen css eksternal.
![251](https://user-images.githubusercontent.com/56380765/114504377-fa942500-9c58-11eb-8121-89e38c6ee6da.png)

# Pertanyaan dan tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
![tugas1](https://user-images.githubusercontent.com/56380765/115134859-16733e80-a03e-11eb-922e-0ff216dfb129.png)
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
```
CSS elemen h1 mengubah tampilan seluruh elemen yang mempunyai tag h1, sedangkan intro h1 hanya dapat mengubah tampilan elemen h1 yang mempunyai id #intro.
```
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
```
mendeklarasikan CSS secara internal, lalu ditambahkan dengan CSS eksternal dan inline CSS pada elemen yang sama namun hasilnya deklarasi yang berbeda, maka hasilnya semua deklarasi pada CSS tersebut akan ditampilkan. Disini saya mencoba untuk menambahkan deklarasi font-style dan font-size pada CSS secara internal dan menambahkan deklarasi text-align pada inline CSS serta menambahkan border-style dan border-color pada CSS eksternal.
```
![no3](https://user-images.githubusercontent.com/56380765/115135011-60105900-a03f-11eb-90fa-a335bcac637a.png)
![gambar3](https://user-images.githubusercontent.com/56380765/115135025-774f4680-a03f-11eb-8c28-1c3f2e9e29fe.png)

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf">
jadi Kedua deklarasi tersebut akan tampil, namun selector ID yang akan tampil jika deklarasinya ada yang sama antara ID dan Class.
![no4](https://user-images.githubusercontent.com/56380765/115135118-fe042380-a03f-11eb-9a5b-853e17e4f985.png)
