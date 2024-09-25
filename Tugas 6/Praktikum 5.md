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
- 
![1c.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1c.1.png)
![1c.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/1c.2.png)
![2a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/2a.1.png)
![2a.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/2a.2.png)
![2b.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/2b.1.png)
![3a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/3a.1.png)
![3a.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/3a.2.png)
![3a.3](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/3a.3.png)
![4a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.1.png)
![4a.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.2.png)
![4a.3](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.3.png)
![4a.4](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.4.png)
![4a.5](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.5.png)
![4a.6](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4a.6.png)
![4b.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4b.1.png)
![4b.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4b.2.png)
![4b.3](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4b.3.png)
![4b.4](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/4b.4.png)
![5a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/5a.1.png)
![5b.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/5b.1.png)
![5c.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/5c.1.png)
![5d.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/5d.1.png)
![5d.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/5d.2.png)
![6a.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6a.1.png)
![6b.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6b.1.png)
![6b.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6b.2ctrl%2Bp.png)
![6b.3](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6b.3ctrl%2Bn.png)
![6d.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6d.1.png)
![6d.2](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6d.2.png)
![6e.1](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/Tugas%206/asets/6e.1.png)
