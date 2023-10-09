# Praktikum 2 CSS Dasar HTML

Nama : Dhea Dwi Adelia

NIM : 312210116

Kelas : TI.22.A.1

### Intruksi Praktikum

1. Persiapkan text editor, disini saya menggunakan sublime text.
   
2. Buat file baru dengan nama lab2_css_dasar.html
   
3. Buat struktur dasar dari dokumen HTML.
   
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
   
5. Lakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/

### Praktikum

1. Membuat dokumen HTML

   ![Screenshot (272)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/0aab7b9e-5b03-429b-ad03-c94adb7890ed)

- Maka hasil tampilan di browser sebagai berikut

  ![Screenshot (273)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/917f193b-2943-4fdf-aeeb-a0af55dad791)


2. Mendeklarasi CSS Internal
   Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.

   ![Screenshot (274)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/c2b701be-8a54-4fc8-b613-e4bf05ae8066)

- Berikut hasilnya

  ![Screenshot (275)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/0fa8fc5b-bb9b-4c04-a528-3d45f2d4f3ef)


3. Menambahkan Inline CSS
   Kemudian tambahkan deklarasi inline CSS pada tag <p> seperti berikut.

   ![image](https://github.com/adeliadhea06/Lab2Web/assets/115794875/4d34a678-4f81-4418-8b3f-8c74fb65f370)

- Berikut hasilnya

  ![Screenshot (277)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/6b231f70-0f37-48a6-92e9-f719a6ad42bd)


4. Membuat CSS Eksternal
   Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.

   ![Screenshot (278)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/50e8a03e-6a2f-4c5b-b415-e21f547f3952)

   Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head>

   ![image](https://github.com/adeliadhea06/Lab2Web/assets/115794875/c1aa3214-5fe1-4df2-b64b-fbf30a428be1)

   Selanjutnya refresh kembali browser untuk melihat perubahannya.

   ![Screenshot (280)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/81ad507e-e9e2-4e72-876a-7c65849d075a)


5. Menambahkan CSS Selector
   Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, tambahkan kode berikut.

   ![Screenshot (281)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/53cb68ce-a3ba-47b7-bf57-a0132d1dd1dd)

   Kemudian simpan kembali dan refresh browser untuk melihat perubahannya.

   ![Screenshot (282)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/06a53f32-8bfb-430b-8df1-033d803d4f54)


6. Lakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/

   ![Screenshot (284)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/72047264-5b9d-41ce-8cec-693b311f8e49)


### Pertanyaan dan tugas

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

   ![Screenshot (285)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/0f17e410-0481-4ffc-8f4e-58d3a18fb125)

   ![Screenshot (287)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/235eac80-3945-4a87-8f46-f6156dbec952)

   Pada contoh ini, terdapat elemen " <h2> dengan class "title" " dan elemen <p> dengan class "text". Class tersebut akan digunakan sebagai selector dalam CSS untuk mengubah properti dan nilai. Dalam file CSS (style.css), terdapat aturan CSS yang dideklarasikan untuk class "title" dan "text". Aturan tersebut mengubah properti "color" pada elemen dengan class tersebut. Anda dapat mengubah nilai properti "color" pada file CSS sesuai keinginan Anda untuk melihat perubahan yang terjadi pada judul (h2) dan paragraf (p) dalam hal warna teks.

3. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

   - h1 {...} : Deklarasi ini akan merubah semua elemen "h1".

   - #intro h1 {...} : Deklarasi ini lebih spesifik, maksud nya adalah pendeklarasian yang mengacu kepada pemberian atribut pada elemen "h1" dengan menambahkan id "intro".
   
5. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

   Ketika kita mendeklarasikan secara bersamaan antara INTERNAL EKSTERNAL dan INLINE yang akan ditampilkan pada Browser adalah INLINE, karena INLINE memiliki prioritas dibanding EKSTERNAL atau pun INTERNAL seperti contoh yang saya buat, saya membuat dokumen baru HTML kemudian saya buat Elemen {h1}yang kemudian saya akan deklarasikan di CSS INTERNAL EKSTERNAL dan juga INLINE Dengan property {color} dengan warna yang berbeda,jika INTERNAL {color: orange} sementara EKSTERNAL {color:aqua;} dan INLINE {color: red;} yang terpanggil dibrowser adalah INLINE karena memiliki prioritas.

   Jadi yang terpanggil adalah CSS INLINE karena memiliki prioritas tinggi dibanding CSS deklarasi lainnya.
   
7. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )

   ![Screenshot (288)](https://github.com/adeliadhea06/Lab2Web/assets/115794875/c94e52ae-a092-4d9b-8225-e6d08bc45bc1)

Yang terpanggil di browser adalah ID karena ID bersifat unik berbeda dengan Class. Class bisa digunakan banyak sementara ID hanya tertentu saja itu kenapa ID unik dan yang terpanggil di browser adalah ID.





