# Sistem Operasi 

<h4>Nama : Rakha Madani Rizkullah<h4>  
<h4>NIM : 254107020073<h4>
<h4>Kelas : TI-1H<h4>

## Praktikum 1
Konteks riil: seorang administrator sering mengulang perintah yang sama setiap hari. Agar pekerjaan lebih efisien dan konsisten, ia perlu memiliki toolkit Bash pribadi otomatis yang
aktif setiap login.

Instruksi tugas:
1. Tambahkan konfigurasi pada .bashrc untuk:
• menambahkan direktori bin pribadi ke PATH,
• membuat minimal 2 alias yang membantu kerja harian,
• membuat minimal 1 fungsi shell yang berguna untuk administrasi.
2. Pastikan konfigurasi tersebut aktif kembali saat membuka shell login.
3. Buat satu script sederhana di direktori bin pribadi, misalnya script untuk menampilkan ringkasan sistem.
4. Uji dari direktori yang berbeda untuk memastikan script dapat dipanggil tanpa menuliskan path lengkap.
5. Simpan bukti pengujian ke file toolkit-bash-report.txt

Minimal luaran:
• isi blok konfigurasi yang ditambahkan ke .bashrc,
• output echo $PATH,
• output type untuk alias, fungsi, dan script,
• file laporan toolkit-bash-report.txt.

<img width="901" height="731" alt="Screenshot 2026-04-14 211343" src="https://github.com/user-attachments/assets/ad0c20f8-028b-42e4-884c-aff81fe9a115" />
<img width="536" height="137" alt="Screenshot 2026-04-14 211822" src="https://github.com/user-attachments/assets/ad0e5ae3-c073-49ef-ac7f-3e2db81e6471" />
<img width="495" height="175" alt="Screenshot 2026-04-14 212617" src="https://github.com/user-attachments/assets/038f9ddf-5076-4a58-bc32-92348f891a97" />
<img width="510" height="227" alt="Screenshot 2026-04-14 212954" src="https://github.com/user-attachments/assets/e42fd6db-c228-4a93-95a9-aaf441413a24" />
<img width="636" height="30" alt="Screenshot 2026-04-14 213810" src="https://github.com/user-attachments/assets/81462f9f-aabd-4375-841f-81afac5545a2" />

## Praktikum 2
Konteks riil: saat troubleshooting, administrator sering perlu menginventarisasi file konfigurasi dan memisahkan output normal dari pesan error.

Instruksi tugas:
1. Buat file laporan bernama audit-konfigurasi-$(date +%F).txt.
2. Cari file *.conf di dalam /etc dan simpan hasilnya ke file laporan.
3. Catat jumlah total file konfigurasi yang ditemukan.
4. Jika ada pesan error, simpan ke file terpisah, misalnya audit-error.log.
5. Tampilkan isi laporan ke terminal dan sekaligus simpan menggunakan tee.
6. Tambahkan ringkasan singkat 3–5 baris yang menjelaskan mengapa pemisahan
stdout dan stderr penting dalam audit sistem.

Syarat konsep yang harus muncul:
• redirection >, 2>, atau &>,
• pipeline,
• tee,
• penggunaan variabel atau command substitution.
Minimal luaran:
• file laporan audit,
• file log error,
• perintah yang digunakan,
• analisis singkat hasil audit.

<img width="868" height="614" alt="aaaa" src="https://github.com/user-attachments/assets/efa3a818-c234-4675-98f5-ac041a7f3652" />
<img width="516" height="101" alt="image" src="https://github.com/user-attachments/assets/bfbc26a2-c7bd-4737-b993-2b0788c13894" />

## Praktikum 3
Konteks riil: administrator perlu membuat pemeriksaan cepat (health check) untuk mengetahui kondisi dasar server sebelum dan sesudah maintenance.

Instruksi tugas:
1. Buat script Bash bernama daily-healthcheck pada direktori bin pribadi.
2. Script minimal harus menampilkan:
• tanggal dan waktu,
• hostname,
• user aktif,
• shell aktif,
• uptime,
• penggunaan memori,
• penggunaan filesystem root,
• 10 baris terakhir history command yang relevan dengan pengecekan.
3. Simpan hasil ke file log harian, misalnya healthcheck-$(date +%F).log.
4. Tampilkan hasil ke terminal dan ke file secara bersamaan.
5. Jika Anda menggunakan pipeline dengan tee, cek juga status exit command utama.
Syarat konsep yang harus muncul:
• environment variable,
• PATH,
• alias atau fungsi pendukung,
• history,
• tee,
• penanganan error dasar.

Minimal luaran:
• file script yang executable,
• contoh isi file log hasil eksekusi,
• penjelasan singkat fungsi tiap bagian script.
<img width="825" height="222" alt="Screenshot 2026-04-14 230736" src="https://github.com/user-attachments/assets/a1d7a637-831f-4b4a-9997-41464287088c" />
<img width="462" height="240" alt="Screenshot 2026-04-14 230812" src="https://github.com/user-attachments/assets/9217cdd7-2d5b-4fbf-84e8-b1fbd56d585f" />

## Praktikum 4
Konteks riil: file hasil backup, ekspor, atau laporan sering memiliki nama yang mengandung spasi atau karakter khusus. Administrator harus tetap dapat memproses file-file tersebut tanpa salah target.

Instruksi tugas:
1. Buat minimal 4 file contoh dengan nama yang bervariasi, termasuk:
• nama file yang mengandung spasi,
• nama file yang mengandung tanda kurung siku atau karakter khusus,
• file dengan pola nama serupa untuk diuji dengan wildcard.
2. Tunjukkan perbedaan hasil jika file diakses tanpa quoting dan dengan quoting
yang benar.
3. Lakukan preview wildcard dengan echo sebelum dipakai untuk operasi nyata.
4. Salin file-file tersebut ke direktori backup dengan nama yang aman.
5. Buat arsip tar.gz dari hasil backup.
6. Simpan riwayat perintah yang Anda gunakan ke file riwayat-arsip.txt.
Syarat konsep yang harus muncul:
• single quote, double quote, dan escaping,
• wildcard,
• variabel path,
• history,
• operasi file lanjutan yang aman.

Minimal luaran:
• daftar file awal,
• daftar file hasil backup,
• file arsip tar.gz,
• file riwayat-arsip.txt,
• refleksi singkat tentang pentingnya quoting di Bash.

<img width="361" height="63" alt="Screenshot 2026-04-14 233408" src="https://github.com/user-attachments/assets/9ef0d80f-eb96-401d-9ce0-c44d96470b53" />
<img width="496" height="79" alt="Screenshot 2026-04-14 233511" src="https://github.com/user-attachments/assets/fd101844-264f-4e2b-808a-2c3d7f710c5a" />
<img width="345" height="71" alt="Screenshot 2026-04-14 233805" src="https://github.com/user-attachments/assets/bb1163e3-c272-4b73-88ab-2e8d2c1bdd05" />
<img width="906" height="41" alt="Screenshot 2026-04-14 234229" src="https://github.com/user-attachments/assets/c6c7b226-c37e-48a5-a5f2-ecc678ef1244" />
<img width="416" height="92" alt="Screenshot 2026-04-14 234354" src="https://github.com/user-attachments/assets/cbb62fd3-3167-49cd-9fce-5d6c2d67cef0" />
<img width="840" height="270" alt="Screenshot 2026-04-14 234517" src="https://github.com/user-attachments/assets/f8842b3e-db6f-4289-bdbf-51713d2d59df" />






