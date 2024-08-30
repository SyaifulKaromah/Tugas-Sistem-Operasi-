# Soal 1
# LAPORAN PRAKTIKUM SISTEM OPERASI

## FSK2108

### PROSES INTSALLASI SISTEM OPERASI UBUNTU

![Logo Universitas Sriwijaya](https://raw.githubusercontent.com/yourusername/your-repo-name/main/images/unsri-logo.png)

**Dosen Pengampu:**
1. Ahmad Heryanto, M. T.
2. Adi Hermansyah, M. T.
3. Sutarno, M.T.
4. Iman Saladin B. Azhar, S. Kom., M. M.SI.
5. Dr. Ahmad Zarkarsi, M. T.

**Disusun Oleh:**
- Nama: M. Syaiful Karomah
- NIM: 09011282328111
- Hari/Tanggal: Kamis, 29 Agustus 2024

**JURUSAN SISTEM KOMPUTER**  
**FAKULTAS ILMU KOMPUTER**  
**UNIVERSITAS SRIWIJAYA**  
**2024**

## Daftar Isi
- [Pendahuluan](#pendahuluan)
  - [Latar Belakang](#latar-belakang)
  - [Tujuan](#tujuan)
  - [Landasan Teori](#landasan-teori)
- [Alat dan Bahan](#alat-dan-bahan)
  - [Alat](#alat)
  - [Bahan](#bahan)
- [Prosedur](#prosedur)
- [Hasil dan Pembahasan](#hasil-dan-pembahasan)
  - [Hasil](#hasil)
  - [Pembahasan](#pembahasan)
- [Kesimpulan](#kesimpulan)
- [Daftar Pustaka](#daftar-pustaka)

## Pendahuluan

### Latar Belakang
Dalam era komputasi modern, pemahaman dan keterampilan dalam menginstal dan mengoperasikan berbagai sistem operasi menjadi semakin penting. Salah satu sistem operasi yang mendapat perhatian khusus adalah Ubuntu, sebuah distribusi Linux yang terkenal dengan keamanan, stabilitas, dan kemudahan penggunaannya.

[Latar belakang lengkap...]

### Tujuan
- Memahami proses instalasi sistem operasi Ubuntu pada lingkungan virtual menggunakan VirtualBox.
- Mempraktikkan langkah-langkah konfigurasi awal sistem operasi Ubuntu.
- Mengeksplorasi antarmuka grafis Ubuntu dan membiasakan diri dengan lingkungan desktop Linux.
- [Tujuan lainnya...]

### Landasan Teori
- Sistem operasi adalah perangkat lunak sistem yang mengelola sumber daya perangkat keras dan perangkat lunak komputer.
- Linux adalah keluarga sistem operasi open-source berbasis Unix yang dikembangkan oleh Linus Torvalds pada tahun 1991.
- [Teori lainnya...]

## Alat dan Bahan

### Alat
Oracle VM VirtualBox

### Bahan
- File ISO Ubuntu Versi 24.04
- Komputer Host
- Ruang Penyimpanan
- Koneksi Internet
- Memori RAM

## Prosedur

1. Siapkan File ISO Ubuntu Versi 24.04
2. Buka Virtual Box
3. Tekan Tombol Baru
4. Tuliskan Nama, tentukan folder penyimpanan, kemudian Lanjut

   ![Langkah 4](https://raw.githubusercontent.com/yourusername/your-repo-name/main/images/step4.png)

5. Tentukan besaran ram dan core prossesor

   ![Langkah 5](https://raw.githubusercontent.com/yourusername/your-repo-name/main/images/step5.png)

6. Tentukan besaran Penyimpanan yang akan di alokasikan

   ![Langkah 6](https://raw.githubusercontent.com/yourusername/your-repo-name/main/images/step6.png)

7. Masukkan ISO Ubuntu 24.04

   ![Langkah 7](https://raw.githubusercontent.com/yourusername/your-repo-name/main/images/step7.png)

8. Try or Install Ubuntu

   ![Langkah 8](https://raw.githubusercontent.com/yourusername/your-repo-name/main/images/step8.png)

9. Tunggu Proses Booting
10. Next
11. Pasang Ubuntu
12. Masukkan Identitas yang diperlukan dan Password
13. Klik "Mulai Memasang"
14. Tunggu Proses Installasi selesai
15. Kemudian, "Restart now"
16. Ubuntu telah selesai di install

   ![Langkah 16](https://raw.githubusercontent.com/yourusername/your-repo-name/main/images/step16.png)

## Hasil dan Pembahasan

### Hasil
- Berhasil menginstal dan mengkonfigurasi Oracle VM VirtualBox pada komputer host.
- Berhasil membuat mesin virtual baru dengan spesifikasi yang sesuai untuk Ubuntu.
- Berhasil menginstal Ubuntu 24.04 LTS pada mesin virtual yang telah dibuat.
- [Hasil lainnya...]

### Pembahasan
- Persiapan dan Konfigurasi VirtualBox
- Proses Instalasi Ubuntu
- Konfigurasi Sistem
- [Pembahasan lainnya...]

## Kesimpulan
Praktikum instalasi Ubuntu pada mesin virtual memberikan pengalaman hands-on yang berharga dalam manajemen sistem operasi dan virtualisasi. Melalui proses ini, mahasiswa memperoleh pemahaman praktis tentang konsep-konsep kunci seperti alokasi sumber daya, partisi disk, dan konfigurasi sistem.

[Kesimpulan lengkap...]

## Daftar Pustaka
- Praktikum 1 Sistem Operasi Linux
- Canonical Ltd. (2024). Ubuntu Desktop for developers. https://ubuntu.com/desktop/developers
- Oracle Corporation. (2024). Oracle VM VirtualBox User Manual. https://www.virtualbox.org/manual/
- [Referensi lainnya...]

----

# Soal 2
# Analisis Pemilihan Mount Point Saat Instalasi

## Informasi Mahasiswa
- **Nama:** M. Syaiful Karomah
- **NIM:** 09011282328111
- **Kelas:** SK3C

Analisislah pada gambar kenapa saat instalasi perlu dipilih "/" pada opsi **mount point**?

![Mount Point Selection](https://raw.githubusercontent.com/yourusername/your-repo-name/main/images/mount-point-selection.png)

## Jawaban

Ada beberapa alasan mengapa saat instalasi perlu dipilih "/" pada opsi **mount point**:

1. Tanda "/" merupakan direktori root, yang mana merupakan tempat tertinggi dalam struktur sistem file. Jadi, ketika dipilih "/" sebagai mount point, maka sebenarnya kita memasang sistem operasi di direktori root.

2. Pilihan "/" membuat kita bisa mengakses semua file dan folder di System. Misalnya ketika ingin membuka file di Desktop, Jalur lengkapnya adalah "/Desktop". Jadi dengan di pilihnya "/" sebagai mount point, maka semua jalur file dapat diakses dengan mudah.

3. Karena hampir semua distribusi Linux menggunakan "/" sebagai direktori root.
