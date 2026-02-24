# Sistem Operasi 

<h4>Nama : Rakha Madani Rizkullah<h4>  
<h4>NIM : 254107020073<h4>
<h4>Kelas : TI-1H<h4>

## 1.10.1 Latihan Konseptual

### Pertanyaan
1. Jelaskan 5 fungsi utama sistem operasi dengan contoh komkret dari minimal 2 OS berbeda ( Widndows, macOS, atau Linux)
2. Kapan sebaiknya menggunakan Windows vs Linux vs macOS? Analisis
berdasarkan use case: gaming, development, server, creative work, dan enterprise.

### Jawaban 
1. - Manajemen Proses
Fungsi:
Mengatur jalannya program yang sedang berjalan (process), termasuk menjalankan, menghentikan, dan mengatur prioritasnya.

Contoh:
Microsoft Windows → Menggunakan Task Manager untuk melihat dan mengakhiri proses seperti Google Chrome atau game yang tidak merespons.
Ubuntu (Linux) → Menggunakan perintah top, htop, atau kill di Terminal untuk memantau dan menghentikan proses.

- Manajemen Memori
Fungsi:
Mengatur penggunaan RAM agar setiap program mendapat alokasi memori yang cukup tanpa saling mengganggu.

Contoh:
Microsoft Windows → Menggunakan Virtual Memory (paging file) ketika RAM hampir penuh.
Ubuntu → Menggunakan sistem swap memory untuk membantu RAM saat kapasitas hampir habis.

- Manajemen Sistem File
Fungsi:
Mengatur penyimpanan data dalam bentuk file dan folder.

Contoh:
Microsoft Windows → Menggunakan sistem file NTFS dan mengelola file melalui File Explorer.
Ubuntu → Menggunakan sistem file seperti ext4 dan mengelola file melalui Files (Nautilus) atau Terminal.

- Manajemen Perangkat Keras (Device Management)
Fungsi:
Mengontrol dan menghubungkan perangkat keras seperti printer, keyboard, mouse, dan flashdisk melalui driver.

Contoh:
Microsoft Windows → Menginstal driver otomatis saat printer atau mouse baru dicolokkan.
Ubuntu → Banyak driver sudah otomatis terpasang (plug and play), atau dapat ditambahkan melalui Software & Updates.

- Keamanan dan Hak Akses
Fungsi:
Mengatur keamanan sistem dan hak akses pengguna terhadap file atau program.

Contoh:
Microsoft Windows → Memiliki fitur User Account Control (UAC) untuk membatasi perubahan sistem.
Ubuntu → Menggunakan sistem izin akses (permission) seperti chmod dan sudo untuk membatasi akses administrator.

2. - dalam gaming lebih baik menggunakan windows karena mayoritas game dibuat untuk windows, sedangkan pada macOS pilihan game sangat terbatas dan pada linux terdapat game yang tidak cocok untuk linux

- dalam software development disarankan memakai linux karena open source dan gratis

- dalam server creative work lebih baik menggunakan linux karena linux dikenal sangat handal dalam menangani beban kerja berat serta uptime yang panjang tanpa memerlukan reboot


## 1.10.2 Latihan Praktikal

### Latihan 1.3
1. Download Ubuntu Server ISO dari website resmi
2. Create VM baru di VirtualBox (RAM: 2GB, Disk: 25GB)
3. Install dengan automatic partitioning (guided)
4. Buat user account dengan password yang kuat
5. Reboot dan login ke sistem
6. Dokumentasikan proses instalasi dengan screenshot key step

### Jawaban Latihan 1.3
<img width="1000" height="650" alt="Ubuntu" src="https://github.com/user-attachments/assets/333618ba-bb9b-4362-aaa7-30ea502c70d3" />

### Latihan 1.4 
1. Update package list: sudo apt update
2. Upgrade packages: sudo apt upgrade
3. Install neofetch: sudo apt install neofetch
4. Jalankan neofetch dan screenshot hasilnya
5. Check disk usage dengan df -h
6. Check memory dengan free -h
7. Dokumentasikan output dari setiap command

### Jawaban Latihan 1.4
1.
 <img width="300" height="250" alt="Screenshot 2026-02-25 010226" src="https://github.com/user-attachments/assets/d966f578-cda4-4d38-bb9b-8924f7bb9a2f" />
 
2. 
<img width="300" height="250" alt="Screenshot 2026-02-25 010255" src="https://github.com/user-attachments/assets/8e1d3f33-18b0-4d47-9b3a-2e2589a04db8" />

4.
<img width="400" height="350" alt="Screenshot 2026-02-25 010539" src="https://github.com/user-attachments/assets/d8a4268f-b5d5-4319-aa01-340972cd2285" />

5. 
<img width="300" height="250" alt="Screenshot 2026-02-25 012607" src="https://github.com/user-attachments/assets/24863e78-8a13-4793-abe2-6c678f7b3c00" />

6. 
<img width="300" height="250" alt="Screenshot 2026-02-25 013002" src="https://github.com/user-attachments/assets/83a7dc4c-878b-497e-bba8-55e577d78071" />

### Latihan 1.5
1. Tampilkan informasi OS: cat /etc/os-release
2. Tampilkan versi kernel: uname -r
3. List partisi: lsblk
4. Check network connectivity: ping -c 4 google.com
5. Install dan jalankan htop untuk melihat resource usage
6. Buat laporan singkat tentang konfigurasi sistem Anda

### Jawaban Latihan 1.5
- cat /etc/os-release, digunakan untuk menunjukan versi ubuntu yan gdugunakan
- uname -r, digunakan untuk menunjukan versi kernela linux yang aktif
- lasbl, digunakan untuk menampilkan informasi disk dan partisi yang terpasang
- ping -c 4 google, digunakan untuk memeriksa koneksi internet
- htop, digunakan untuk menampilkan penggunaan CPU, RAM, Swap, proses yang berjalan

## Latihan Refleksi

### Latihan 1.6
1. Sistem operasi apa yang Anda gunakan sehari-hari? (Windows, macOS,
Linux, atau lainnya)
2. Berapa lama Anda menggunakan sistem operasi tersebut?
3. Apa yang Anda sukai dari sistem operasi tersebut?
4. Apa tantangan atau masalah yang pernah Anda hadapi?
5. Apakah Anda pernah menggunakan sistem operasi lain? Bandingkan
pengalaman Anda.
6. Setelah mempelajari bab ini, apakah ada sistem operasi lain yang ingin
Anda coba? Mengapa?

### Jawaban Latihan 1.6
1. Saya menggunakan sistem operasi windows
2. Saya sudah menggunakan windows sejak saya menggunakan laptop ayah saya, dan laptop saya sendiri yang baru saya beli sekitar 6 bulan juga menggunakan windows
3. Yang saya sukai dari windows yaitu terdapat banyak game yang bisa dimainkan di windows dan juga lebih optimal dibandingkan dengan sistem operasi yang lain
4. Masalah yang pernah saya hadapi yaitu saat saya sedang memakai laptop untuk membuat tugas, laptop saya tiba tiba melakukan restart secara otomati yang membuat saya sangat terganggu oleh hal tersebut, lalu saya laptop saya juga pernah mengalami restart ulang saat saya sedang melaksanakan ujian
5. Saya belum pernah menggunakan sistem operasi lain tetapi salah terdapat satu teman saya yang menggunakan linux, dan dari apa yang saya lihat, terkadang teman saya bingung untuk mendownload suatu aplikasi dengan versi linux 
6. Saya belum berpikir untuk mencoba sistem operasi lain, tetapi saya sedikit penasaran untuk mencoba sistem operasi linux


