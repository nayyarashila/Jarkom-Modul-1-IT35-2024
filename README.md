# Jarkom-Modul-1-IT35-2024

| Nama          | NRP          |
| ------------- | ------------ |
| RM Novian Malcolm Bayuputra | 5027231035 |
| Nayyara Ashila | 5027231083 |

# Modul 1


## 1. Advance Sanity Check
-Soal pertama kita diminta untuk memasukkan username, pada bagian kanan bawah kalau di scroll ketemu username nya yaitu JaneD03

![Screenshot 2024-09-18 194357](https://github.com/user-attachments/assets/94cf0324-a66e-47c8-b445-ef47a73be808)

-Soal kedua kita diminta nama file, jika di scroll ketemu nama filenya `clue3.txt` sesuai format soal

![Screenshot 2024-09-20 230314](https://github.com/user-attachments/assets/9c7c7f83-dcbf-4c11-8452-31a3360658bb)

-Soal ketiga apabila dilihat di stream yg sama ada hint `lihat peraturan soal shift ada surprise` seperti dibawah

![Screenshot 2024-09-20 230801](https://github.com/user-attachments/assets/be68a992-0cdf-4a85-8a00-682b61d2d613)

Setelah dilihat ketemu code `cGVud29yZA== `

![Screenshot 2024-09-21 011655](https://github.com/user-attachments/assets/9bc46918-42ba-46c7-8c29-0b081be8893d)

Kemudian decode maka keluar hasilnya ``penword``

![Screenshot 2024-09-20 231337](https://github.com/user-attachments/assets/7b136bde-938a-44b9-8b67-acbc8867c312)


Setelah mengisi kata tersebut maka flag nya muncul ```JarkomIT{8uK4n_S4n1ty_b1a5A_NG6mtQVcQR8S3xkzYnhemX5DDSu5gHEDT2i8FqhR7m0QPf4VyMn5OIKK}``` 
seperti foto dibawah


![image](https://github.com/user-attachments/assets/8b0caf60-2864-4ee3-8fac-721a0ec12762)


## 2. Illegal Breakthrough

-Pada soal ini karena kita diminta untuk memasukkan ip address maka bisa dilihat yaitu ip nya `172.21.88.207`.

![image](https://github.com/user-attachments/assets/97790d2b-5b97-4e83-8f9e-35d9e6ccaeb2)

-kemudian soal selanjutnya ditanyakan port apabila dilihat port yang dipakai `1917` sesuai isi stream nya

![image](https://github.com/user-attachments/assets/86078002-7b25-4713-9046-f8864828a4bc)

-Kemudian soal selanjutnya ditanyakan endpoint pada login bisa dilihat disini

![image](https://github.com/user-attachments/assets/bce9a992-8866-4697-b074-5a9bc89366e5)

-Soal selanjutnya Tools apa yang digunakan oleh attacker, bisa dilihat disini tapi setelah saya coba isi ternyata masih salah dan saat dicoba singkat namanya kemudian version, maka berhasil `ffuf-v2.1.0-dev`

![Screenshot 2024-09-20 233153](https://github.com/user-attachments/assets/b8f0fa8b-f277-4497-95e2-ce60094d013e)

-Kemudian soal terakhir diminta masukkan nama dan password yg benar yaitu `username=Redbaron&password=fly1ng4c3` dengan format sesuai soal
Disini terdapat nama dan password yang benar apabila di scroll di ``tcp.stream eq 1917`` karena sebelumnya kebanyakan yang berisi username dan password salah

![Screenshot 2024-09-20 234038](https://github.com/user-attachments/assets/f24287d7-fd44-4156-b917-5fc210cec99e)


Maka setelah saya masukkan username sesuai ketentuan dan juga kredensial nya ketemu flagnya ```JarkomIT{d34th_fr0m_th3_sky_eVLCFiVmEs6ivZzSBLaOjIlX7H1UD2hdgdRRynPVvJz7RhUag1nuWW1}``` seperti foto dibawah

![image](https://github.com/user-attachments/assets/21fd6998-12cb-433d-b1a7-9a7f1e07a63c)

![image](https://github.com/user-attachments/assets/9e992541-3be2-4968-828b-d0a1be201fe3)


## 3. Pegawai Negeri Sebelah
-Soal pertama kita diminta Siapa yang memiliki password nNnM%coQuF? yaitu `Vero Tampubolon,nNnM%coQuF,Kepala Bidang`

![Screenshot 2024-09-21 000004](https://github.com/user-attachments/assets/b6b18c58-8426-4c57-bed8-a64ac28c7ec5)

-Soal kedua Apa jabatan dari Taufan Kuswandari? yaitu `Analisis Kebijakan`

![image](https://github.com/user-attachments/assets/4971b1fa-2ef2-4b9f-a92c-365d240c83ab)

-Soal ketiga Siapa yang paling awal di list? yaitu `Cici Mustofa`

![image](https://github.com/user-attachments/assets/8263937c-b036-44ff-b2d0-3d84a526ec23)

-Soal terakhir Apa password paling akhir dari list? yaitu `RyxaJPv^yF`

![image](https://github.com/user-attachments/assets/c4270488-e9a0-4f39-bb9d-48e3da68af62)


Maka ketemu flagnya yaitu ```JarkomIT{Tum8eN_p45SnYa_Ku4t_B1aS4Nya_wEsBuGICvKvgGn8UdXxWV7R8QL3Pdkf13GT79rrbrNvxGDZj2XlHM4h}```

![image](https://github.com/user-attachments/assets/1e41cf63-c377-4d7b-b563-432ea3fa4733)


## 4. FTP Login
Pertama kita cari stream dengan status login successfull yaitu di 

![image](https://github.com/user-attachments/assets/6ca93244-61b0-492a-84e8-91d9540a2c38)

-Soal pertama username yg berhasil login? yaitu `sn34ky`

![image](https://github.com/user-attachments/assets/9bf47b3d-a276-4c52-a458-ae84ec6bde39)

-Soal kedua password apa yang digunakan utk login? yaitu `sup3rsn1ff3r`

![image](https://github.com/user-attachments/assets/e34e43fc-96ca-432e-a1cc-d87b451ee0fc)

Maka ketemu flagnya ```JarkomIT{n0t_s0_s3cur3_ftp_7YYw3gFIH8alHPCxsqhlKVctGL0yOQsuJ5BZ3govZ1YTV9JrfiMgG1N}``` 
![image](https://github.com/user-attachments/assets/f94d31de-814e-4388-b9a3-51bf6e18cea6)


## 5. EZ
Pertama kita coba analyze > follow > tcp kemudian ditanya

-Soal pertama ditanya Temukan jawaban dari log tersebut, setelah di scroll ketemu yaitu `jawabannya jawaban`

![image](https://github.com/user-attachments/assets/0f5921eb-5cac-43ea-9ba6-10a0a66d84ee)

-Soal kedua ditanya port yang digunakan, dan apabila diihat bagian bawah maka terlihat portnya `1234`

![image](https://github.com/user-attachments/assets/e9d36389-b2f7-4f08-8a11-b4037be4f32b)

Maka ketemu flagnya ```JarkomIT{BiAr_aman_Pake_sSh_qulMxGpPKZSPwAThtIYoz9mmF3zheXysRaYPzoNosL6rJMBs6kZ0EZ}```

![image](https://github.com/user-attachments/assets/66e7d72e-a9b2-4a76-a925-36213dd8737f)


## 6. Surprise
-Soal pertama Apa service yang digunakan pada FTP server? yaitu `vsFTPd 3.0.3` karena apabila kita tcp > follow yang keluar dengan format sama seperti soal yg paling atas

![image](https://github.com/user-attachments/assets/cc353a1f-e60d-450a-b993-f1263fe95da7)

-Soal kedua Apa nama file yang dikirim oleh attacker? yaitu `g0tcha.cpp` karena setelah saya scroll yang memiliki format extension hanya file tsb

![image](https://github.com/user-attachments/assets/a1a0be94-4ea7-445d-81f5-4849fcfc87f0)

-Soal ketiga Apa pesan rahasia yang ditinggalkan oleh attacker? awalnya krn file tsb dalam c++ jadi saya coba 
ctrl + F > g0tcha.cpp dan setelah di scroll keluar code dalam bahasa c

![image](https://github.com/user-attachments/assets/d18ff3f9-f016-45f9-ac03-ba511777fd00)

kemudian saya jalankan di compiler maka keluar pesan `g0tchu n0w l1ttl3 m0us3`

![image](https://github.com/user-attachments/assets/4b5ef54b-cda5-4cfd-b2df-2195c8bcb61d)


Maka ketemu flagnya ```JarkomIT{l1ttl3_m0us3_1n_th3_h0us3_vtEF19Ky4LQuzaQNbNyeAqVSRG0b7grUqihe9dOn4NAn9FRS5kWWTCHU}```
![image](https://github.com/user-attachments/assets/581d11eb-644d-4d5d-a83a-2968f9eecc87)


## 7. Corporate Breach
-Soal pertama Siapa nama attacker? setelah kita scroll maka ketemu namanya yaitu `Nakhimov` 

![image](https://github.com/user-attachments/assets/ecf5ebd2-7285-42bd-b36b-347963068639)

-Soal kedua Apa email yang digunakan untuk login? yaitu terletak di stream 108 dengan email `jarkomsupport@gmail.com`

![image](https://github.com/user-attachments/assets/5ea41e5b-0c73-4757-980f-3dce112ce46e)

-soal ketiga Apa password yang digunakan untuk login? yaitu `j4rk0mg4c0rbg`

![image](https://github.com/user-attachments/assets/67b1969d-09ff-4486-860e-d2201fffe284)


Maka ketemu flagnya ```JarkomIT{supp0rt_k0k_l3m4h_bg_OQdBDF2AA2DBAnJswpq0prn63G6RpMVNpvrEDtwbW2HYW2Lzsy4oG6}```
![image](https://github.com/user-attachments/assets/2e1c36f6-ba01-44a0-b501-bdeece632ff4)


## 8. Gajah Terbang (Server Recon)
-Soal pertama Apa DBMS yang digunakan pada server tersebut? kemudian kalau di scroll PGSQL itu banyak jadi saya coba masukkan ternyata benar yaitu `PostgreSQL`

![image](https://github.com/user-attachments/assets/73e0a32a-8b79-4156-a0a9-a7bbe4f6afc7)

-Soal kedua Di port berapa DBMS server tersebut berjalan? kemudian kalau dilihat port `6969` itu banyak digunakan sehingga saya coba masukkan ternyata benar

-Soal ketiga OS apa yang digunakan untuk server tersebut? yaitu `Debian` 

-Soal keempat Apa credentials username DBMS valid yang digunakan? yaitu `s1gm4`

![Screenshot 2024-09-21 114442](https://github.com/user-attachments/assets/5a5060f2-de99-4317-9f26-a0486963511b)

-Soal kelima Apa nama database yang digunakan? yaitu `sigmaskibidigyatrizzzz`

![image](https://github.com/user-attachments/assets/cbd98b61-b7a7-44b7-87dc-1d7bd4afb83a)

-Soal keenam Ada berapa banyak users dalam database tersebut? yaitu ada `4`

![image](https://github.com/user-attachments/assets/3f7604fb-d688-455a-b6fb-4ebece56fe26)

-Soal ketujuh Apa email yang digunakan oleh admin? yaitu `jojohermawan@gmail.com.`

![image](https://github.com/user-attachments/assets/80354909-021d-4f44-8c0f-380ddd5eb993)

-Soal kedelapan Apa password yang digunakan oleh admin? yaitu `c93ccd78b2076528346216b3b2f701e6` 

![image](https://github.com/user-attachments/assets/c274b2d9-9180-45d5-9803-f11f6500d054)

Karena harus decode jadinya `admin1234` adalah password

![Screenshot 2024-09-18 230354](https://github.com/user-attachments/assets/2bc16bea-923e-439d-abda-f4036d0f2cb6)


Maka ketemu flagnya ```JarkomIT{Gy4tT_M5g_4U_lpokFThhxI2J6va3hogx1NFb15k1JbRMKXppQAsg8IndqhVCwneZABiD1}``` 

![Screenshot 2024-09-18 230336](https://github.com/user-attachments/assets/a32b2d92-d8b4-45af-9751-234a2bb4d36a)


## 9. Gajah Terbang (Attacker Recon)
-Soal pertama Akun apa yang dimiliki oleh penyerang dalam database tersebut, berikan emailnya! saya coba masukkan akun kunto aji krn dia adalah user yg terkena banned dengan id akunnya adalah 3 ternyata benar `kuntoajiisrillll@gmail.com`

![image](https://github.com/user-attachments/assets/80fe8e8e-dff0-4a1d-9232-d576ff4ee3bd)

-Soal kedua Apa password yang digunakan oleh penyerang? yaitu `aa1cbddbb1667f7227bcfdb25772f85c` sehingga setelah decode keluar `kissme`

![image](https://github.com/user-attachments/assets/d43d6016-fdaf-4c8c-82c9-3f2eaf2c6ab1)

-Soal ketiga Pada tanggal berapa akun penyerang diban? yaitu `2024-06-09`

![image](https://github.com/user-attachments/assets/922e4b00-90a8-45bd-a2c8-cf065108fe6d)

-Soal keempat Table apa saja yang dimodifikasi oleh penyerang? yaitu` users dan banned_users` karena yang di update tabel tsb

![image](https://github.com/user-attachments/assets/8b3727e4-2ed4-410e-bc69-6d2dce17281a)

-soal kelima Barang apa saja yang telah dibeli oleh penyerang? yaitu `rokok dan es krim`

![image](https://github.com/user-attachments/assets/2467717b-994a-41e3-8e2f-dac83b4c9dcb)

-soal keenam Berapa total transaksi dari barang yang dibeli oleh penyerang? yaitu `24500` karena dari hasil penambahan harga rokok dan es krim

![image](https://github.com/user-attachments/assets/93ffc7b2-c000-4172-96f9-1f516fccb6aa)


Maka ketemu flagnya ``` JarkomIT{G4jaH_K0k_t3RbaNG_LeQuu8Zh476F8FOdm1DXnblAuYntqED4yRb8OLjnDIQpGdVLh50FrKt5}```

![Screenshot 2024-09-18 232512](https://github.com/user-attachments/assets/46955747-119e-41a6-aca0-7260e583d5c7)


## 10. Packets Barrage
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

## 11. Rizzset

Pertanyaan pertama didapat dari membaca dari wireshark, pertanyaan selanjutnya dapat terjawab jika menjalankan jarm dengan domain www.its.ac.id

![Screenshot 2024-09-18 231155](https://github.com/user-attachments/assets/d012f9a2-3f29-469e-b318-5f26f3cf5763)

## 12. Malicious Code

Pertanyaan pertama didapat dari memfilter frame yang berisi GET

![image](https://github.com/user-attachments/assets/814c76cd-febc-46bf-afa9-1e1036a5bf6a)

Pertanyaan kedua didapat dari GET terakhir yang dilakukan

![Screenshot 2024-09-18 231659](https://github.com/user-attachments/assets/409a0213-c71d-4bbd-b3d7-da4fb9fdbb0c)

Pertanyaan ketiga didapat dari attempt terakhir yaitu di stream 207 dikurangkan dengan 54 yaitu stream terakhir sebelum attempt pertama

![Screenshot 2024-09-18 232446](https://github.com/user-attachments/assets/5ff90e3d-6b8c-4595-a1f4-0846b1afd855)

Pertanyaan keempat didapat dengan decode ASCII ke TEXT

![image](https://github.com/user-attachments/assets/ca5e990f-b44f-4241-ae84-4f69c8eaba28)

![Screenshot 2024-09-18 233540](https://github.com/user-attachments/assets/0c261c71-7393-4453-9bb3-f7b6698b4554)

Flag

![Screenshot 2024-09-18 233554](https://github.com/user-attachments/assets/713be9e1-ec41-4b67-a336-3421931c30c0)

## 13. Stegography

Pertanyaan pertama didapat dari memfilter frame yang berisi PNG

![Screenshot 2024-09-18 234022](https://github.com/user-attachments/assets/5afbe138-9d55-4c3d-b3b7-e16be61f19b5)

Pertanyaan kedua didapat dari mendownload 13 gambar yang tersedia lalu menjalankan reverse.py yang disediakan oleh soal

![Screenshot 2024-09-19 000449](https://github.com/user-attachments/assets/dfb5636a-5a7a-47de-a438-9c15c05baa41)

Pertanyaan ketiga didapat dengan menyusun anagram dan didapat flagnya

![Screenshot 2024-09-19 000435](https://github.com/user-attachments/assets/612ebbaf-7ee4-4e03-b459-e7468b46f10f)

## 14. 22 Nightmare

Pertanyaan pertama didapat dari mengecek stream

![Screenshot 2024-09-19 001521](https://github.com/user-attachments/assets/daab76cf-8c97-4007-a058-30a2af6dcf89)

Pertanyaan kedua didapat dari mendownload jpg lalu membuka isinya

![Screenshot 2024-09-19 003640](https://github.com/user-attachments/assets/58fafb8c-8017-4da7-a8cd-27faaa81e124)

Pertanyaan ketiga didapat dari mengecek stream

![Screenshot 2024-09-19 003805](https://github.com/user-attachments/assets/64374c9d-81c1-4903-8009-fb4debe04daf)

Pertanyaan keempat didapat dari stream ke-142 dimana binernya dikonversi ke UTF lalu di XOR kan dengan key NUN

![Screenshot 2024-09-19 004510](https://github.com/user-attachments/assets/1835719e-ff30-4c7d-89d0-e56af720335f)

![Screenshot 2024-09-19 004500](https://github.com/user-attachments/assets/3a47bcbe-cd3b-400b-9c25-d4f1abb37110)

Flag

![Screenshot 2024-09-19 004529](https://github.com/user-attachments/assets/3f159dd1-7ddf-4f8f-94f4-4ad19ecda001)

## 15. inneRCE

Pertanyaan pertama didapat dari mengecek frame yang berisi "shell" lalu dicek arrival timenya

![image](https://github.com/user-attachments/assets/3013b3db-f6e4-4f1f-8882-99647fe5097f)

Pertanyaan kedua didapat dari mengecek dari stream

![Screenshot 2024-09-19 023057](https://github.com/user-attachments/assets/b2a4dfb4-18f2-4e91-a03c-2b3687fe66c3)

Pertanyaan ketiga juga dapat diselesaikan dari gambar di atas

Pertanyaan keempat dapat dijawab dengan melihat urutan waktu dari frame yang berisi "shell"

![image](https://github.com/user-attachments/assets/f0724a4a-a5d9-4989-9aef-43089b595e09)

Pertanyaan kelima didapat dari mengecek base64 yang diecho 

![image](https://github.com/user-attachments/assets/c5f7e81d-f8ca-4c36-bcf9-8b273e1de806)

![image](https://github.com/user-attachments/assets/ea876b8f-324c-4867-a26d-2b7e41d4afb9)

Flag

![image](https://github.com/user-attachments/assets/7437d0e4-3278-4dca-8aa6-9ecd80b2e305)


