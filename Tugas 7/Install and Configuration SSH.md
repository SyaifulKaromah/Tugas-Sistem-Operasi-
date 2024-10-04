[←    BACK](https://github.com/SyaifulKaromah/Tugas-Sistem-Operasi-/blob/main/README.md)

# Tugas 7
## Informasi Mahasiswa
**Nama: M. Syaiful Karomah**\
**NIM: 090112823828111**\
**Kelas: SK3C**
<br>
<div align="Center">
  
## INSTALL AND CONFIGURATION SSH

</div>

### Prepare Ubuntu
Langkah pertama yang perlu dilakukan adalah mempersiapkan Ubuntu dengan cara:
```
sudo apt update && apt upgarade
```

  ![Prepare Ubuntu](https://github.com/user-attachments/assets/56e1da06-23ea-4b97-a514-763fddd0223e)

<br>

### Install SSH on Ubuntu
Selanjutnya lakukan penginstallan SSH di Ubuntu, disini saya menggunakan Ubuntu 22.04 
```
sudo apt install openssh-server
```
   ![Install SSH](https://github.com/user-attachments/assets/a5f0e693-fc2c-4401-898c-c0d284bbf146)

<br>

### Start SSH
Mulai program SSh
```
sudo systemctl enable --now ssh
```
   ![Start](https://github.com/user-attachments/assets/45dc9bc5-ebbe-4ceb-a33c-029c36aa2771)

Cek status
```
sudo systemctl status ssh
```
   ![ssh Status](https://github.com/user-attachments/assets/f783c950-0daa-4e4b-8e82-25b5c2931cf0)

<br>

### Configuration The Firewall
Cek UFW status
```
sudo ufw status
```
   ![UFW Status Inactive](https://github.com/user-attachments/assets/1882b74b-3d6a-4e97-8d76-3bf5942f6b94)

Jika status UFW inactive seperti di kasus ini, maka kita dapat mengaktifkan dengan:
```
sudo ufw enable
```
   ![UFW Status Active](https://github.com/user-attachments/assets/719657d3-9de9-4bdc-82a4-8274c1a2b053)

Selanjutnya izinkan lalu lintas SSH
```
sudo ufw allow ssh
```
   ![allow SSH](https://github.com/user-attachments/assets/bda85d68-861a-4ec9-8b8f-083156db4085)

<br>

### Connect to The Server
Sambungkan ke server sendiri dengan user dan ip sendiri
```
ssh syf@192.168.49.179
```
   ![syf@192.168.49.179](https://github.com/user-attachments/assets/a35538df-635e-4129-9549-7867c22fc10a)


Selanjutnya coba untuk menghubungkan kepada komputer lain dengan user mereka dan ip mereka, pastikan dalam satu jaringan yang sama:
```
ssh anggaa17@192.168.49.129
```
   ![anggaa17@192.168.49.129](https://github.com/user-attachments/assets/05e44535-099c-4856-85cc-f1f7bde19c23)

### Configuration SSH
Cadangkan dahulu file sshd_config
```
sudo cp /etc/ssh/sshd_config /etc/ssh/sshd_config.initial
```

Lalu edit file konfigurasinya
```
sudo nano /etc/ssh/sshd_config
```

Hilangkan pagar pada Port, PubkeyAuthentication dan PermitRootLogin, untuk baris PermitRootLogin ubah menjadi PermitRootLogin no

  ![Screenshot from 2024-10-04 11-40-21](https://github.com/user-attachments/assets/162d6160-72b2-4b34-9010-bb7a6415b3a2)

Sekarang coba untuk merestart SSH
```
sudo systemctl restart ssh
```

Lalu coba untuk menjalankan ssh lagi dengan port yang dikonfigurasi tadi
```
ssh -p 22 syf@192.168.185.179
```   
   ![Screenshot from 2024-10-04 11-41-51](https://github.com/user-attachments/assets/48bda3e9-ace9-451c-ae32-768483677345)