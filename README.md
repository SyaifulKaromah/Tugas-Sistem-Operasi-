# PRAKTIKUM 1 - SISTEM OPERASI
> [Soal 1](#soal-1)\
> [Soal 2](#soal-2)\
> [Soal 3](#soal-3)


<br>
<br>

# [←    BACK](#praktikum-1---sistem-operasi) Soal 1

<div align="center">

## LAPORAN PRAKTIKUM SISTEM OPERASI

## FSK2108

## PROSES INTSALLASI SISTEM OPERASI UBUNTU

**Dosen Pengampu:**\
Ahmad Heryanto, M. T.\
Adi Hermansyah, M. T.\
Sutarno, M.T.\
Iman Saladin B. Azhar, S. Kom., M. M.SI.\
Dr. Ahmad Zarkarsi, M. T.

![Logo Universitas Sriwijaya](https://github.com/SyaifulKaromah/foto-repo/blob/285a4fb7041ceb481a2d3136fdbcd03727e3a042/lambang-unsri-png-0-removebg-preview.png)

**Disusun Oleh:**\
Nama: M. Syaiful Karomah\
NIM: 09011282328111\
Hari/Tanggal: Kamis, 29 Agustus 2024

**JURUSAN SISTEM KOMPUTER**  
**FAKULTAS ILMU KOMPUTER**  
**UNIVERSITAS SRIWIJAYA**  
**2024**
<br>
<br>

## Daftar Isi

</div>

>
**[Pendahuluan](#pendahuluan)**
  > [Latar Belakang](#latar-belakang)\
  > [Tujuan](#tujuan)\
  > [Landasan Teori](#landasan-teori)

>
**[Alat dan Bahan](#alat-dan-bahan)**
  > [Alat](#alat)\
  > [Bahan](#bahan)

>
**[Prosedur](#prosedur)**

>
**[Hasil dan Pembahasan](#hasil-dan-pembahasan)**
  > [Hasil](#hasil)\
  > [Pembahasan](#pembahasan)

>
**[Kesimpulan](#kesimpulan)**

>
**[Daftar Pustaka](#daftar-pustaka)**

<div align="center">
<br>
<br>

## Pendahuluan

</div>

### Latar Belakang

<div align="justify">

Dalam era komputasi modern, pemahaman dan keterampilan dalam menginstal dan mengoperasikan berbagai sistem operasi menjadi semakin penting. Salah satu sistem operasi yang mendapat perhatian khusus adalah Ubuntu, sebuah distribusi Linux yang terkenal dengan keamanan, stabilitas, dan kemudahan penggunaannya. Ubuntu menawarkan alternatif yang kuat dan fleksibel terhadap sistem operasi proprietary, memberikan pengguna kontrol penuh atas lingkungan komputasi mereka.\
Instalasi sistem operasi, khususnya Ubuntu, merupakan langkah fundamental dalam memahami arsitektur dan fungsi sistem operasi. Proses ini tidak hanya melibatkan pemahaman tentang perangkat keras komputer, tetapi juga konsep-konsep penting seperti partisi disk, bootloader, dan konfigurasi sistem. Melalui praktikum instalasi Ubuntu, mahasiswa dapat memperoleh pengalaman langsung dalam mengelola dan mengkonfigurasi sistem operasi, yang merupakan keterampilan penting dalam bidang teknologi informasi.\
Penggunaan mesin virtual seperti VirtualBox dalam praktikum ini memungkinkan eksperimen yang aman dan fleksibel dengan berbagai konfigurasi sistem tanpa risiko merusak sistem utama. Hal ini memberikan lingkungan belajar yang ideal untuk memahami proses instalasi, konfigurasi, dan manajemen sistem operasi.\
Selain itu, Ubuntu, sebagai sistem operasi open-source, menawarkan peluang untuk mempelajari dan berkontribusi pada pengembangan software. Ini sejalan dengan filosofi pendidikan yang mendorong eksplorasi, inovasi, dan kolaborasi dalam dunia teknologi informasi.\
Praktikum instalasi Ubuntu ini juga memberikan dasar yang kuat untuk mata kuliah lanjutan dalam sistem operasi, jaringan komputer, dan keamanan sistem. Pemahaman yang diperoleh dari proses instalasi ini akan membantu mahasiswa dalam memahami konsep-konsep yang lebih kompleks dalam pengelolaan sistem dan pengembangan software di masa depan.\
Dengan melakukan praktikum ini, mahasiswa diharapkan tidak hanya memperoleh keterampilan teknis dalam instalasi sistem operasi, tetapi juga mengembangkan pemahaman yang lebih dalam tentang prinsip-prinsip dasar sistem operasi, manajemen sumber daya komputer, dan pentingnya fleksibilitas dalam lingkungan komputasi modern.

### Tujuan
-	Memahami proses instalasi sistem operasi Ubuntu pada lingkungan virtual menggunakan VirtualBox.
-	Mempraktikkan langkah-langkah konfigurasi awal sistem operasi Ubuntu, termasuk pengaturan bahasa, zona waktu, dan akun pengguna.
-	Mengeksplorasi antarmuka grafis Ubuntu dan membiasakan diri dengan lingkungan desktop Linux.
-	Mendapatkan pengalaman hands-on dalam manajemen sumber daya virtual seperti alokasi RAM, penyimpanan, dan core prosesor.
-	Meningkatkan pemahaman tentang konsep virtualisasi dan manfaatnya dalam pembelajaran sistem operasi.
-	Mempersiapkan lingkungan kerja yang aman untuk eksperimen dan pembelajaran lebih lanjut tentang sistem operasi Linux tanpa mempengaruhi sistem utama.

### Landasan Teori
-	Sistem operasi adalah perangkat lunak sistem yang mengelola sumber daya perangkat keras dan perangkat lunak komputer. Menurut Silberschatz et al. (2018), sistem operasi bertindak sebagai perantara antara pengguna komputer dan perangkat keras komputer, menyediakan lingkungan di mana pengguna dapat mengeksekusi program secara nyaman dan efisien.
-	Linux adalah keluarga sistem operasi open-source berbasis Unix yang dikembangkan oleh Linus Torvalds pada tahun 1991. Ubuntu, dikembangkan oleh Canonical Ltd., adalah salah satu distribusi Linux yang populer. Menurut Canonical (2024), Ubuntu dirancang dengan fokus pada kemudahan penggunaan, stabilitas, dan keamanan.
-	Virtualisasi memungkinkan beberapa sistem operasi berjalan pada satu mesin fisik. VirtualBox, dikembangkan oleh Oracle Corporation, adalah perangkat lunak virtualisasi open-source yang memungkinkan pengguna untuk menjalankan beberapa sistem operasi secara bersamaan pada satu komputer (Oracle, 2024).
-	Proses instalasi sistem operasi melibatkan beberapa tahap kritis, termasuk partisi disk, instalasi bootloader, dan konfigurasi sistem. Menurut Tanenbaum dan Bos (2014), pemahaman tentang proses ini penting untuk manajemen sistem yang efektif dan pemecahan masalah.
-	Open Source dan Pengembangan Kolaboratif
-	Filosofi open-source, seperti yang diterapkan dalam pengembangan Ubuntu, mendorong transparansi, kolaborasi, dan inovasi dalam pengembangan software. Raymond (2001) menyoroti bagaimana model pengembangan open-source dapat menghasilkan software yang lebih kuat dan adaptif. 

</div>

<div align="center">
<br>
<br>

## Alat dan Bahan

</div>

<div align="justify">

### Alat
- Oracle VM VirtualBox

### Bahan
- File ISO Ubuntu Versi 24.04
- Komputer Host
- Ruang Penyimpanan
- Koneksi Internet
- Memori RAM

</div>

<div align="center">
<br>
<br>

## Prosedur

</div>

<div align="justify">

1. Siapkan File ISO Ubuntu Versi 24.04
2. Buka Virtual Box
3. Tekan Tombol Baru
4. Tuliskan Nama, tentukan folder penyimpanan, kemudian Lanjut

   ![Langkah 4](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step4.png)

5. Tentukan besaran ram dan core prossesor

   ![Langkah 5](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step5.png)

6. Tentukan besaran Penyimpanan yang akan di alokasikan

   ![Langkah 6](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step6.png)

   ![Langkah 6-2](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step6-2.png)

7. Masukkan ISO Ubuntu 24.04

   ![Langkah 7](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step7.png)

8. Try or Install Ubuntu

   ![Langkah 8](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step8.png)

9. Tunggu Proses Booting

    ![Langkah 9](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step9.png)

10. Next

    ![Langkah 10](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step10.png)

11. Pasang Ubuntu

![Langkah 11](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step11.png)

12. Masukkan Identitas yang diperlukan dan Password

![Langkah 12](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step12.png)

13. Klik "Mulai Memasang"

![Langkah 13](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/step13.png)

14. Tunggu Proses Installasi selesai

![Langkah 14](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/loading.png)

15. Kemudian, "Restart now"

![Langkah 15](https://github.com/SyaifulKaromah/foto-repo/blob/c9f20bf27a7fc03518c6200053bb3de74a7459e6/restartnow.png)

![Langkah 15-2](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/booting.png)

16. Ubuntu telah selesai di install

   ![Langkah 16](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/selesai.png)

<\div>

<div align="center">
<br>
<br>

## Hasil dan Pembahasan

</div>

<div align="justify">

### Hasil
Hasil dari praktikum ini adalah sebagai berikut:
-	[x] Berhasil menginstal dan mengkonfigurasi Oracle VM VirtualBox pada komputer host.
-	[x] Berhasil membuat mesin virtual baru dengan spesifikasi yang sesuai untuk Ubuntu:
    - Alokasi RAM: 5199 MB
    -	Alokasi penyimpanan: 20 GB
    -	Jumlah core prosesor: 1
-	[x] Berhasil menginstal Ubuntu 24.04 LTS pada mesin virtual yang telah dibuat.
-	[x] Berhasil melakukan konfigurasi awal Ubuntu, termasuk:
    -	Pemilihan bahasa dan zona waktu
    -	Pembuatan akun pengguna
    -	Pengaturan koneksi jaringan
-	[x] Berhasil melakukan boot ke sistem operasi Ubuntu yang baru diinstal dan memverifikasi fungsionalitas dasarnya.

### Pembahasan
-	Persiapan dan Konfigurasi VirtualBox:\
Penggunaan VirtualBox memungkinkan instalasi Ubuntu tanpa mempengaruhi sistem operasi host. Ini memberikan lingkungan yang aman untuk eksperimen dan pembelajaran. Alokasi sumber daya (RAM, penyimpanan, core prosesor) harus dipertimbangkan dengan cermat untuk memastikan kinerja yang optimal dari sistem virtual.

-	Proses Instalasi Ubuntu:\
Instalasi Ubuntu berjalan lancar tanpa kendala signifikan. Antarmuka instalasi Ubuntu yang user-friendly memudahkan proses, bahkan bagi pengguna yang baru mengenal Linux. Pemilihan opsi "Try or Install Ubuntu" memungkinkan pengguna untuk mencoba sistem sebelum melakukan instalasi penuh, yang merupakan fitur yang berguna untuk pengenalan awal.

-	Konfigurasi Sistem:\
Proses konfigurasi awal Ubuntu, termasuk pemilihan bahasa, pengaturan zona waktu, dan pembuatan akun pengguna, berjalan dengan baik. Ini mendemonstrasikan fleksibilitas Ubuntu dalam menyesuaikan dengan kebutuhan pengguna dari berbagai latar belakang dan lokasi geografis.

-	Performa Sistem:\
Setelah instalasi, Ubuntu berjalan dengan baik di lingkungan virtual. Meskipun ada sedikit penurunan performa dibandingkan dengan instalasi pada hardware langsung, hal ini wajar dalam lingkungan virtualisasi. Penggunaan Guest Additions VirtualBox dapat meningkatkan performa dan integrasi antara sistem host dan guest.

-	Pembelajaran dan Implikasi:\
Praktikum ini memberikan wawasan berharga tentang proses instalasi sistem operasi dan manajemen sumber daya komputer. Mahasiswa dapat melihat secara langsung bagaimana sistem operasi diinstal dan dikonfigurasi, yang penting untuk pemahaman yang lebih dalam tentang cara kerja sistem operasi.

-	Tantangan dan Solusi:\
Beberapa tantangan yang mungkin dihadapi termasuk masalah kompatibilitas hardware virtual dan alokasi sumber daya yang tidak mencukupi. Solusinya melibatkan penyesuaian pengaturan VirtualBox dan alokasi sumber daya yang tepat.

-	Penerapan Konsep Sistem Operasi:\
Praktikum ini mengilustrasikan konsep-konsep penting dalam sistem operasi seperti manajemen memori, penjadwalan prosesor, dan sistem file. Mahasiswa dapat melihat bagaimana konsep-konsep ini diterapkan dalam konteks nyata instalasi dan konfigurasi sistem.


</div>

<div align="center">
<br>
<br>

## Kesimpulan

</div>

<div align="justify">

- Praktikum instalasi Ubuntu pada mesin virtual memberikan pengalaman hands-on yang berharga dalam manajemen sistem operasi dan virtualisasi. Melalui proses ini, mahasiswa memperoleh pemahaman praktis tentang konsep-konsep kunci seperti alokasi sumber daya, partisi disk, dan konfigurasi sistem. Penggunaan VirtualBox mendemonstrasikan keuntungan virtualisasi dalam pembelajaran dan eksperimen sistem operasi.
- Keberhasilan instalasi Ubuntu menunjukkan kemampuan mahasiswa dalam menerapkan pengetahuan teoritis ke dalam praktek nyata. Pengalaman ini juga memperkenalkan mahasiswa pada ekosistem open-source, yang penting dalam pengembangan software modern.
- Keterampilan yang diperoleh dari praktikum ini akan sangat bermanfaat dalam studi lanjutan tentang sistem operasi, jaringan komputer, dan pengembangan software. Selain itu, pemahaman tentang sistem Linux seperti Ubuntu semakin relevan dalam industri teknologi informasi saat ini.

</div>

<div align="center">
<br>
<br>

## Daftar Pustaka

</div>

<div align="justify">

- Praktikum 1	Sistem Operasi Linux
- Canonical Ltd. (2024). Ubuntu Desktop for developers. https://ubuntu.com/desktop/developers
- Oracle Corporation. (2024). Oracle VM VirtualBox User Manual. https://www.virtualbox.org/manual/
- Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). Operating System Concepts (10th ed.). Wiley.
- Tanenbaum, A. S., & Bos, H. (2014). Modern Operating Systems (4th ed.). Peason.
- Ubuntu Documentation Team. (2024). Ubuntu Server Guide. https://ubuntu.com/server/docs

</div>

----
<br>
<br>

# Soal 2
[←    BACK](#praktikum-1---sistem-operasi)

## Informasi Mahasiswa
- **Nama:** M. Syaiful Karomah
- **NIM:** 09011282328111
- **Kelas:** SK3C

<br>

<div asign= "justify">

## Analisislah pada gambar kenapa saat instalasi perlu dipilih "/" pada opsi **mount point**?

![Mount Point Selection](https://github.com/SyaifulKaromah/foto-repo/blob/e433532cee5da6d4afdc9639eebc9ae06a79300b/Mount.png)

<br>

## Jawaban

Ada beberapa alasan mengapa saat instalasi perlu dipilih "/" pada opsi **mount point**:

1. Tanda "/" merupakan direktori root, yang mana merupakan tempat tertinggi dalam struktur sistem file. Jadi, ketika dipilih "/" sebagai mount point, maka sebenarnya kita memasang sistem operasi di direktori root.

2. Pilihan "/" membuat kita bisa mengakses semua file dan folder di System. Misalnya ketika ingin membuka file di Desktop, Jalur lengkapnya adalah "/Desktop". Jadi dengan di pilihnya "/" sebagai mount point, maka semua jalur file dapat diakses dengan mudah.

3. Karena hampir semua distribusi Linux menggunakan "/" sebagai direktori root.

</div>

----
<br>
<br>

# Soal 3
[←    BACK](#praktikum-1---sistem-operasi)

## Informasi Mahasiswa
- **Nama:** M. Syaiful Karomah
- **NIM:** 09011282328111
- **Kelas:** SK3C

<br>

<div align="Justify">

## Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs ! 

<br>

## Jawab:

**1. ext4:**
  - Penerus dari ext3 dengan peningkatan performa dan fitur
  - Mendukung volume dan file berukuran sangat besar
  - Memiliki fitur journaling untuk mencegah kerusakan data

**2. ext3:**
  - Versi sebelumnya dari ext4
  - Menambahkan fitur journaling ke ext2
  - Kompatibel dengan ext2 dan ext4

**3. swap:**
  - Bukan sistem file, melainkan ruang pada hard drive yang digunakan sebagai memori virtual
  - Membantu sistem ketika RAM fisik penuh

**4. NTFS:**
  - New Technology File System, dikembangkan oleh Microsoft
  - Digunakan pada sistem operasi Windows modern
  - Mendukung fitur keamanan, kompresi, dan enkripsi

**5. FAT32:**
  - File Allocation Table 32-bit
  - Sistem file lama namun masih kompatibel dengan banyak perangkat
  - Memiliki batasan ukuran file maksimal 4GB

</dir>

**6. Btrfs:**
  - B-tree File System, dikembangkan untuk Linux
  - Menawarkan fitur canggih seperti snapshots, kompresi, dan RAID
  - Fokus pada toleransi kesalahan dan kemudahan pengelolaan penyimpanan
