<div align="center">
  <h1 style="text-align: center;font-weight: bold">PRAKTIKUM 1<br>SISTEM OPERASI</h1>
  <h4 style="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h4>
</div>
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : </h3>
  <p style="text-align: center;">
    <strong>Marieta Nona Alfani (312350026) </strong><br>
    <strong>Ale Perdana Putra Darmawan (3123500027) </strong><br>
    <strong>Kanisius Keru Okok Dinggon(3123500028)</strong>
  </p>
<h3 style="text-align: center;line-height: 1.5">Politeknik Elektronika Negeri Surabaya<br>Departemen Teknik Informatika Dan Komputer<br>Program Studi Teknik Informatika<br>2023/2024</h3>
  <hr><hr>
</div>

## Daftar Isi
1. [Dasar Teori](#Dasar-teori)
2. [Soal](#soal)
3. [Instalasi Oracle Virtual Box](#Instalasi-Oracle-Virtual-Box)
4. [Mengkonfigurasi Debian dalam Oracle Virtual Box](#Mengkonfigurasi-Debian-dalam-Oracle-Virtual-Box)
5. [Instalasi Linux Debian dalam Oracle Virtual Box](#Instalasi-Linux-Debian-dalam-Oracle-Virtual-Box)


## Dasar teori
Pengertian Sistem Operasi:</br>
<strong>Sistem Operasi</strong> adalah perangkat lunak pada lapisan pertama yang ditempatkan pada memori komputer pada saat komputer dinyalakan booting. Sedangkan software-software lainnya dijalankan setelah sistem operasi berjalan, dan sistem operasi akan melakukan layanan inti untuk software-software itu.

## Soal
#### <h3> > Sebutkan dan jelaskan proses booting !</h3>
1. Pertama, kita menekan tombol Power komputer. Setelah komputer dihidupkan, keadaan memori masih kosong. Pada saat ini masih belum ada instruksi yang bisa dieksekusi oleh prosesor. Namun pengguna tidak perlu ikut memberi intruksi karena prosesor telah dirancang untuk mencari alamat tertentu di BIOS. Saat inilah prosesor menjalankan BIOS.

2. Kedua, BIOS mulai mengambil alih sebagai sistem operasi sementara komputer, lalu proses akan berlanjut dengan melakukan inspeksi terhadap semua kesalahan (penyebab variasi data) dalam memori, maupun Device-Device yang memang terhubung kepada komputer. Proses inilah yang sering dikenal dengan POST atau Power-On Self Test. Jika terdapat device yang bermasalah, proses tidak akan berlanjut. Tetapi memberi peringatan tentang masalah device tersebut.

3. ketiga, Proses dilanjutkan dengan BIOS mencari kartu grafis yang tertanam pada komputer dan berikutnya sistem BIOS menjalankan kartu grafis BIOS, serta pengecekan BIOS terhadap ROM.

4. Keempat, Setelah BIOS selesai melakukan pengecekan awal, BIOS akan mencari sistem operasi yang sudah diinstall lalu memuatnya pada memori serta segera menjalankannya. Kemudian, BIOS akan menjalankan sistem operasi tersebut. Jika sistem operasi mengalami error atau tidak ditemukan, BIOS akan menampilkan pesan kesalahan atau menu pilihan untuk masuk ke dalam visual BIOS.

5. Saat komputer telah diambil alih oleh sistem operasi, pengguna dapat mulai menjalankan berbagai program-program yang diinginkan.


#### Bagaimana cara install Oracle Virtual Box dan Debian dalam Virtual Box ?

## Instalasi Oracle Virtual Box
1. Masuk ke laman [Oracle Virtual box](https://www.virtualbox.org/wiki/Downloads), lalu unduh sesuai sistem operasi yang anda gunakan.
![Assets](Assets/01(1).jpeg)

2. Masuk ke laman Download sistem operasi [Debian](https://www.debian.org/download) untuk mengunduh sistem operasi Linux Debian.
   ![Assets](Assets/debian.02.png)

3. Buka setup Oracle dan klik Next.
   ![Assets](Assets/21.jpeg)

4. Dalam menu tidak ada yang perlu diubah, klik Next.
   ![Assets](Assets/22.jpeg)

5. Klik Yes.
   ![Assets](Assets/23.jpeg)

6. Klik Install.
   ![Assets](Assets/24.jpeg)

7. Oracle Virtual Box telah di install, klik finish.
   ![Assets](Assets/25.jpeg)

## Instalasi Linux Debian dalam Oracle Virtual Box
1. Buka Oracle Virtual Box, lalu klik opsi "New".
![Assets](Assets/06.jpeg)

2. Isi nama, pilih letak penyimpanan Virtual Box, masukkan file ISO debian yang telah diunduh, klik "Skip unattended Installation, dan klik Next.
   ![Assets](Assets/07.jpeg)

3. Isi Username dan hostname dan ubah password, untuk domain name tidak perlu diganti, lalu klik Next. 
   ![Assets](Assets/11.jpeg)

4. Tentukan RAM dan jumlah CPU yang diinginkan, lalu klik Next.
   ![Assets](Assets/05.jpeg)

5. Tentukan ukuran storage didalam Virtual Machine, lalu klik Next.
   ![Assets](Assets/10.jpeg)

6. Dalam tampilan ini, anda dapat melihat ulang pilihan yang anda telah pilih sebelumnya, jika sudah sesuai keinginan, pilih Finish.
   ![Assets](Assets/13.jpeg)

## Mengkonfigurasi Debian dalam Oracle Virtual Box
1. Klik "Start" untuk membuka Virtual Machine.
![Assets](Assets/12.jpeg)

2. Pilih Graphical Install untuk memulai konfigurasi Debian.
   ![Assets](Assets/15.jpeg)

3. Pilih Bahasa, lalu klik continue.
   ![Assets](Assets/14.jpeg)

4. Pilih lokasi, lalu klik continue.
   ![Assets](Assets/17.jpeg)

5. Pilih konfigurasi bahasa Keyboard, lalu klik continue.
   ![Assets](Assest/18.jpeg)

6. Isi Hostname, lalu klik continue.
   ![Assets](Assets/19.png)

7. Untuk nama domain tidak perlu diisi, klik continue.
   ![26.png](26.png)

9. Isi root password, lalu klik continue.
   ![27.png](27.png)

10. Isi nama, lalu klik continue.
    ![28.png](28.png)

11. Isi username, lalu klik continue.
    ![29.png](29.png)

12. Pilih lokasi jam, lalu klik continue.
    ![30.png](30.png)

13. Untuk partition disk, pilih manual, lalu klik continue.
    ![31.png](31.png)

14. Pilih opsi seperti pada gambar dibawah, lalu klik continue.
    ![32.png](32.png)

15. Pilih "Yes" untuk membuat partition disk baru, lalu klik continue.
    ![33.png](33.png)

16. Pilih pri/log untuk membuat bagian partition disk, lalu klik continue.
    ![34.png](34.png)


17. Pilih "create new partition disk" untuk membuat partition disk, lalu klik continue.
    ![35.png](35.png)

18. Tentukan jumlah penyimpanan partition disk pertama, lalu klik continue.
    ![36.png](36.png)

19. Pilih "primary" agar menjadikan penyimpanan utama, lalu klik continue.
    ![37.png](37.png)

20. Pilih "beginning", lalu klik continue.
    ![38.png](38.png)


21. pilih opsi "done setting up the partition" klik continue.
    ![39.png](39.png)

22. Setelah membuat partition disk pertama, silahkan membuat partition disk ke dua, tentukan isi penyimpanan yang ukurannya lebih kecil dibandingkan partition disk pertama, lalu klik continue.
    ![40.png](40.png)


23. Untuk partition disk kedua, pilih opsi logical dan pada mount point pilih Enter manually dan ketik "/storage", lalu klik continue.
    ![41.png](41.png)

24. Setelah membuat partition disk kedua, silahkan membuat partition disk ke tiga, tentukan isi penyimpanan yang ukurannya lebih kecil dibandingkan partition disk kedua, lalu klik continue.
    ![42.png](42.png)

25. Untuk partition disk kedua, pilih opsi logical, lalu jadikan "swap area" pada bagian "use as:", lalu klik continue.
    ![43.png](43.png)

26. Cek ulang seperti gambar dibawah, jika sudah sesuai, klik continue.
    ![44.png](44.png)
    
28. Pilih opsi "Yes", lalu klik continue.
    ![45.png](45.png)

29. Pilih opsi "no", lalu klik continue.
    ![46.png](46.png)

30. Pilih lokasi terdekat untuk mengunduh package manager, lalu klik continue.
    ![47.png](47.png)

31. Pilih archive mirror, lalu klik continue.
    ![48.png](48.png)
    
33. Pada bagian ini tidak perlu diisi, klik continue
    ![49.png](49.png)

35. Pilih opsi "Yes", lalu klik continue.
    ![50.png](50.png)

37. Pilih opsi "/dev/sda", lalu klik continue.
    ![51.png](51.png)
    
39. Instalasi dan konfigurasi Debian telah selesai, klik continue dan Virtual machine akan me-reboot. 
    ![52.png](52.png)
    
41. Tampilan Linux Debian setelah reboot.
    ![53.png](53.png)
<!---
kanisiusdinggon/kanisiusdinggon is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
