# Jarkom-Modul-1-IT35-2024

| Nama          | NRP          |
| ------------- | ------------ |
| RM Novian Malcolm Bayuputra | 5027231035 |
| Nayyara Ashila | 5027231083 |

## 1. Advance Sanity Check
Soal pertama kita diminta untuk memasukkan username, pada bagian kanan bawah kalau di scroll ketemu username nya yaitu JaneD03

![Screenshot 2024-09-18 194357](https://github.com/user-attachments/assets/94cf0324-a66e-47c8-b445-ef47a73be808)


![image](https://github.com/user-attachments/assets/3bcda38c-4109-40c6-8fb2-099075627bf3)

Kemudian jika kita scroll ke bawah lagi maka akan ketemu filenya dengan format yang sesuai dengan yang diminta yaitu `clue3.txt` dan karena kita diminta untuk mencari hidden word dari ppt praktikum yaitu `cGVud29yZA==` setelah saya coba translate maka keluar hasilnya `penword` seperti foto dibawah

![image](https://github.com/user-attachments/assets/bf8d95a9-3e5f-4d76-abd7-0b35b497ee86)

Setelah mengisi kata tersebut maka flag nya muncul ```JarkomIT{8uK4n_S4n1ty_b1a5A_NG6mtQVcQR8S3xkzYnhemX5DDSu5gHEDT2i8FqhR7m0QPf4VyMn5OIKK}``` seperti foto dibawah


![image](https://github.com/user-attachments/assets/8b0caf60-2864-4ee3-8fac-721a0ec12762)


## 2. Illegal Breakthrough
Pada soal ini karena kita diminta untuk memasukkan ip address maka bisa dilihat yaitu ip nya `172.21.88.207` kemudian apabila dilihat port yang dipakai `1917`
Disini terdapat nama dan password yang benar apabila di scroll, karena sebelumnya kebanyakan yang berisi username dan password salah

![Screenshot 2024-09-18 224803](https://github.com/user-attachments/assets/38dd42d4-59a2-45b2-b561-0139994bfdeb)

Maka setelah saya masukkan username sesuai ketentuan dan juga kredensial nya ketemu flagnya ```JarkomIT{d34th_fr0m_th3_sky_eVLCFiVmEs6ivZzSBLaOjIlX7H1UD2hdgdRRynPVvJz7RhUag1nuWW1}``` seperti foto dibawah

![image](https://github.com/user-attachments/assets/21fd6998-12cb-433d-b1a7-9a7f1e07a63c)

![image](https://github.com/user-attachments/assets/9e992541-3be2-4968-828b-d0a1be201fe3)


## 3. Pegawai Negeri Sebelah
Maka ketemu flagnya yaitu ```JarkomIT{Tum8eN_p45SnYa_Ku4t_B1aS4Nya_wEsBuGICvKvgGn8UdXxWV7R8QL3Pdkf13GT79rrbrNvxGDZj2XlHM4h}```

![image](https://github.com/user-attachments/assets/1e41cf63-c377-4d7b-b563-432ea3fa4733)

## FTP Login
Maka ketemu flagnya ```JarkomIT{n0t_s0_s3cur3_ftp_7YYw3gFIH8alHPCxsqhlKVctGL0yOQsuJ5BZ3govZ1YTV9JrfiMgG1N}``` 
![image](https://github.com/user-attachments/assets/f94d31de-814e-4388-b9a3-51bf6e18cea6)

## 4. EZ
Maka ketemu flagnya ```JarkomIT{BiAr_aman_Pake_sSh_qulMxGpPKZSPwAThtIYoz9mmF3zheXysRaYPzoNosL6rJMBs6kZ0EZ}```
![image](https://github.com/user-attachments/assets/66e7d72e-a9b2-4a76-a925-36213dd8737f)

## 5. Surprise
Maka ketemu flagnya ```JarkomIT{l1ttl3_m0us3_1n_th3_h0us3_vtEF19Ky4LQuzaQNbNyeAqVSRG0b7grUqihe9dOn4NAn9FRS5kWWTCHU}```
![image](https://github.com/user-attachments/assets/581d11eb-644d-4d5d-a83a-2968f9eecc87)

## 6. Corporate Breach
Maka ketemu flagnya ```JarkomIT{supp0rt_k0k_l3m4h_bg_OQdBDF2AA2DBAnJswpq0prn63G6RpMVNpvrEDtwbW2HYW2Lzsy4oG6}```
![image](https://github.com/user-attachments/assets/2e1c36f6-ba01-44a0-b501-bdeece632ff4)

## 7. Gajah Terbang (Server Recon)
Awalnya kita diminta untuk memasukkan DBMS yang digunakan bisa didapatkan dari melihat PGSQL nya, kemudian port yg digunakan bisa dilihat di wireshark nya dan setelah saya coba memasukkan `6969` berhasil, kemudian pertanyaan yang lain seperti email, password, database juga didapatkan dari informasi seperti foto dibawah.
Untuk pertanyaan password, kita diharuskan untuk decode dari kode yang diberikan dari awalnya `c93ccd78b2076528346216b3b2f701e6` setelah saya decode menjadi `admin1234`

![Screenshot 2024-09-18 225950](https://github.com/user-attachments/assets/256e4551-e619-415a-a6f3-d2588116ac59)


![Screenshot 2024-09-18 230354](https://github.com/user-attachments/assets/2bc16bea-923e-439d-abda-f4036d0f2cb6)

Maka ketemu flagnya ```JarkomIT{Gy4tT_M5g_4U_lpokFThhxI2J6va3hogx1NFb15k1JbRMKXppQAsg8IndqhVCwneZABiD1}``` 

![Screenshot 2024-09-18 230336](https://github.com/user-attachments/assets/a32b2d92-d8b4-45af-9751-234a2bb4d36a)

### 8. Gajah Terbang (Attacker Recon)
Pertanyaan pertama saya mencoba memasukkan akun kunto aji, kemudian berhasil. Karena kita diminta untuk memasukkan password tetapi password nya harus di decode dari `aa1cbddbb1667f7227bcfdb25772f85c` menjadi `kissme`. Pertanyaan yang lain juga berdasarkan informasi yang ada. Untuk menghitung transaksi tinggal ditambah harga rokok dan eskrim yang tercantum sehingga menjadi 24.500.

![Screenshot 2024-09-18 232536](https://github.com/user-attachments/assets/fa654932-3f84-4f91-90b4-22902f8bb963)

Maka ketemu flagnya ``` JarkomIT{G4jaH_K0k_t3RbaNG_LeQuu8Zh476F8FOdm1DXnblAuYntqED4yRb8OLjnDIQpGdVLh50FrKt5}```

![Screenshot 2024-09-18 232512](https://github.com/user-attachments/assets/46955747-119e-41a6-aca0-7260e583d5c7)

### 9. Packets Barrage
Pertanyaan pertama dapat dilihat dari source

![image](https://github.com/user-attachments/assets/34c2d44f-4285-4830-aeb5-c8a23e3de8fc)

Pertanyaan kedua dapat dilihat dari stream

![image](https://github.com/user-attachments/assets/f5fa3b9e-cfac-45d5-993f-c4644ae1a953)

Pertanyaan ketiga didapatkan dengan mendownload file Regex.zip lalu mengekstraknya

![Screenshot 2024-09-18 222943](https://github.com/user-attachments/assets/db0af7c4-e82d-484e-a165-fe8058a5d4a3)

Pertanyaan keempat didapatkan dengan membuka file Albatros.txt

![Screenshot 2024-09-18 223009](https://github.com/user-attachments/assets/c6f2de1a-6d1d-41c1-bcc1-fcecd984c0e5)

Flag

![Screenshot 2024-09-18 223040](https://github.com/user-attachments/assets/77450f79-6a77-48ad-b360-574f3ffb90a9)

### 10. Rizzset

Pertanyaan pertama didapat dari membaca dari wireshark, pertanyaan selanjutnya dapat terjawab jika menjalankan jarm dengan domain www.its.ac.id

![Screenshot 2024-09-18 231155](https://github.com/user-attachments/assets/d012f9a2-3f29-469e-b318-5f26f3cf5763)
