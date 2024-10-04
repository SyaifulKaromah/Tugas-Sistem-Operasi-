[←    BACK](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/README.md)

# Tugas 6
## Informasi Mahasiswa
**Nama: M. Syaiful Karomah**\
**NIM: 090112823828111**\
**Kelas: SK3C**
<br>
<div align="Center">
  
## Praktikum 5

</div>

## Soal 1
**Eksekusi seluruh profile yang ada :**  
### A. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut :
  > echo "Profile dari /etc/profile

**Jawab:**
- edit file profile
  
  > nano /etc/profile

- isi dengan 'echo "Profile dari /etc/profile"

  ![1a.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1a.2.png)

- Masuk mode root
- tampilkan dengan kode berikut

  ![1a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1a.1.png)

<br>

### B. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :
   /home/stD02001/.bash_profile  
   /home/. stD02001/.bash_login  
   /home/mahasiswa/.profile  
   /home/mahasiswa/.bashrc  

Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile :  
  > echo “Profile dari .bash_profile”  

Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang bersangkutan.  

**Jawab:**
- Buat file ".bash_profile" pada user "syf"
  > cd syf
  
  > sudo nano .bash_profile

    ![1b.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1b.1.png)

- Tulis "echo "Profile dari .bash_profile"
  ![1b.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1b.2.png)

- Buat file ".bash_login"
  > sudo nano .bash_login
  
    ![1b.3](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1b.3.png)

- Tulis "echo "Profile dari .bash_login"
  ![1b.4](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1b.4.png)

- Pindah user "mahasiswa"
  > su - mahasiswa

- Buat file ".profile"
  > nano .profile

    ![1b.5](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1b.5.png)

- Tulis "echo "Profile dari .profile"
  ![1b.6](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1b.6.png)

- Buat file ".bashrc"
  > nano .bashrc
  
    ![1b.7](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1b.7.png)

- Tulis "echo "Profile dari .bashrc"
  ![1b.8](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1b.8.png)

<br>

### C. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:
  > $ su mahasiswa  

  > $ exit  

kemudian gunakan opsi – sebagai berikut :  
  > $ su – mahasiswa  
  
  > $ exit  

Jelaskan perbedaan kedua utilitas tersebut.

**Jawab:**
**Metode tanpa "-":**
- cek posisi
  > pwd

- switch user
  > su mahasiswa
  
- cek posisi
  > pwd

- exit
  > exit

    ![1c.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1c.1.png)

**Metode dengan "-"**
- cek posisi
  > pwd

- switch user
  > su - mahasiswa
  
- cek posisi
  > pwd

- exit
  > exit

    ![1c.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1c.2.png)

**Perbedaan kedua utilitas**
- su target:
  - Menggunakan perintah ini akan mengganti pengguna saat ini ke pengguna target, tetapi tetap berada di shell saat ini. Ini berarti variabel lingkungan (environment variables) seperti PATH tidak akan berubah.
  - Contoh: su john akan mengganti pengguna saat ini ke john, tetapi tetap menggunakan shell dan lingkungan yang sama.
- su - target:
  - Menambahkan tanda minus (-) setelah su akan mengganti pengguna saat ini ke pengguna target dan juga memuat lingkungan pengguna baru tersebut. Ini berarti variabel lingkungan akan diatur ulang sesuai dengan pengguna baru.
  - Contoh: su - john akan mengganti pengguna saat ini ke john dan memuat lingkungan pengguna john, seperti jika pengguna john baru saja login.

<br>
<br>

## Soal 2
**Prompt String (PS)**  
### Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan 
parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell  
  > PS1=‟> „  
  
  > export PS1

**Jawab:**
- Edit file ".bash_profile"
  > nano .bash_profile

  ![2a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/2a.1.png)

- Tulis dengan:
  > PS1=‟> „  
  
  > export PS1
    
    ![2a.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/2a.2.png)

### b.  Eksperimen hasil PS1 : 
  > $ PS1=“\! > “  

  > 69 > PS1=”\d > “  

  > Mon Sep 23 > PS1=”\t > “  

  > 10:10:20 > PS1=”Saya=\u > “  
  
  > Saya=mahasiswa > PS1=”\w >”  

  > ~ > PS1=\h >” 

**Jawab:**
- Tampilkan nomor perintah dari history
  > PS1=“\! > “

- Tmapilkan tanggal
  > PS1=”\d > “

- Tampilkan waktu
  > PS1=”\t > “

- Tampilkan username
  > PS1=”Saya=\u > “

- Tampilkan direktori saat ini
  > PS1=”\w >”

- tampilkan nama host
  > PS1=\h >”

    ![2b.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/2b.1.png)

<br>
<br>

## Soal 3
**Logout**  
### Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout  
  > Echo “Terima kasih atas sesi yang diberikan”  

  > Sleep 5  

  > clear  

**Jawab:**
- edit file ".bash_logout"
  > nano .bash_logout

- ketik:
  > Echo “Terima kasih atas sesi yang diberikan”  

  > Sleep 5  

  > clear
  
    ![3a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/3a.1.png)

- Uji coba
  ![3a.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/3a.2.png)

- Setelah 5 detik, terminal akan dibersihkan
  ![3a.3](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/3a.3.png)

<br>
<br>

