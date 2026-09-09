NIM: 260530911042

Nama: Kaisar Singgih Suta Pratama

Divisi: Cyber Security

Categori CTF : WEB EXPLOID

Tools yang berhasil di install : Ubuntu

DOKUMENTASI :

<img width="1920" height="1080" alt="Screenshot (127)" src="https://github.com/user-attachments/assets/e45a7593-e7d8-41bb-b2f8-891ff695076a" />
1. challange undo:

step 1 ; menggunakan  prompt base64 -d fungsinya untuk mengubah bentuk kode rahasia bernama "base64", prompt ini bertugas untuk memecahkan sandi agar kembali menjadi teks biasa

step 2 : menggunakan command rev untuk merevers atau memutar balikan text .

step 3 : menggunakan command tr '-' '_' untuk merubah semua simbol - menjadi _

step 4 : menggunakan command tr '()' '{}' untuk merubah semua simbol () menjadi simbol {}

step ke 5 / terakhir : menggunakan command tr 'a-zA-Z' 'n-za-mN-ZA-M' yang berfungsi untuk mengenkripsi atau mendekripsi teks menggunakan metode ROT13 (Rotate 13). 
Perintah ini akan menggeser setiap huruf alfabet sebanyak 13 posisi ke kanan. Karena total alfabet ada 26 huruf, jadi ketika kita menjalankan perintah ini dua kali pada teks yang sama, teks tersebut akan kembali ke bentuk aslinya.

Lalu akan menghasilkan flag berupa : picoCTF{Revers1ng_t3xt_Tr4nsf0rm@t10ns_0ea42cd0}

