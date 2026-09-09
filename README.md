NIM: 260530911042

Nama: Kaisar Singgih Suta Pratama

Divisi: Cyber Security

Categori CTF : WEB EXPLOID

Tools yang berhasil di install : Ubuntu

DOKUMENTASI CHALLENGE UNDO :

<img width="1920" height="1080" alt="Screenshot (127)" src="https://github.com/user-attachments/assets/e45a7593-e7d8-41bb-b2f8-891ff695076a" />
1. Challange Undo:

Step 1 ; menggunakan  prompt base64 -d fungsinya untuk mengubah bentuk kode rahasia bernama "base64", prompt ini bertugas untuk memecahkan sandi agar kembali menjadi teks biasa

Step 2 : menggunakan command rev untuk merevers atau memutar balikan text .

Step 3 : menggunakan command tr '-' '_' untuk merubah semua simbol - menjadi _

Step 4 : menggunakan command tr '()' '{}' untuk merubah semua simbol () menjadi simbol {}

Step ke 5 / terakhir : menggunakan command tr 'a-zA-Z' 'n-za-mN-ZA-M' yang berfungsi untuk mengenkripsi atau mendekripsi teks menggunakan metode ROT13 (Rotate 13). 
Perintah ini akan menggeser setiap huruf alfabet sebanyak 13 posisi ke kanan. Karena total alfabet ada 26 huruf, jadi ketika kita menjalankan perintah ini dua kali pada teks yang sama, teks tersebut akan kembali ke bentuk aslinya.

Lalu akan menghasilkan flag berupa : picoCTF{Revers1ng_t3xt_Tr4nsf0rm@t10ns_0ea42cd0}

DOKUMENTASI CHALLENGE INTROTOBURP:

<img width="1920" height="1080" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/a2d0e618-33f7-4b05-b03c-c5bab3b5e7a9" />
Langkah 1 : Kita salin link lalu kita masuk ke tools burp

<img width="1920" height="1080" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/1d9740ab-6f1e-4e88-b5c4-d13a4773be7e" />
Langkah 2 : Setelah masuk ke tools, lalu aktifkan "intercept on" dan open browser

<img width="1920" height="1080" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/bd1596cc-c974-48f0-895d-b93fcf271683" />
Langkah 3 : Setelah sudah terbuka web tersebut, lalu kembali ke tools dan lakukan foward all

<img width="1920" height="1080" alt="Screenshot (112)" src="https://github.com/user-attachments/assets/7104ab5d-cd5b-43f2-b9e8-031776eeed59" />
Langkah 4 : Kemudian isi registrasi

<img width="1920" height="1080" alt="Screenshot (113)" src="https://github.com/user-attachments/assets/35f69219-bf80-49d5-8ddb-faf54218bb9a" />
Langkah 5 : Kembali ke tools, lakukan foward all dan kembali ke web

<img width="1920" height="1080" alt="Screenshot (114)" src="https://github.com/user-attachments/assets/51b942b6-b382-4b70-956f-95b1d9d0979b" />
Langkah 6 : Kemudian isi kode otp

<img width="1920" height="1080" alt="Screenshot (115)" src="https://github.com/user-attachments/assets/4320e8fb-7683-4b33-a49f-fecb35213484" />
Langkah 7 : Setelah mengisi kode otp, kembali ke tools lalu hapus kode otp

<img width="1920" height="1080" alt="Screenshot (116)" src="https://github.com/user-attachments/assets/5c4856e8-52e5-44fd-9e59-2cdb7f88c125" />
Langkah 8 : Setelah itu lakukan foward all dan kita akan mendapatkan hasil

<img width="1920" height="1080" alt="Screenshot (117)" src="https://github.com/user-attachments/assets/e253d476-59fe-4137-9edf-126cbcb64cf0" />

<img width="1920" height="1080" alt="Screenshot (118)" src="https://github.com/user-attachments/assets/8f3e9b6d-e3b2-4398-b24a-1a8e6fb8424b" />
Dan kita akan menemukan Flagnya seperti gambar ini :
<img width="1920" height="1080" alt="Screenshot (119)" src="https://github.com/user-attachments/assets/d1d9c378-05b7-45c5-b625-ef83ce705b77" />