## Soal 4
**Bash Script**
### a.  Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :  
  - p1.sh  
    > #! /bin/bash  
    > echo “Program p1”  
    > ls –l  
  - p2.sh  
    > #! /bin/bash  
    > echo “Program p2”  
    > who  
  - p3.sh  
    > #! /bin/bash  
    > echo “Program p3”  
    > ps x 

**Jawab:**
- Buat file "p1.sh
  > nano p1.sh

    ![4a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.1.png)

- Ketik dengan:
  > #! /bin/bash  
  
  > echo “Program p1”  
  
  > ls –l

    ![4a.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.2.png)

- Buat file "p2.sh
  > nano p2.sh
  
    ![4a.3](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.3.png)

- Ketik dengan:
  > #! /bin/bash  
  
  > echo “Program p1”  
  
  > who
    
    ![4a.4](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.4.png)

- Buat file "p3.sh
  > nano p3.sh
  
    ![4a.5](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.5.png)

- Ketik dengan:
  > #! /bin/bash  
  
  > echo “Program p1”  
  
  > who
  
    ![4a.6](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.6.png)

<br>

### b.  Jalankan script tersebut sebagai berikut :  
  > $  ./p1.sh ; ./p3.sh ; ./p2.sh  

  > $  ./p1.sh &  
  
  > $  ./p1.sh $ ./p2.sh & ./p3.sh &  
  
  > $  ( ./p1.sh ; ./p3.sh ) & 

**Jawab:**
- Jalankan script pertama:
  > ./p1.sh ; ./p3.sh ; ./p2.sh
  
    ![4b.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4b.1.png)

- Jalankan script kedua:
  > ./p1.sh &
  
    ![4b.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4b.2.png)

- Jalankan script ketiga:
  > ./p1.sh $ ./p2.sh & ./p3.sh &
  
    ![4b.3](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4b.3.png)

- Jalankan script keempat:
  > ( ./p1.sh ; ./p3.sh ) &
  
    ![4b.4](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4b.4.png)

<br>
<br>

## Soal 5
**Jobs**
### a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.
  > #!/bin/bash  

  > while [ true ]  
  
  > do  

  > date >> hasil  

  > sleep 10  
  
  > done

**Jawab:**
- Buat file baru "pwaktu.sh"
  > nano pwaktu.sh

- Ketik dengan:
  > #!/bin/bash  

  > while [ true ]  
  
  > do  

  > date >> hasil  

  > sleep 10  
  
  > done
  
    ![5a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/5a.1.png)

<br>

### b.  Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background sebagai berikut :
  > $ jobs  
  
  > $ find / -print > files 2>/dev/null &  

  > $ jobs  

**Jawab:**
- Jalankan program sebagai background
  > ./pwaktu.sh &

- Lihat jobs
  > jobs

- jalankan program find:
  > find / -print > files 2>/dev/null &

- Lalu lihat jobs:
  > jobs

    ![5b.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/5b.1.png)

<br>

### c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background  
  > $ fg %1  

  > $ bg  

**Jawab:**
- Menjadikan program ke 1 sebagai foreground
  > fg %1

- Lalu tekan **Ctrl+Z** untuk menghentikan program itu sementara, atau kembali ke background dalam keadaan stopped

- Lalu lanjutkan kembali program yang terhenti sementara tersebut:
  > bg
  
    ![5c.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/5c.1.png)

<br>

### d.  Stop program background dengan utilitas kil
  > $ ps x  
  > $ kill [Nomor PID]

**Jawab:**
- Menampilkan daftar proses yang berjalan
  > ps x
  
    ![5d.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/5d.1.png)

- Menghentikan proses pwaktu.sh
  > kill  10444
  
    ![5d.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/5d.2.png)

<br>
<br>

## Soal 6
**History**
### a. Ganti nilai HISTSIZE dari 1000 menjadi 20  
  > $ HISTSIZE=20  

  > $ h 

**Jawab:**
- Ganti nilai Ukuran History:
  > HISTSIZE=20

- tampilkan history:
  > history
  
    ![6a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6a.1.png)

<br>

### b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir dilakukan  
  > $ !-5 

**Jawab:**
> !-5

  ![6b.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6b.1.png)

<br>

### c. Ulangi instruksi yang terakhir.  Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer  
  > $ !!

 **Jawab:**
 - Jalankan perintah !!
 - > !!

- Tekan **Ctrl+P** untuk mengambil kode sebelumnya

  ![6c.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6c.1ctrl%2Bp.png)

_ Tekan **Ctrl+N** juga untuk mengambil kode, jadi kosong karena kode sebelummya menampilkan HISTSize=20, setelah kode tersbut tidak ada, jadi kosong

![6c.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6c.2ctrl%2Bn.png)

<br>

### d.  Ulangi instruksi pada history bufer nomor 150  
  > $ !150

**Jawab:**
- Dikarenakan bufer nomor 150 tidak ada, kita coba untuk mengambil history dengan bufer nomor 866
  > !866
  
    ![6d.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6d.1.png)

- Perintah dari history tersebut akan langsung dijalankan ketika di enter
  
  ![6d.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6d.2.png)

<br>

### e. Ulangi instruksi dengan prefix “ls”  
  > $ !ls

**Jawab:**
- Selain dengan metode sebelumnya, kita juga bisa menggunakan kode berikut untuk mengambil history terakhir, misalkan kita ingin mengambil kode yang berawalan "ls"
  > !ls

![6e.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6e.1.png)
