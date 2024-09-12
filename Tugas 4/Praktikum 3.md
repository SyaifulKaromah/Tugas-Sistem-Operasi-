[←    BACK](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/README.md)

# Tugas 4
## Informasi Mahasiswa
**Nama: M. Syaiful Karomah**\
**NIM: 090112823828111**\
**Kelas: SK3C**
<br>
<br>

<div align="Center">
  
## Praktikum 3

</div>

## Soal 1
**Lihat peralatan I/O, character device, yang ada pada system komputer.**
### Jawab:
- Menampilkan peralatan I/O
  > ls -l /dev
  
    ![tugas_4-no1](https://github.com/user-attachments/assets/1382bf60-4b30-424e-9f17-5ba3796f0a25)
<div align="Center">

  ```Pada bagian paling kiri yang ditandai dengan "c" diawal merupakan character device dan yang ditandai dengan "b" meruakan block device```

 </div>
 
- Menampilkan Character device dengan cara lain
  > cat /proc/devices
  
    ![tugas_4-no1b](https://github.com/user-attachments/assets/a2823bda-1b74-4079-8540-a0e87be9fb3c)
<div align="Center">

  ```Dengan kode tersebut, lebih terkumpul antara Character Devices dan Block Devices```

 </div>
<br>

## Soal 2
**Buatlah subdirektori Januari, Februari dan Maret sekaligus pada direktori latihan5**
### Jawab:
- Terlebih dahulu buat folder **latihan5**
  > mkdir latihan5
- Masuk direktori latihan5
  > cd latihan5
- Buat folder **Januari**, **Februari** dan **Maret** sekaligus
  > mkdir Januari Februari Maret
- Cek folder
  > tree
  
    ![tugas_4-no2a](https://github.com/user-attachments/assets/8c177bd2-82d4-4e58-8e27-43b95fc37714)
<br>

## Soal 3
**Buatlah file dataku yang berisi Nama, NIM dan Alamat anda pada sub direktori Januari dan copy file tersebt ke sub direktori februari dan maret**
### Jawab:
- Buat file **dataku.txt**
  > nano Januari/dataku.txt
- Isi identitas:

  ![tugas_4-no3a](https://github.com/user-attachments/assets/6778ec2b-2a68-4c5c-88e2-970ac76aed88)

- keluar dari nano "**CTRL + X**"
- kemudian **Y** dan **enter**
- keluar dari direktori
  > cd ..
- lalu cek
  > tree
  
    ![tugas_4-no3b](https://github.com/user-attachments/assets/149cf077-a539-4a8f-9a74-ed724dbb78d8)

- Salin file **dataku.txt** pada **Januari** ke **Februari** dan **Maret**
  > for dest in latihan5/*; do cp latihan5/Januari/dataku.txt "$dest/"; done
  
- lalu cek
  > tree

    ![tugas_4-no3c](https://github.com/user-attachments/assets/425313b8-15f2-46a2-adc2-6dc65d4a744d)
<br>

## Soal 4
**Ubahlah izin akses file dataku.txt pada sub direktori Januari sehingga group dan others dapat melakukan write**
### Jawab:
- Ubah izin file **dataku.txt** sub direktori **Januari** untuk group dan others
  > chmod g=w,o=w Januari/dataku.txt
- Cek dengan ls -l
  > ls -l Januari/dataku.txt
  
   ![tugas_4-no4](https://github.com/user-attachments/assets/a798354d-cd93-4381-a2e6-339d29dcd529)
<br>

## Soal 5
**Ubahlah ijin akses file dataku pada sub direktori Februari sehingga user dapat melakukan read, write dan execute, tetapi group dan other hanya bisa read dan execute.**
### Jawab:
- Ubah izin file **dataku.txt** sub direktori **Februari** untuk user, group dan others
  > chmod u=rwx,g=rx,o=rx Februari/dataku.txt
- Cek dengan ls -l
  > ls -l Februari/dataku.txt
  
    ![tugas_4-no5](https://github.com/user-attachments/assets/e3421a5a-2fbe-46eb-97b2-463e01975fff)
<br>

## Soal 6
**Ubahlah ijin akses file dataku pada sub direktori Maret sehingga semua dapat melakukan write, read dan execure**
### Jawab:
- ubah ijin akses file **dataku.txt** sub direktori **Maret** untuk user, group dan others
  > chmod a=rwx Maret/dataku.txt
- Cek dengan ls -l
  > ls -l Maret/dataku.txt
  
    ![tugas_4-no6](https://github.com/user-attachments/assets/3c848d5f-cca8-4c3b-9afa-e51fe0224e7a)
<br>

## Soal 7
**Hapus direktori maret.**
### Jawab:
- Hapus direktori
  > rm -r Maret
  
    ![tugas_4-no7](https://github.com/user-attachments/assets/05b083d6-5dd1-4547-b2ff-dc021af5bdd2)
<br>

## Soal 8
**Ubahkan kepemilikan sub direktori Februari sehingga user dan group hanya bisa melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori Februari**
### Jawab:
- Ubah kepemilikan
  > sudo chown syf:mahasiswa Februari/
- Ubah izin
  > sudo chmod ug=r-- Februari/
- Buat folder **haha**
  > mkdir Februari/haha
  
    ![tugas_4-no8](https://github.com/user-attachments/assets/8de4c40f-e517-42ae-bddb-3dbc323b74bf)
<div align="Center">

  ```Permission Dennied terjadi karna user dan grpup hanya bisa Read```

 </div>
<br>

## Soal 9
**Modifikasi umask dari file dataku pada sub direktori Januari menjadi 027 dan berapakah nilai default-Nya?**
### Jawab:
- cek nilai default umask
  > umask
- umask default adalah **002**
- set nilai umask
  > umask 027
  
  ![tugas_4-no9](https://github.com/user-attachments/assets/44696115-6d08-4a0c-a69b-a6eed9f9cd7f)

- Jika nilai umask adalah 027, maka izin default untuk file baru akan menjadi 750. Berikut adalah perhitungannya:
  - Izin default untuk direktori: 777
  - Umask: 027
  - Izin akhir: 777 - 027 = 750
- ubah izin **dataku.txt** menjadi 750
  > chmod 750 dataku.txt
  
    ![tugas_4-no9b](https://github.com/user-attachments/assets/b56ee30a-851f-4d31-a750-7eeec84f01cb)

- jadi, izin semula adalah **user** bisa **membaca** dan **menulis**, **group** dan **others** hanya bisa **membaca** atau **622**, setelah diberikan **umask** **027**, mendapatkan perubahan izin menjadi **user** bisa **membaca**, **menulis** dan **eksekusi**, **group** hanya bisa **membaca** dan **mengeksekusi**, sedangkan **others** **tidak memilki izin** apapun atau **750** 

<br>

## Soal 10
**Buatlah link dari file dataku.txt ke file dataku.ini dan file dataku.juga dan dengan perintah list perhatikan berapa link yang terjadi?**
### Jawab:
- link **dataku.txt** ke **dataku.ini** dan **dataku.juga**
  > ln -s dataku.txt dataku.ini && ln -s dataku.txt dataku.juga
- tampilkan link dengan list
  > ls -l
  
    ![tugas_4-no10](https://github.com/user-attachments/assets/60d96a37-a564-4235-9b91-c0fa261324f0)
