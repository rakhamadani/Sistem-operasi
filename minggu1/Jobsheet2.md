# Sistem Operasi

<h4>Nama : Rakha Madani Rizkullah<h4>
<h4>NIM : 254107020073<h4>
<h4>Kelas : TI-1H<h4>

## Praktikum 2.1

### Latihan 2.1
Catat: (1) jumlah CPU(s), core/thread, (2) total RAM, (3) total swap. Jelaskan perbedaan RAM vs swap dalam 2–3 kalimat.

### Jawaban Latihan 2.1
1. jumlah CPU(s) : 1
core/thread : 1
2. total RAM : 1.9 Gi
3. total swap : 2.0 Gi

Perbedaan RAM dan swap : RAM adalah memori utama yang digunakan komputer untuk menyimpan data sementara saat program sedang berjalan, sedangkan  swap adalah ruang di hard disk atau SSD yang digunakan sebagai memori cadangan ketika RAM hampir penuh

## Praktikum 2.2

### Latihan 2.2
Temukan 1 perangkat PCI (misal NIC) dan tuliskan: Vendor:Device ID (angka
heksadesimal), nama driver/modul kernel, dan deskripsi singkat fungsinya

### Jawaban Latihan 2.2
1. PCI : Intel Corporation 82540EM Gigabit Ethernet Controller (rev 02)
2. Vendor:Device ID : 8086:100e
3. modul kernel : 1000e

- Fugsi PCI : jalur komunikasi hardware ke motherboard
- Fungsi Vendor:Device ID : kode unik untuk mengenali perangkat keras
- Modul kernel : driver yang mengontrol perangkat agar bisa digunakan sistem

## Praktikum 2.6

### Latihan 2.3
Dari output ls -l, jelaskan perbedaan penanda file untuk block device dan
character device. (Hint: karakter pertama pada permission string)

### Jawaban Latihan 2.3 
Block device digunakan untuk perangkat yang mentransfer dat dalam bentuk blok/blok besar, sedangkan character device digunakan untuk perangkat yang mentransfer data karakter per karakter 

## Praktikum 2.9

### Latihan 2.4
Gunakan grep untuk menampilkan hanya baris yang mengandung INFO atau
WARN dari data.log. (Hint: gunakan grep -E dengan pola alternatif)

### Jawaban
<img width="350" height="200" alt="image" src="https://github.com/user-attachments/assets/2837ec6d-7a4c-4a8d-9853-822c44530615" />

## Latihan 1.9

### Latihan 2.A
Jalankan lspci -nnk. Pilih 1 perangkat PCI dan tuliskan: nama perangkat, ID vendor:device, dan kernel driver in use.
<img width="300" height="200" alt="Screenshot 2026-03-03 200310" src="https://github.com/user-attachments/assets/d683ad99-8a14-47ee-90db-a4cf63baa4c7" />

### Latihan 2.B
Tentukan device root filesystem dengan findmnt /. Lalu cocokkan dengan lsblk -f dan tuliskan tipe filesystem serta UUID-nya.
<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/bb273fda-b4fe-4aee-9e2e-b5c235810e77" />

### Latihan 2.C
Buat file server.log berisi minimal 10 baris dengan variasi kata: INFO, WARN, ERROR. Gunakan grep untuk menampilkan hanya baris ERROR.
<img width="211" height="171" alt="image" src="https://github.com/user-attachments/assets/dd6da037-1c54-457b-8e36-4264cbdf0acd" />

<img width="200" height="100" alt="image" src="https://github.com/user-attachments/assets/c7efee73-e770-46dc-bd69-62d9cc1f3314" />


### Latihan 2.D
Gunakan sed untuk mengganti semua kata server menjadi node pada file latihan. Tunjukkan sebelum dan sesudah.
<img width="200" height="100" alt="image" src="https://github.com/user-attachments/assets/ad2ac84e-fda1-4468-9551-55c4ecd1e423" />

### Latihan 2.E
Gunakan df -h lalu awk untuk menampilkan filesystem yang penggunaan disk di atas 70%.
<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/2822213a-e182-4f0f-ac29-bb3fcb09715c" />

### Latihan 2.F
Jalankan sleep 600 &. Temukan PID-nya dengan ps. Hentikan dengan SIGTERM. Jelaskan beda SIGTERM vs SIGKILL.
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/0265688f-3d21-4d6d-9cd8-8cc565a26e11" />

perbedaan SIGTERM dan SIGKILL adalah SIGTERM proses diminta berhernti secara baik (bisa cleanup data), sedangkan SIGKILL proses langsung dihentikan paksa (tidak bisa cleanup data)

### Latihan 2.G
Gunakan systemctl –failed. Jika tidak ada yang gagal, pilih satu service aktif (misal ssh) dan tampilkan status serta 30 baris log terakhirnya.
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/33480b6f-b809-4d52-9a33-3034e457312e" />


