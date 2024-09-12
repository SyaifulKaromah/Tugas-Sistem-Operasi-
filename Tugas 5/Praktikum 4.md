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
**Lihat daftar secara lengkap pada direktori aktif, belokkan tampilan standard output ke file baru.**
### Jawab:
- Melihat daftar secara lengkap pada **direktori aktif** dan simpan ke **file_baru**
  > ls -l > file_baru
  
    ![latihan6_no1](https://github.com/user-attachments/assets/abbf2675-d4f5-4eaf-a3d8-8a0e8139a846)

<br>

## Soal 2
**Lihat daftar secara lengkap pada direktori /etc/passwd, belokkan tampilan standard output ke file baru tanpa menghapus file_baru sebelumnya.**
### Jawab:
- Melihat daftar secara lengkap pada direktori **/etc/passwd**, dan simpan ke **file_baru** tanpa menghapus **file_baru** sebelumnya.
  > ls -l /etc/passwd >> file_baru
  
    ![latihan6_no2](https://github.com/user-attachments/assets/19edc6a7-4863-41f1-aa69-e2b9f4daac0b)

<br>

## Soal 3
**Urutkan file baru dengan cara membelokkan standard input.**
### Jawab:
- Mengurutkan **file_baru**
  > sort < file_baru
  
    ![latihan6_no3](https://github.com/user-attachments/assets/134f57ee-ea60-4710-a4cb-10d75b95ac72)

<br>

## Soal 4
**Urutkan file baru dengan cara membelokkan standard input dan standard output ke file baru.urut.**
### Jawab:
- Mengurutkan **file_baru** dan simpan ke **file_baru.urut**
  > sort < file_baru > file_baru.urut
 
    ![latihan6_no4](https://github.com/user-attachments/assets/230ca2de-6494-4a92-8fc4-8c19202bdb1c)

<br>

## Soal 5
**Buatlah direktori latihan6 sebanyak 2 kali dan belokkan standard error ke file rmdirerror.txt.**
### Jawab:
- Membuat direktori **latihan6** 2 kali dan simpan pesan eror di **rmdirerror.txt**
  > mkdir latihan6 2> rmdirerror.txt
  
  > mkdir latihan6 2>> rmdirerror.txt
  
    ![latihan6_no5](https://github.com/user-attachments/assets/58dcb5ae-243b-4223-b180-1770f53a6ec8)

<br>

## Soal 6
**Urutkan kalimat berikut :**\
  - **Jakarta**  
  - **Bandung**  
  - **Surabaya**  
  - **Padang**  
  - **Palembang**  
  - **Lampung**\
**Dengan menggunakan notasi here document (<@@@ …@@@)**
### Jawab:
- Urutkan dengan notasi here document
  > sort <<@@@
  
  > Jakarta
  
  > Bandung
  
  > Surabaya
  
  > Padang
  
  > Palembang
  
  > Lampung
  
  > @@@ 

    ![latihan6_no6](https://github.com/user-attachments/assets/0dfc9c99-55dc-4382-8705-06e0c474af03)

<br>

## Soal 7
**Hitung jumlah baris, kata dan karakter dari file baru.urut dengan menggunakan filter dan tambahkan data tersebut ke file baru.**
### Jawab:
- Menghitung jumlah baris, kata dan karakter dari **file_baru.urut** dan simpan/tambahkan ke **file_baru**
  > wc file_baru.urut >> file_baru

    ![latihan6_no7](https://github.com/user-attachments/assets/b4cdf29c-ba7f-423f-9c20-d9488bf57c71)
  
<br>

## Soal 8
**Gunakan perintah di bawah ini dan perhatikan hasilnya.**\
**$ cat /etc/passwd | sort | pr –n | grep tty03**\
**$ find /etc –print | head**\
**$ head /etc/passwd | tail –5 | sort**
### Jawab:
- Gunakan perintah tersebut
  > cat /etc/passwd | sort | pr –n | grep tty03
  
  > find /etc –print | head
  
  > head /etc/passwd | tail –5 | sort
  
    ![latihan6_no8](https://github.com/user-attachments/assets/4ea4f86d-8860-484f-b595-25a702c6e2f8)

- Fungsi dari perintah-perintah tersebut:
  - ```$ cat /etc/passwd | sort | pr –n | grep tty03```
     - cat /etc/passwd: Menampilkan isi file /etc/passwd.
     - sort: Mengurutkan isi file secara alfabetis.
     - pr –n: Menambahkan nomor baris pada output.
     - grep tty03: Menyaring dan menampilkan baris yang mengandung “tty03”.
  - ```$ find /etc –print | head```
     - find /etc –print: Mencari dan menampilkan semua file dan direktori di dalam /etc.
     - head: Menampilkan 10 baris pertama dari hasil pencarian.
  - ```$ head /etc/passwd | tail –5 | sort```
     - head /etc/passwd: Menampilkan 10 baris pertama dari file /etc/passwd.
     - tail –5: Menampilkan 5 baris terakhir dari hasil head.
     - sort: Mengurutkan 5 baris tersebut secara alfabetis.

## Soal 9
**Gunakan perintah $ who | cat | cat | sort | pr | head | cat | tail dan perhatikan hasilnya.**
### Jawab:
- Gunakan perintah tersebut
  > who | cat | cat | sort | pr | head | cat | tail

    ![latihan6_no9](https://github.com/user-attachments/assets/6945693c-115b-46fd-9f33-88dc165a02f3)

- Berikut adalah fungsi dari setiap bagian perintah tersebut:
  - ```who```: Menampilkan daftar pengguna yang sedang login ke sistem.
  - ```cat | cat```: Menyalin input dari who dua kali, yang sebenarnya tidak mengubah output.
  - ```sort```: Mengurutkan daftar pengguna secara alfabetis.
  - ```pr```: Memformat output menjadi halaman yang dapat dicetak.
  - ```head```: Menampilkan 10 baris pertama dari output yang diformat.
  - ```tail```: Menampilkan 10 baris terakhir dari output yang diformat oleh ```head```.
