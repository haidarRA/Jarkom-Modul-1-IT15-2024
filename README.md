# Jarkom-Modul-1-IT15-2024

## ***KELOMPOK IT15***
| Nama      | NRP         |
  |-----------|-------------|
  | M. Abhinaya Al Faruqi | 5027231011  |  
  | Haidar Rafi Aqyla | 5027231029   |

**Advance Sanity Check:**
1.	Pertama cek http.request.method == “POST” untuk mengetahui apa aja yang login
 ![image](https://github.com/user-attachments/assets/d795753d-9826-4962-ba80-5c200006dcf3)
2.	Bisa kita lihat ada 3 percobaan login terdapat 2 yang salah satu yang benar namun untuk yang benar password tersebut disamarka 
![image](https://github.com/user-attachments/assets/04faad69-03f9-4482-9351-b649c3d67ccb)
3.	Setelah kita lihat lagi terdapat keanehan atau pesan yang menyebutkan untuk cek kembali peraturan soal shift 
![image](https://github.com/user-attachments/assets/6d655fea-43e5-4595-af50-041b68ecb463)
4.	Setelah kita lihat terdapat string yang harus di decode terlebih dahulu, setelah kita decode kata tersebut berubah menjadi “penword”
5.	Untuk mendapatkan flagnya kita harus masuk ke nc 10.15.42.60 44000
6.	Pertanyaan pertama adalah username pengirim dan jawabannya sesuai yang kita lihat di wireshark yaitu “JaneD03”
7.	Pertanyaan kedua apa nama file yang dikirim?, jawabannya “Clue3.txt” 
![image](https://github.com/user-attachments/assets/5955dce7-28c7-4041-a499-0490f0179169)
8.	Dan pertanyaan terakhir adalah string kita dapatkan di petunjuk sebelumnya dan kita akan mendapatkan flag tersebut JarkomIT{8uK4n_S4n1ty_b1a5A_WV7asIzALcxpBRSx8b4EHLkoWSu5Nhm6TvQaMHkW6ExMdrS1TzYiwIKK}

**Illegal Breakthrough:**
1.	Untuk pertanyaan yang pertama siapa ip dari korban untuk mengetahuinya kita hanya perlu menganalisis dari wireshark “172.21.88.207” 
![image](https://github.com/user-attachments/assets/7beb25d2-3562-4729-9170-482cf69dce3c)
2.	Pertanyaan kedua prot yang digunakan sebagai web server “1917” 
![image](https://github.com/user-attachments/assets/e3f2a820-0ca1-4e40-8ef1-428f71d28410)
3.	Pertanyaan ketiga endpoint yang terdapat login “/ww1.php” 
![image](https://github.com/user-attachments/assets/ed5ac796-7894-40b5-a051-7ef569c55777)
4.	Pertanyaan keempat tools yang digunakan attacker “ffuf-v2.1.0-dev” 
![image](https://github.com/user-attachments/assets/54cc3abe-c799-4633-892a-108cd819bbb8)
5.	Pertanyaan kelima kredensial yang berhasil digunakan oleh attacker “Redbaron:fly1ng4c3” 
![image](https://github.com/user-attachments/assets/152f5537-658e-404d-a872-29fc3ac210ad)
6.	Flag nya JarkomIT{d34th_fr0m_th3_sky_c0jXLj8m8kv60EsiSkDX9AEu6H1ShaRlkmZVjFW3u4ISVbCV2qlTWW1}

**Ftp Login:**
1.	Username yang berhasil digunakan untuk login “sn34ky” 
![image](https://github.com/user-attachments/assets/b8df6f36-a16d-4a36-8391-c5405c631fa0)
2.	Password yang berhasil digunakan untuk login “”sup3rsn1ff3r”
3.	Flagnya JarkomIT{n0t_s0_s3cur3_ftp_0YF03fBoSAn1y72F2YDp404ZEL0oFoQLiXBdzjPJQ0iTkNSibiJXG1N}

**Packet Barrage:**
1.	Ini sama seperti soal yang ilegal breakthrough namun pertanyaan pertamanya apa ip dari attacker “172.21.80.1”
2.	Pertanyaan kedua berapa total attempt dari bruteforce attacker “1917” 
![image](https://github.com/user-attachments/assets/c73ff422-614d-42de-b52a-28a0f09307c2)
3.	Apa nama file yang didownload oleh attacker “Albatros.txt” 
![image](https://github.com/user-attachments/assets/cb061a0a-ceea-4110-ace2-9b0c669fae25)
4.	Apa isi file yang disisipkan oleh attacker “Der Rote Kampfflieger” 
![image](https://github.com/user-attachments/assets/3198859b-b4a7-43ec-a5bd-3f6041e964fa)
5.	Flagnya JarkomIT{th3_fly1ng_c1rcus_0f_w4r_2359oDRNDReqGnfW07k1S8sJ25Stvy1wtJls8fs1iqvjBExZNMehMACE}

**Surprise:**
1.	Service apa yang digunakan ftp server tersebut “vsFTPd 3.0.3” 
![image](https://github.com/user-attachments/assets/127a6cce-4663-4e31-aa86-9fe68446f5bc)
2.	Apa nama file yang dikirm oleh attacker “g0tcha.cpp” 
![image](https://github.com/user-attachments/assets/541e8284-4513-4d21-adbd-e7809d0b5d87)
3.	Apa pesan rahasia yang ditinggalkan oleh attacker? “g0tchu n0w l1ttl3 m0us3” 
![image](https://github.com/user-attachments/assets/7f7fae7f-3dbe-41cc-86c0-0ca11d55abef)
4.	Setelah itu kita mendapatkan flagnya

**Pegawai Negeri Sebelah:**
1.	Pertama kita download dahulu file csv nya  
![image](https://github.com/user-attachments/assets/981fca5a-6669-4037-ab17-3cc037bdbba8)
2.	Pertanyaan pertama siapa yang memiliki password berikut “nNnM%coQuF”? Vero Tampubolon 
![image](https://github.com/user-attachments/assets/d553b4fa-0c75-4342-b24f-aae699aaf8f9)
3.	Apa jabatan dari Taufan Kuswandari? Analis Kebijakan 
![image](https://github.com/user-attachments/assets/1b9c76aa-5cfe-43bc-9e4c-16b1537baf72)
4.	Siapa yang paling awal di list? Cici mustofa  
![image](https://github.com/user-attachments/assets/855e517f-6743-47fe-a4da-dc85694fa1a1)
5.	Apa password di akhir list? RyxaJPv^yF
6.	Setelah kita menjawab semua soal melalui file csv yang telah kita download kita akan mendapatkan flagnya

**EZ:**
1.	Temukan jawaban dari log tersebut? jawabannya jawaban 
![image](https://github.com/user-attachments/assets/5012a8a6-7ede-445e-877b-c1fe24c6e876)
2.	Port berapa yang digunakan service tersebut? 1234 
![image](https://github.com/user-attachments/assets/f2792235-7d2a-4ec1-9a92-643acc737cef)
3.	Setelah itu kita dapat flagnya

**Rizzset:**
1.	 ![image](https://github.com/user-attachments/assets/bf006e65-ebd9-4dc6-abdb-aed1b12cfef4)
2.	 ![image](https://github.com/user-attachments/assets/8aa6e645-ebcf-4c8a-ace8-04c88c73794c)
3.	 ![image](https://github.com/user-attachments/assets/31b5817a-aa2c-48b6-9a93-4cc91761417a)
4.	 ![image](https://github.com/user-attachments/assets/623ffa98-60bb-4397-9a90-6bacf575d6c5)

**Corporate Breach:**
1.	Untuk yang pertama, harus mencari nama dari attacker. Di sini, digunakan filter frame contains “name” untuk mencari tahu nama dari attacker.
![image](https://github.com/user-attachments/assets/39ed21f7-e76a-4fad-a314-a59bb906c8db)
Setelah menggunakan filter, ada satu packet yang beda dari yang lain. Untuk mencari tahu isinya, menggunakan Follow -> HTTP Stream.
![image](https://github.com/user-attachments/assets/455dbb4e-e4e4-44b1-8f61-21e39e2371fc)
Nama dari attacker adalah Nakhimov.
2.	Untuk mencari email yang digunakan attacker untuk login, maka digunakan filter http.
![image](https://github.com/user-attachments/assets/6c1d796c-51e1-430d-96f9-e17aa527eb2a)
![image](https://github.com/user-attachments/assets/32278d94-5b07-43ee-9f2f-a26546ff9c45)
Di sini, dapat dilihat ada pola yang berulang. Untuk setiap packet HTTP dengan POST request berisi email dan password yang dimasukkan oleh attacker dan packet selanjutnya (HTTP/1.1 200 OK) berisi halaman HTML setelah login dan kebanyakan isinya adalah “Invalid email or password”. Oleh karena itu, dicari packet HTTP/1.1 yang beda dari yang lain.
![image](https://github.com/user-attachments/assets/888c6d9f-fc67-40be-aaac-7638566918f0)
Ternyata ada packet yang beda dari yang lain karena packet HTTP/1.1 ini tidak ada “Invalid email or password” di isi informasinya. Dengan asumsi bahwa attacker telah berhasil mengakses sebuah akun, dilihat packet sebelumnya.
![image](https://github.com/user-attachments/assets/3754c9da-9630-47bf-9ed5-c9bcee30c69b)
![image](https://github.com/user-attachments/assets/47abbb5f-042f-48f1-9dd3-d7c6a400a1c6)
Email yang digunakan penyerang adalah jarkomsupport@gmail.com.
3.	Untuk password yang digunakan penyerang adalah j4rk0mg4c0rbg.
![image](https://github.com/user-attachments/assets/2824dca6-09e2-401f-8b1c-220e4547ca65)


**Malicious Code**
1.	Untuk mencari banyak attempt dir listing yang dilakukan oleh attacker, digunakan filter frame contains “GET”.
![image](https://github.com/user-attachments/assets/aed3aeff-db48-41a7-9574-cbb0f9292cf1)
![image](https://github.com/user-attachments/assets/4142e890-0c20-4b32-a568-63d77070ae45)
Dari stream index packet pertama dan terakhir, dapat disimpulkan bahwa attacker melakukan dir listing sebanyak 52 kali.
2.	Untuk mencari endpoint yang berhasil didapatkan attacker  untuk login page, kembali lagi ke penyelesaian pertanyaan kedua dari challenge Corporate Breach.
![image](https://github.com/user-attachments/assets/e1db2333-c5a9-4463-8156-79967d6f5996)
Karena biasanya endpoint ada di packet dengan POST Request, maka endpointnya adalah /index.php.
3.	Untuk mencari tahu berapa kali attempt login yang dilakukan attacker hingga berhasil, dilihat attempt awal sampai attacker berhasil mendapatkan akses akun dengan email jarkomsupport@gmail.com.
![image](https://github.com/user-attachments/assets/d9e3b196-add1-4bcb-b45b-00af216b91dd)
![image](https://github.com/user-attachments/assets/7c2d2f70-f6c7-40d0-8e88-581fa2d7ce5e)
Dari stream index kedua packet, dapat disimpulkan bahwa attacker melakukan attempt login sebanyak 153 kali.
4.	Untuk mengetahui pertanyaan dari attacker, digunakan filter ip.src == 172.21.80.1 && http.
![image](https://github.com/user-attachments/assets/1c4699f5-d7b9-4806-8cde-78bc9e7e875b)
Di packet di atas, attacker ingin memberikan sebuah pertanyaan ke kita. Oleh karena itu, dilihat packet selanjutnya
![image](https://github.com/user-attachments/assets/059c4f6f-02f3-4d4b-94f6-71cc017e751b)
![image](https://github.com/user-attachments/assets/a466e895-8700-4cd7-8b43-b695d7fa3717)
Setelah melihat packet selanjutnya, didapatkan urutan angka 9711297321199711411097321029711811111410511632112101109981179711632991049710810810111010310163324010410511011658321151191019711610111441 yang jika dipisah akan menjadi urutan ASCII:
97 112 97 32 119 97 114 110 97 32 102 97 118 111 114 105 116 32 112 101 109 98 117 97 116 32 99 104 97 108 108 101 110 103 101 63 32 40 104 105 110 116 58 32 115 119 101 97 116 101 114 41
Jika di-decode, didapatkan pertanyaan berikut.
![image](https://github.com/user-attachments/assets/801b0a58-bfe6-4121-998d-6a1ecf794ca3)
Pertanyaan yang didapat adalah apa warna favorit pembuat challenge (nevarrawr)? dengan hint sweater. Karena Mas Aji suka memakai sweater merah, maka jawabannya adalah merah.
![image](https://github.com/user-attachments/assets/4032dbf6-0273-4326-9532-ef5e1ed2c115)

**Gajah Terbang (Server Recon)**
1.	Untuk mencari DBMS yang digunakan, menggunakan keyword seperti sql untuk mencari database yang mungkin dapat ditemukan.
![image](https://github.com/user-attachments/assets/f97ffd4e-6675-41cc-964b-4cdfcff24ac8)
Di sini, dapat dilihat ada protokol PGSQL, yang merupakan inisial dari PostgreSQL.
2.	Menggunakan capture pada nomor 1, ada beberapa packet dengan informasi 65520 -> 6969 dan sebagainya yang artinya DBMS tersebut berjalan di port 6969.
3.	Untuk mencari tahu sistem operasi yang berjalan, dapat melihat salah satu packet yang telah di-filter.
![image](https://github.com/user-attachments/assets/822d83df-904d-4a97-81b8-329274a3ece1)
![image](https://github.com/user-attachments/assets/d05450d2-1cb5-4ed2-873a-b1380f4d538e)
Di sini, dapat dilihat bahwa sistem operasi yang digunakan adalah Debian.
4.	Merujuk ke gambar sebelumnya, kredensial username DBMS yang digunakan adalah s1gm4.
5.	Untuk mencari nama dari database yang digunakan, digunakan filter frame contains "s1gm4".
![image](https://github.com/user-attachments/assets/75e1967e-d577-431f-97af-c283429af882)
Nama dari databasenya adalah sigmaskibidigyatrizzzz.
6.	Merujuk pada gambar sebelumnya, ada 4 user, yaitu Jojo Hermawan, Kevin Anugerah, Siska Awikwok, dan Kunto Aji.
7.	Untuk mencari user admin, dilihat lagi isi dari packet sebelumnya.
![image](https://github.com/user-attachments/assets/45d0c530-8cda-4d28-9478-2467d5f7d9e4)
Di sini, ada query SQL SELECT * FROM users WHERE role = ‘admin’ dengan hasil querynya adalah Jojo Hermawan dengan email jojohermawan@gmail.com.
8.	Jika dilihat gambar sebelumnya, password dari user Jojo Hermawan adalah c93ccd78b2076528346216b3b2f701e6 yang masih dalam bentuk hash MD5. Setelah dilakukan MD5 reverse, didapatkan passwordnya adalah admin1234.
![image](https://github.com/user-attachments/assets/8da77c42-d9f5-44e6-89dd-3a18b6939c2a)
 

**Stegography**
1.	Untuk menghitung jumlah file yang dikirim, dapat menggunakan filter frame contains “png”.
![image](https://github.com/user-attachments/assets/da3a5750-72c7-491f-bfce-51bf0511277c)
Dari packet yang telah di-filter, ada 13 file yang dikirim.
2.	Untuk mencari file gambar yang memiliki pesan, dapat menggunakan program reversed.py.
![image](https://github.com/user-attachments/assets/c80e4102-7e61-4665-a913-1a712239b36a)
Untuk mencari pesan tersembunyi dalam file, cukup mengganti “filename.extantion” menjadi path dari file yang ingin dicari pesan rahasianya.
![image](https://github.com/user-attachments/assets/6bb61e25-1377-4dad-8ae6-b2e59e9e5976)
Untuk mencari pesannya urut sesuai dengan urutan file yang ada. Sehingga, file yang memiliki pesan adalah ATP, EH, dan KJK.
3.	Untuk pesan - pesan yang didapat, ada nawalhap, nanamaek, dan rebis. Jika dibalik, maka kata - kata tersebut akan menjadi pahlawan, keamanan, dan siber yang jika digabung akan menghasilkan pesan pahlawan keamanan siber.
![image](https://github.com/user-attachments/assets/49067dfb-1c7f-45b7-b423-a0f71ae72669)

**Gajah Terbang (Attacker Recon)**
1.	Untuk mencari akun email dari penyerang, kita harus menganalisis query - query yang ada di packet yang sudah digunakan di challenge Gajah Terbang (Server Recon).
![image](https://github.com/user-attachments/assets/b44d06e3-c1a0-45c8-9128-f16961da297f)
Di sini, dapat dilihat bahwa ada yang ingin memberikan akses admin ke user dengan ID 3 dan unband user ID 3. Artinya, akun email penyerang adalah kuntoajiisrillll@gmail.com.
2.	Password yang digunakan penyerang adalah aa1cbddbb1667f7227bcfdb25772f85c yang jika menggunakan teknik MD5 reverse akan didapatkan password kissme.
3.	Untuk melihat kapan akun penyerang di-ban, dapat melihat gambar sebelumnya.
![image](https://github.com/user-attachments/assets/220256d4-24e2-4963-8646-82137ec3a9f9)
Dapat disimpulkan bahwa akun penyerang di-ban pada tanggal 2024-06-09 (format YYYY-MM-DD).
4.	Untuk table yang dimodifikasi penyerang, dengan merujuk pada gambar sebelumnya, tabel yang diubah adalah tabel users dan banned_users.
5.	Untuk daftar produk ada di tabel products.
![image](https://github.com/user-attachments/assets/d8b09a21-5737-4e07-905d-244e46083f0c)
Di tabel products, terdapat beberapa produk, yaitu rokok, teh botol, telur, es krim, dan permen (urutan ID dari 1 sampai 5). Dan di tabel transaction, penyerang membeli barang dengan ID 1 dan 4 yang artinya penyerang membeli rokok dan es krim.
6.	Dari tabel products, harga rokok adalah 18000 dan harga es krim adalah 6500. Jika dijumlahkan, total transaksi penyerang adalah 24500.
![image](https://github.com/user-attachments/assets/d1696c70-d036-4759-842a-3eff9c946191)

**innerRCE**
1.	Untuk mencari tahu kapan hacker berhasil mengupload webshell, digunakan filter http.request.method == POST.
![image](https://github.com/user-attachments/assets/00c5c751-f8ed-4d6f-b637-599b3ccdc999)
Untuk melihat lebih lanjut detailnya, bisa menggunakan Follow -> HTTP Stream.
![image](https://github.com/user-attachments/assets/2d4d8014-b3b2-49d6-b176-f5ecde7c99a5)
Di sini, dapat dilihat bahwa webshell berhasil dikirim pada 2024-09-16 06:18:05 GMT atau 2024-09-16 13:18:05 WIB.
2.	Untuk mencari endpoint yang rentan, dapat dilihat di gambar sebelumnya. Dari gambar sebelumnya, didapatkan endpoint tersebut adalah /upload.php.
Sedangkan untuk  server yang rentan, dapat digunakan filter frame contains “server”.
![image](https://github.com/user-attachments/assets/03fa149f-9371-4796-a82a-cbdf1bad6c00)
![image](https://github.com/user-attachments/assets/d517b763-8f0e-49f4-a381-91af727a1b0c)
Di sini, dapat dilihat bahwa server yang rentan adalah server-app.
Jadi, untuk endpoint dan server yang rentan adalah /upload.php_server-app.
3.	Untuk mencari nama dari file webshell, dapat digunakan filter http.request.method == POST.
![image](https://github.com/user-attachments/assets/b6843bb5-d530-4574-860f-ad2460fc9c5e)
Nama dari webshellnya adalah idzoyyshell.php.
4.	Untuk mencari command pertama yang dijalankan pada webshell, dapat digunakan filter http.request.method == GET.
![image](https://github.com/user-attachments/assets/da17c98e-f17e-43d0-b099-504082e9843f)
Di sini, dapat dilihat bahwa command yang pertama kali dijalankan adalah whoami.
5.	Dengan menggunakan filter yang sama seperti soal sebelumnya, terdapat sebuah command echo, yaitu %22echo%20cGxzIHJhdGUgc29hbCBpbmkK%20|%20base64%20-d%22 yang jika menggunakan proses URL decode akan didapatkan:
"echo cGxzIHJhdGUgc29hbCBpbmkK | base64 -d"
Jika dijalankan di bash:
![image](https://github.com/user-attachments/assets/9d9db8c4-4dc2-44e9-ab2d-71b764149265)
Didapatkan string pls rate soal ini.
![image](https://github.com/user-attachments/assets/8e87ee1b-bab8-4e35-8817-557b8ae4cbe6)

**Adult Hengker**
1.	Untuk mencari device yang digunakan, dapat melihat secara detail packet dengan frame GET DESCRIPTOR Response CONFIGURATION.
![image](https://github.com/user-attachments/assets/4cb34423-a615-4a24-97ea-69e8c425d0d3)
Untuk device yang digunakan adalah Mouse.
2.	Untuk mencari pesan dari USB HID yang diberikan, yang pertama adalah menggunakan filter usb.src == 1.1.1.
![image](https://github.com/user-attachments/assets/792ac1db-8f96-4042-938c-f7fefd541f4a)
Selanjutnya, bisa dipilih detail HID Data pada detail packet dan menggunakan Apply as Column.
![image](https://github.com/user-attachments/assets/0939ad6d-8655-4693-ba64-f40385ef2ee8)
Setelah menambahkan HID Data sebagai kolom, dapat diekspor menjadi CSV.
![image](https://github.com/user-attachments/assets/42459e86-fd21-46f5-a33e-b45ab49fcb70)
Untuk menyaring data HID, dapat menggunakan command bash cut -d’,’ -f7 adulthengker.csv | tr -d ‘ “ ‘.
![image](https://github.com/user-attachments/assets/08ad0290-31da-4414-8803-10a5e2fcbd77)
Setelah mendapatkan semua data HID, dapat diekstrak lagi datanya menggunakan CyberChef.
![image](https://github.com/user-attachments/assets/78428fe2-7021-4ca5-a6e1-7ccb4bcedf64)
Untuk hasilnya dapat di-copy ke sebuah program Python untuk menghasilkan gambar dari kumpulan data HID mouse.
![image](https://github.com/user-attachments/assets/1bec3576-f468-41b5-96c5-6fc6b98db05d)
Setelah data HID dimasukkan, program Python dapat dijalankan.
![image](https://github.com/user-attachments/assets/136ab901-875a-4614-bcb0-265cea06d348)
Setelah dijalankan, akan dihasilkan sebuah gambar.
![image](https://github.com/user-attachments/assets/04cf9f7c-06d7-4d9d-8103-aaaaac1975da)
Tulisan yang ada di gambar adalah HALO MAS KEVIN SALKEN.
![image](https://github.com/user-attachments/assets/3ef527b3-e0fb-42f0-a246-3640d2ea78c3)

**LINK VIDEO DEMO REVISI**
https://youtu.be/dMjiRgat5To
