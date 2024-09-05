[←    BACK](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/8d6109ee4ac0a66b0f3c1e32776c9dc78248a35c/README.md)
# Tugas 3 Command Line

## Informasi Mahasiswa
**Nama: M. Syaiful Karomah**\
**NIM: 090112823828111**\
**Kelas: SK3C**
<br>
<br>

<div align="Center">

## 50 COMMAND LINE UBUNTU

</div>

### Daftar Isi
<details>
  <summary>Show more</summary>

1. [Shutdown (Matikan atau Reboot)](#shutdown-matikan-atau-reboot)
2. [Reboot (Mulai Ulang)](#reboot-mulai-ulang)
3. [Poweroff (Matikan)](#poweroff-matikan)
4. [Help (Bantuan)](#help-bantuan)
5. [Man (Manual/Panduan)](#man-manualpanduan)
6. [Clear (Bersihkan Terminal)](#clear-bersihkan-terminal)
7. [History (Menampilkan History)](#history-menampilkan-history)
8. [Exit (Menutup Terminal)](#exit-menutup-terminal)
9. [ls (List)](#ls-list)
10. [mkdir (Make Directory)](#mkdir-make-directory)
11. [cd](#cd)
12. [Touch](#touch)
13. [mv (move)](#mv-move)
14. [cat](#cat)
15. [Head](#head)
16. [tail](#tail)
17. [passwd](#passwd)
18. [nano](#nano)
19. [cp](#cp)
20. [rm](#rm)
21. [wc](#wc)
22. [wget (web get)](#wget-web-get)
23. [grep](#grep)
24. [tar](#tar)
25. [echo](#echo)
26. [date](#date)
27. [df](#df)
28. [dig](#dig)
29. [htop](#htop)
30. [du](#du)
31. [hostname](#hostname)
32. [ifconfig](#ifconfig)
33. [sudo apt](#sudo-apt)
34. [kill](#kill)
35. [locate](#locate)
36. [netstat](#netstat)
37. [nslookup](#nslookup)
38. [ping](#ping)
39. [ps](#ps)
40. [locale](#locale)
41. [pwd](#pwd)
42. [free](#free)
43. [journalctl](#journalctl)
44. [times](#times)
45. [top](#top)
46. [uname](#uname)
47. [alias](#alias)
48. [crontab](#crontab)
49. [curl](#curl)
50. [file](#file)

</details>
<br>
<br>

### 1. Shutdown (Matikan atau Reboot)
**Cara Penggunaan:**
> shutdown [opsi]

**Contohh Penggunaan:**
- > shutdown -r

    ![Shutdown -r](https://github.com/SyaifulKaromah/foto-repo/blob/65d0bcbfa3b719d099ddd5eff37819f8e5d36ea0/tugas2/shutdown_-r.png)

<div align="center">

```Shutdown -r``` digunakan untuk menyalakan ulang komputer

</div>
<br>

- > shutdown -f

    ![Shutdown -f](https://github.com/SyaifulKaromah/foto-repo/blob/3cec6c8b142a3d00eb5b3168b40600e5bb8a2548/tugas2/shutdown%20-f.png)

<div align="center">

```Shutdown -f``` digunakan untuk Mematikan komputer

</div>
<br>
<br>

### 2. Reboot (Mulai Ulang)
**Cara Penggunaan:**
> reboot

**Contoh Penggunaan:**
> reboot

  ![reboot](https://github.com/SyaifulKaromah/foto-repo/blob/3cec6c8b142a3d00eb5b3168b40600e5bb8a2548/tugas2/reboot.png)

<div align="center">

sama seperti **Shutdown -r**, ```Reboot``` juga berfungsi untuk menyalakan ulang komputer 

</div>
<br>
<br>

### 3. Poweroff (Matikan)
**Cara Penggunaan:**
> poweroff

**Contoh Penggunaan:**
> poweroff

  ![poweroff](https://github.com/SyaifulKaromah/foto-repo/blob/3cec6c8b142a3d00eb5b3168b40600e5bb8a2548/tugas2/poweroff.png)

<div align="center">

sama seperti **Shutdown -f**, ```Poweroff``` juga berfungsi untuk mematikan komputer

</div>
<br>
<br>

### 4. Help (Bantuan)
**Cara Penggunaan:**
> help

**Contoh Penggunaan:**
> help

  ![help](https://github.com/SyaifulKaromah/foto-repo/blob/3cec6c8b142a3d00eb5b3168b40600e5bb8a2548/tugas2/help.png)

<div align="center">

command ```Help``` digunakan untuk menampilkan bantuan syntax atas command-command secara singkat

</div>
<br>
<br>

### 5. Man (Manual/Panduan)
**Cara Penggunaan:**
> man [command]

**Contoh Penggunaan:**
> man netstat

  ![Man netstat](https://github.com/SyaifulKaromah/foto-repo/blob/3cec6c8b142a3d00eb5b3168b40600e5bb8a2548/tugas2/man.png)

  ![man netstat hasil](https://github.com/SyaifulKaromah/foto-repo/blob/3cec6c8b142a3d00eb5b3168b40600e5bb8a2548/tugas2/man2.png)

<div align="center">

```Man``` digunakan untuk menampilkan manual command-command secara lengkap, terkadang terdapat contoh penggunaan.

</div>
<br>
<br>

### 6. Clear (Bersihkan Terminal)
**Cara Penggunaan:**
> clear

**Contoh Penggunaan:**
> clear

  ![clear](https://github.com/SyaifulKaromah/foto-repo/blob/2433ff73d1455cb33f814915a99bc0e32a802ff5/tugas2/clear.png)

  ![clear hasil](https://github.com/SyaifulKaromah/foto-repo/blob/2433ff73d1455cb33f814915a99bc0e32a802ff5/tugas2/clear2.png)

<div align="center">

```Clear``` digunakan untuk membersihkan terminal

</div>
<br>
<br>

### 7. History (Menampilkan History)
**Cara Penggunaan:**
> history

**Contoh Penggunaaan:**
> history

  ![History](https://github.com/SyaifulKaromah/foto-repo/blob/019b7a29c9bcac117024d9f3cab29e041dda69c1/tugas2/history.png)

<div align="center">

```History``` digunakan untuk menampilkan history command yang pernah dijalankan

</div>
<br>
<br>  

### 8. Exit (Menutup Terminal)
**Cara Penggunaan:**
> exit

**Contoh Penggunaan:**
> exit

  ![exit](https://github.com/SyaifulKaromah/foto-repo/blob/019b7a29c9bcac117024d9f3cab29e041dda69c1/tugas2/exit.png)

<div align="center">

command ```Exit``` digunakan untuk menutup terminal

</div>
<br>
<br>

### 9. ls (List)
**Cara Penggunaan:**
> ls [opsi] [nama_direktori]

**Contoh Penggunaan:**
> ls

  ![ls](https://github.com/SyaifulKaromah/foto-repo/blob/2433ff73d1455cb33f814915a99bc0e32a802ff5/tugas2/ls.png)

<div align="center">

```lS``` digunakan untuk menampilkan list folder dan file

</div>
<br>
<br>

### 10. mkdir (Make Directory)
**Cara Penggunaan:**
> mkdir [nama_direktori]

**Contoh Penggunaan:**
> mkdir Hello

  ![mkdir](https://github.com/SyaifulKaromah/foto-repo/blob/2433ff73d1455cb33f814915a99bc0e32a802ff5/tugas2/mkdir.png)

<div align="center">

```mkdir``` digunakan untuk membuat folder

</div>
<br>
<br>

### 11. cd
**Cara Penggunaan:**
> cd [nama_direktori]

**Contoh Penggunaan:**
> cd \Hello

  ![cd](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/cd.png)

<div align="center">

```cd``` digunakan untuk berpindah ke dalam direktori lain

</div>
<br>
<br>

### 12. Touch
**Cara Penggunaan:**
> touch [opsi] [nama_file]

**Contoh Penggunaan:**
> touch readme.md

  ![touch](https://github.com/SyaifulKaromah/foto-repo/blob/2433ff73d1455cb33f814915a99bc0e32a802ff5/tugas2/touch.png)

<div align="center">

```touch``` digunakan untuk membuat file baru

</div>
<br>
<br>

### 13. mv (move)
**Cara Penggunaan:**
> mv [nama_file_asal] [nama_file_tujuan]

**Contoh Penggunaan:**
> mv readme.md realme.md

  ![head](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/mv.png)

<div align="center">

```mv``` digunakan untuk mengubah nama atau memindahkan file dan folder

</div>
<br>
<br>

### 14. cat 
**Cara Penggunaan:**
> cat [nama_file]

**Contoh Penggunaan:**
> cat realme.md

  ![cat](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/cat.png)

<div align="center">

```cat``` digunakan untuk menampilkan file

</div>
<br>
<br>

### 15. Head 
**Cara Penggunaan:**
> head [nama_file]

**Contoh Penggunaan:**
> head realme.md

  ![head](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/head.png)

<div align="center">

```head``` digunakan untuk menampilkan baris pertama file

</div>
<br>
<br>

### 16. tail 
**Cara Penggunaan:**
> tail [nama_file]

**Contoh Penggunaan:**
> tail realme.md

  ![tail](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/tail.png)

<div align="center">

```tail``` digunakan untuk menampilkan baris terakhir file

</div>
<br>
<br>

### 17. passwd 
**Cara Penggunaan:**
> paswd

**Contoh Penggunaan:**
> passwd

  ![passwd](https://github.com/SyaifulKaromah/foto-repo/blob/af5082a589f4f7372a55b5e222b15c2f864f205c/tugas2/passwd.png)

<div align="center">

```passwd``` digunakan untuk mengganti password host

</div>
<br>
<br>

### 18. nano 
**Cara Penggunaan:**
> nano [nama_file]

**Contoh Penggunaan:**
> nano realme.md

  ![nano](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/nano1.png)

  ![nano2](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/nano2.png)

<div align="center">

```nano``` digunakan untuk membuka editor nano untuk mengedit file

</div>
<br>
<br>

### 19. cp 
**Cara Penggunaan:**
> cp [opsi] [nama_file_asal] [nama_file_tujuan]

**Contoh Penggunaan:**
> cp realme.md readme.html

  ![cp](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/cp.png)

<div align="center">

```cp``` digunakan untuk menyalin file

</div>
<br>
<br>

### 20. rm 
**Cara Penggunaan:**
> rm [nama_file]

**Contoh Penggunaan:**
> rm realme.md

  ![rm](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/rm.png)

<div align="center">

```rm``` digunakan untuk menghapus file

</div>
<br>
<br>

### 21. wc 
**Cara Penggunaan:**
> wc [opsi] [nama_file]

**Contoh Penggunaan:**
> wc -l realme.md

  ![wc](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/wc.png)

<div align="center">

```wc``` digunakan untuk menghitung baris suatu file

</div>
<br>
<br>

### 22. wget (web get)
**Cara Penggunaan:**
> wget [url]

**Contoh Penggunaan:**
> wget google.com

  ![wget](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/wget.png)

<div align="center">

```wget``` digunakan untuk mendownload file dari internet menggunakan protokol HTTP, HTTPS, atau FTP

</div>
<br>
<br>

### 23. grep
**Cara Penggunaan:**
> grep [pola] [nama_file]

**Contoh Penggunaan:**
> grep "error"  index.html

  ![grep](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/grep.png)

<div align="center">

```grep``` digunakan untuk mencari pola/teks yang sama dalam file tujuan

</div>
<br>
<br>

### 24. tar
**Cara Penggunaan:**
> tar [opsi] [nama_file]

**Contoh Penggunaan:**
> tar -czvf Hello.tar.gz Hello/

  ![tar](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/tar.png)

<div align="center">

```tar``` digunakan untuk mengompresi direktori

</div>
<br>
<br>

### 25. echo
**Cara Penggunaan:**
> echo [teks]

**Contoh Penggunaan:**
> echo M. Syaiful Karomah

  ![echo](https://github.com/SyaifulKaromah/foto-repo/blob/271f566c6ce61a31bbf8b077aa596a21f4e48949/tugas2/echopng.png)

<div align="center">

```echo``` digunakan untuk menampilkan teks yang di input
</div>
<br>
<br>

### 26. date
**Cara Penggunaan:**
> date [option]

**Contoh Penggunaan:**
> date

  ![date](https://github.com/SyaifulKaromah/foto-repo/blob/b6e338c1530738d6f30ec9be68f2175cea7bdb60/tugas2/date.png)

<div align="center">

```date``` digunakan untuk menampilkan atau mengatur waktu sistem
</div>
<br>
<br>

### 27. df
**Cara Penggunaan:**
> df [option]

**Contoh Penggunaan:**
- > df

    ![df](https://github.com/SyaifulKaromah/foto-repo/blob/b6e338c1530738d6f30ec9be68f2175cea7bdb60/tugas2/df.png)

- > df -h

    ![df](https://github.com/SyaifulKaromah/foto-repo/blob/main/tugas2/df2.png)

<div align="center">

```df``` untuk menampilkan informasi ruang disk yang tersedia
</div>
<br>
<br>

### 28. dig
**Cara Penggunaan:**
> dig [domain]

**Contoh Penggunaan:**
> dig

  ![dig](https://github.com/SyaifulKaromah/foto-repo/blob/main/tugas2/dig.png)

<div align="center">

```dig``` digunakan untuk meminta informasi  tentang DNS name server.
</div>
<br>
<br>

### 29. htop
**Cara Penggunaan:**
> htop 

**Contoh Penggunaan:**
> htop

  ![htop](https://github.com/SyaifulKaromah/foto-repo/blob/b6e338c1530738d6f30ec9be68f2175cea7bdb60/tugas2/htop1.png)
  
  ![htop](https://github.com/SyaifulKaromah/foto-repo/blob/b6e338c1530738d6f30ec9be68f2175cea7bdb60/tugas2/htop2.png)

<div align="center">

```htop``` digunakan untuk memantau proses sistem dan mengelola proses.
</div>
<br>
<br>

### 30. du
**Cara Penggunaan:**
> du [opsi] [nama_direktori] 

**Contoh Penggunaan:**
- > du

  ![du](https://github.com/SyaifulKaromah/foto-repo/blob/b6e338c1530738d6f30ec9be68f2175cea7bdb60/tugas2/du.png)

- > du -sh \Hello

  ![du -sh](https://github.com/SyaifulKaromah/foto-repo/blob/b6e338c1530738d6f30ec9be68f2175cea7bdb60/tugas2/du2.png)
  
<div align="center">

```du``` digunakan untuk menampilkan penggunaan disk suatu direktori.
</div>
<br>
<br>

### 31. hostname
**Cara Penggunaan:**
> hostname 

**Contoh Penggunaan:**
> hostname

  ![hostname](https://github.com/SyaifulKaromah/foto-repo/blob/b6e338c1530738d6f30ec9be68f2175cea7bdb60/tugas2/du.png)

<div align="center">

```hostname``` digunakan untuk menampilkan nama host sistem.
</div>
<br>
<br>

### 32. ifconfig
**Cara Penggunaan:**
> ifconfig [opsi]

**Contoh Penggunaan:**
> ifconfig

  ![ifconfig](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/ifconfig.png)

<div align="center">

```ifconfig``` digunakan untuk menampilkan konfiguasi antarmuka jaringan.
</div>
<br>
<br>

### 33. sudo apt
**Cara Penggunaan:**
> sudo apt [opsi] [perintah]

**Contoh Penggunaan:**
- > sudo apt install net-tools

    ![sudo apt install](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/install_net_tools.png)

- > sudo apt update

    ![sudo apt update](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/sudo_apt_update.png)

- > sudo apt upgrade

    ![sudo apt upgrade](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/sudo_apt_upgrade.png)

<div align="center">

```sudo apt``` digunakan untuk melakukan eksekusi root yang berurusan dengan sistem paket.
</div>
<br>
<br>

### 34. kill
**Cara Penggunaan:**
> kill [Nomor_ID_Proses/PID]

**Contoh Penggunaan:**
> kill 2788

  ![kill](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/kill.png)

<div align="center">

```kill``` digunakan untuk menghentikan proses yang sedang berjalan.
</div>
<br>
<br>

### 35. locate
**Cara Penggunaan:**
> locate [opsi] [nama_file]

**Contoh Penggunaan:**
> locate -l realme.md

  ![locate](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/locate.png)

<div align="center">

```lcoate``` digunakan untuk mencari file atau direktori berdasarkan nama.
</div>
<br>
<br>

### 36. netstat
**Cara Penggunaan:**
> netstat [opsi]

**Contoh Penggunaan:**
> netstat

  ![netstat](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/netstat.png)

<div align="center">

```netstat``` digunakan untuk menampilkan informasi tentang koneksi jaringan, routing tabel, dan statistik antarmuka.
</div>
<br>
<br>

### 37. nslookup
**Cara Penggunaan:**
> nslookup [domain]

**Contoh Penggunaan:**
> nslookup google.com

  ![nslookup](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/nslookup2.png)

<div align="center">

```nslookup``` digunakan untuk mengambil informasi DNS tentang domain tertentu.

</div>
<br>
<br>

### 38. ping
**Cara Penggunaan:**
> ping [opsi] [domain/IP_Address]

**Contoh Penggunaan:**
> ping 8.8.8.8

  ![ping](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/ping.png)

<div align="center">

```ping``` digunakan untuk mengirimkan request ke host tertentu.
</div>
<br>
<br>

### 39. ps
**Cara Penggunaan:**
> ps [opsi] 

**Contoh Penggunaan:**
> ps aux

  ![ps](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/ps.png)

<div align="center">

```ps``` digunakan untuk menampilkan informasi proses yang sdang berjalan.
</div>
<br>
<br>

### 40. locale
**Cara Penggunaan:**
> locale

**Contoh Penggunaan:**
> locale

  ![locale](https://github.com/SyaifulKaromah/foto-repo/blob/af5082a589f4f7372a55b5e222b15c2f864f205c/tugas2/locale.png)

<div align="center">

```locale``` digunakan untuk mengidentifikasi suatu aturan lokal misalnya bahasa, karakter, penanggalan dan sebagainya dari suatu wilayah negara tertentu.
</div>
<br>
<br>

### 41. pwd
**Cara Penggunaan:**
> pwd

**Contoh Penggunaan:**
> pwd

  ![pwd](https://github.com/SyaifulKaromah/foto-repo/blob/af5082a589f4f7372a55b5e222b15c2f864f205c/tugas2/pwd.png)

<div align="center">

```pwd``` digunakan untuk menampilkan direktori kerja saat ini.
</div>
<br>
<br>

### 42. free
**Cara Penggunaan:**
> free [opsi]

**Contoh Penggunaan:**
> free

  ![free](https://github.com/SyaifulKaromah/foto-repo/blob/af5082a589f4f7372a55b5e222b15c2f864f205c/tugas2/free.png)

<div align="center">

```free``` digunakan untuk menampilkan informasi tentang memory dan swap dalam kibibyte (KiB).
</div>
<br>
<br>

### 43. journalctl
**Cara Penggunaan:**
> journalctl [opsi] [service]

**Contoh Penggunaan:**
> journalctl -u NetworkManager-wait-online.service

  ![journalctl](https://github.com/SyaifulKaromah/foto-repo/blob/af5082a589f4f7372a55b5e222b15c2f864f205c/tugas2/journalctl.png)

<div align="center">

```journalctl``` digunakan untuk menampilkan log sistem menggunakan jurnal sistem systemd.
</div>
<br>
<br>

### 44. times
**Cara Penggunaan:**
> times

**Contoh Penggunaan:**
> times

  ![times](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/times.png)

<div align="center">

```times``` digunakan untuk menampilkan ringkasan waktu secara real-time dan waktu user CPU, system CPU.
</div>
<br>
<br>

### 45. top
**Cara Penggunaan:**
> top

**Contoh Penggunaan:**
> top

  ![top](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/top2.png)

<div align="center">

```top``` digunakan untuk menunjukkan kinerja dan statistik penggunaan server kamu.
</div>
<br>
<br>

### 46. uname
**Cara Penggunaan:**
> uname [ospi]

**Contoh Penggunaan:**
> uname

  ![uname](https://github.com/SyaifulKaromah/foto-repo/blob/692cf7d65473eef7117b4781d2ded8c21781a2dd/tugas2/uname.png)

<div align="center">

```uname``` digunakan untuk menampilkan informasi tentang sistem operasi
</div>
<br>
<br>

### 47. alias
**Cara Penggunaan:**
> alias

**Contoh Penggunaan:**
> alias

  ![alias](https://github.com/SyaifulKaromah/foto-repo/blob/af5082a589f4f7372a55b5e222b15c2f864f205c/tugas2/alias.png)

<div align="center">

```alias``` digunakan untuk menambah atau menampilkan alias dari perintah
</div>
<br>
<br>

### 48. crontab
**Cara Penggunaan:**
> crontab [opsi]

**Contoh Penggunaan:**
> crontab -e

  ![crontab](https://github.com/SyaifulKaromah/foto-repo/blob/main/tugas2/crontab_-e.png)

<div align="center">

```crontab``` digunakan untuk mengatur tugas tugas terjadwal
</div>
<br>
<br>

### 49. curl
**Cara Penggunaan:**
> curl [opsi] [URL]

**Contoh Penggunaan:**
> curl google.com

  ![curl](https://github.com/SyaifulKaromah/foto-repo/blob/af5082a589f4f7372a55b5e222b15c2f864f205c/tugas2/curl.png)

<div align="center">

```curl``` digunakan untuk mendownload atau mengirim data dengan URL
</div>
<br>
<br>

### 50. file
**Cara Penggunaan:**
> file [namafile]

**Contoh Penggunaan:**
> file text.txt

  ![file](https://github.com/SyaifulKaromah/foto-repo/blob/af5082a589f4f7372a55b5e222b15c2f864f205c/tugas2/file.png)

<div align="center">

```file``` digunakan untuk menampilkan jenis file
</div>
