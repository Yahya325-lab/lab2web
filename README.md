
|Nama|NIM|Kelas|Matkul|
|----|---|-----|------|
|Yahya Ramadhan|312310401|TI.23.A4|Pemograman Web 1|

Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

![Screenshot 2024-10-05 075344](https://github.com/user-attachments/assets/2991a7b3-d5c2-44c0-8139-5ad35f6759ed)
 
 Disini saya mengubah warna dan hover dalam bagian nav nya menjadi hitam dan hovernya menjadi putih, lalu menambah properti Marquee pada
 tulisan Hello world, lalu mengubah link informasi selengkapnya menjadi tombol yang mempunyai hover, dan juga menambah efek shadow pada 
 tulisan CSS INTERNAL INLINE CSS.


 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!

Perbedaannya adalah kalau hanya menuliskan h1 saja tanpa adanya # itu tandanya elemen h1 tersebut tidak diberikan id, kalau #intro h1 
itu tandanya elemen tersebut mempunyai sebuah id. Contoh

![Screenshot 2024-10-05 080433](https://github.com/user-attachments/assets/180c2824-f16e-4ba5-a0e1-3b78b057b9d5)
semua tulisan h1 akan menjadi berwarna biru, tetapi kalau tulisan #intro yang akan berwarna merah karena gaya yang lebih spesifik dari #intro h1


3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!

Yang akan muncul dalam hasil nya adalah Inline CSS karena Inline CSS mempunyai prioritas tertinggi di antara eksternal atau internal, contoh :

![Screenshot 2024-10-05 081108](https://github.com/user-attachments/assets/35f09d20-a2e3-4f8a-b16b-279f79a4a52f)

Ini CSS nya
![Screenshot 2024-10-05 081245](https://github.com/user-attachments/assets/a93e155e-64ee-49ea-b891-746a0fe78d2c)

Maka hasil yang keluar adalah
![Screenshot 2024-10-05 081321](https://github.com/user-attachments/assets/717e8069-b315-46f1-b349-1cd834db594e)


4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya!

Ketika HTML mempunyai sebuah 2 deklarasi seperti Id dan Class, yang akan dimunculkan pada hasilnya adalah Id karena spesfisitas Id lebih tinggi dibanding
Class, contoh
![Screenshot 2024-10-05 081848](https://github.com/user-attachments/assets/08dd0846-492f-4f8e-b536-0e6953ea0b15)

CSS nya
![Screenshot 2024-10-05 081918](https://github.com/user-attachments/assets/5492b4e8-dacb-4bbb-bd88-224640f8c46c)

Hasil akhirnya
![Screenshot 2024-10-05 081950](https://github.com/user-attachments/assets/f848fe41-40de-4cd6-a53e-337af0a73e26)
