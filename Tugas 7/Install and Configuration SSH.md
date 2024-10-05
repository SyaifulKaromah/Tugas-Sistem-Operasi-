Here's the reformatted version with indented code blocks and images:

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
* Update dan upgrade sistem Ubuntu
    ```
    sudo apt update && apt upgarade
    ```
    ![Prepare Ubuntu](https://github.com/user-attachments/assets/56e1da06-23ea-4b97-a514-763fddd0223e)

### Install SSH on Ubuntu
* Install OpenSSH server pada Ubuntu 22.04
    ```
    sudo apt install openssh-server
    ```
    ![Install SSH](https://github.com/user-attachments/assets/a5f0e693-fc2c-4401-898c-c0d284bbf146)

### Start SSH
* Aktifkan layanan SSH
    ```
    sudo systemctl enable --now ssh
    ```
    ![Start](https://github.com/user-attachments/assets/45dc9bc5-ebbe-4ceb-a33c-029c36aa2771)

* Periksa status layanan SSH
    ```
    sudo systemctl status ssh
    ```
    ![ssh Status](https://github.com/user-attachments/assets/f783c950-0daa-4e4b-8e82-25b5c2931cf0)

### Configuration The Firewall
* Periksa status UFW
    ```
    sudo ufw status
    ```
    ![UFW Status Inactive](https://github.com/user-attachments/assets/1882b74b-3d6a-4e97-8d76-3bf5942f6b94)

* Aktifkan UFW jika statusnya inactive
    ```
    sudo ufw enable
    ```
    ![UFW Status Active](https://github.com/user-attachments/assets/719657d3-9de9-4bdc-82a4-8274c1a2b053)

* Izinkan lalu lintas SSH
    ```
    sudo ufw allow ssh
    ```
    ![allow SSH](https://github.com/user-attachments/assets/bda85d68-861a-4ec9-8b8f-083156db4085)

### Connect to The Server
* Hubungkan ke server lokal
    ```
    ssh syf@192.168.49.179
    ```
    ![syf@192.168.49.179](https://github.com/user-attachments/assets/a35538df-635e-4129-9549-7867c22fc10a)

* Hubungkan ke komputer lain dalam jaringan yang sama
    ```
    ssh anggaa17@192.168.49.129
    ```
    ![anggaa17@192.168.49.129](https://github.com/user-attachments/assets/05e44535-099c-4856-85cc-f1f7bde19c23)

### Configuration SSH
* Buat cadangan file konfigurasi SSH
    ```
    sudo cp /etc/ssh/sshd_config /etc/ssh/sshd_config.initial
    ```

* Edit file konfigurasi SSH
    ```
    sudo nano /etc/ssh/sshd_config
    ```
    ![nano ssh_config](https://github.com/user-attachments/assets/162d6160-72b2-4b34-9010-bb7a6415b3a2)

* Mulai ulang layanan SSH
    ```
    sudo systemctl restart ssh
    ```

* Uji koneksi SSH dengan port yang dikonfigurasi
    ```
    ssh -p 22 syf@192.168.185.179
    ```   
    ![menjalankan ssh kembali](https://github.com/user-attachments/assets/48bda3e9-ace9-451c-ae32-768483677345)
