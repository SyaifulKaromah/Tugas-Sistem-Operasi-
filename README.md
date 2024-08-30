# LAPORAN PRAKTIKUM SISTEM OPERASI

## FSK2108

### PROSES INTSALLASI SISTEM OPERASI UBUNTU

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
Dalam era komputasi modern, pemahaman dan keterampilan dalam menginstal dan mengoperasikan berbagai sistem operasi menjadi semakin penting. Salah satu sistem operasi yang mendapat perhatian khusus adalah Ubuntu, sebuah distribusi Linux yang terkenal dengan keamanan, stabilitas, dan kemudahan penggunaannya. Ubuntu menawarkan alternatif yang kuat dan fleksibel terhadap sistem operasi proprietary, memberikan pengguna kontrol penuh atas lingkungan komputasi mereka.

[Latar belakang lengkap...]

### Tujuan
- Memahami proses instalasi sistem operasi Ubuntu pada lingkungan virtual menggunakan VirtualBox.
- Mempraktikkan langkah-langkah konfigurasi awal sistem operasi Ubuntu, termasuk pengaturan bahasa, zona waktu, dan akun pengguna.
- Mengeksplorasi antarmuka grafis Ubuntu dan membiasakan diri dengan lingkungan desktop Linux.
- Mendapatkan pengalaman hands-on dalam manajemen sumber daya virtual seperti alokasi RAM, penyimpanan, dan core prosesor.
- Meningkatkan pemahaman tentang konsep virtualisasi dan manfaatnya dalam pembelajaran sistem operasi.
- Mempersiapkan lingkungan kerja yang aman untuk eksperimen dan pembelajaran lebih lanjut tentang sistem operasi Linux tanpa mempengaruhi sistem utama.

### Landasan Teori
- Sistem operasi adalah perangkat lunak sistem yang mengelola sumber daya perangkat keras dan perangkat lunak komputer.
- Linux adalah keluarga sistem operasi open-source berbasis Unix yang dikembangkan oleh Linus Torvalds pada tahun 1991.
- Virtualisasi memungkinkan beberapa sistem operasi berjalan pada satu mesin fisik.
- Proses instalasi sistem operasi melibatkan beberapa tahap kritis, termasuk partisi disk, instalasi bootloader, dan konfigurasi sistem.
- Filosofi open-source, seperti yang diterapkan dalam pengembangan Ubuntu, mendorong transparansi, kolaborasi, dan inovasi dalam pengembangan software.

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
5. Tentukan besaran ram dan core prossesor
6. Tentukan besaran Penyimpanan yang akan di alokasikan
7. Masukkan ISO Ubuntu 24.04
8. Try or Install Ubuntu
9. Tunggu Proses Booting
10. Next
11. Pasang Ubuntu
12. Masukkan Identitas yang diperlukan dan Password
13. Klik "Mulai Memasang"
14. Tunggu Proses Installasi selesai
15. Kemudian, "Restart now"
16. Ubuntu telah selesai di install

## Hasil dan Pembahasan

### Hasil
- Berhasil menginstal dan mengkonfigurasi Oracle VM VirtualBox pada komputer host.
- Berhasil membuat mesin virtual baru dengan spesifikasi yang sesuai untuk Ubuntu:
  - Alokasi RAM: 5199 MB
  - Alokasi penyimpanan: 20 GB
  - Jumlah core prosesor: 1
- Berhasil menginstal Ubuntu 24.04 LTS pada mesin virtual yang telah dibuat.
- Berhasil melakukan konfigurasi awal Ubuntu, termasuk:
  - Pemilihan bahasa dan zona waktu
  - Pembuatan akun pengguna
  - Pengaturan koneksi jaringan
- Berhasil melakukan boot ke sistem operasi Ubuntu yang baru diinstal dan memverifikasi fungsionalitas dasarnya.

### Pembahasan
- Persiapan dan Konfigurasi VirtualBox
- Proses Instalasi Ubuntu
- Konfigurasi Sistem
- Performa Sistem
- Pembelajaran dan Implikasi
- Tantangan dan Solusi
- Penerapan Konsep Sistem Operasi

[Pembahasan lengkap...]

## Kesimpulan
Praktikum instalasi Ubuntu pada mesin virtual memberikan pengalaman hands-on yang berharga dalam manajemen sistem operasi dan virtualisasi. Melalui proses ini, mahasiswa memperoleh pemahaman praktis tentang konsep-konsep kunci seperti alokasi sumber daya, partisi disk, dan konfigurasi sistem. Penggunaan VirtualBox mendemonstrasikan keuntungan virtualisasi dalam pembelajaran dan eksperimen sistem operasi.

[Kesimpulan lengkap...]

## Daftar Pustaka
- Praktikum 1 Sistem Operasi Linux
- Canonical Ltd. (2024). Ubuntu Desktop for developers. https://ubuntu.com/desktop/developers
- Oracle Corporation. (2024). Oracle VM VirtualBox User Manual. https://www.virtualbox.org/manual/
- Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). Operating System Concepts (10th ed.). Wiley.
- Tanenbaum, A. S., & Bos, H. (2014). Modern Operating Systems (4th ed.). Pearson.
- Ubuntu Documentation Team. (2024). Ubuntu Server Guide. https://ubuntu.com/server/docs


# Analisis Pemilihan Mount Point Saat Instalasi

## Informasi Mahasiswa
- **Nama:** M. Syaiful Karomah
- **NIM:** 09011282328111
- **Kelas:** SK3C

### Soal 2
Analisislah pada gambar kenapa saat instalasi perlu dipilih "/" pada opsi **mount point**?

![Mount Point Selection](https://raw.githubusercontent.com/yourusername/your-repo-name/main/images/mount-point-selection.png)

## Jawaban

Ada beberapa alasan mengapa saat instalasi perlu dipilih "/" pada opsi **mount point**:

1. Tanda "/" merupakan direktori root, yang mana merupakan tempat tertinggi dalam struktur sistem file. Jadi, ketika dipilih "/" sebagai mount point, maka sebenarnya kita memasang sistem operasi di direktori root.

2. Pilihan "/" membuat kita bisa mengakses semua file dan folder di System. Misalnya ketika ingin membuka file di Desktop, Jalur lengkapnya adalah "/Desktop". Jadi dengan di pilihnya "/" sebagai mount point, maka semua jalur file dapat diakses dengan mudah.

3. Karena hampir semua distribusi Linux menggunakan "/" sebagai direktori root.

## Catatan
- Pastikan untuk mengganti `yourusername` dan `your-repo-name` pada URL gambar dengan username GitHub Anda dan nama repository yang sesuai.
- Jika gambar disimpan di lokasi yang berbeda, sesuaikan path URL-nya.

## Lisensi
[Masukkan informasi lisensi jika ada]

## Kontak
Jika Anda memiliki pertanyaan, silakan hubungi [Masukkan informasi kontak Anda]
