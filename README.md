# latihanVSC
Instalasi Git:

Unduh Git dari situs web resmi: https://git-scm.com/downloads
Ikuti instruksi pemasangan yang sesuai untuk sistem operasi Anda.
Konfigurasi Git:

Setel nama pengguna dan alamat email Anda, yang akan digunakan dalam setiap komit Git. Gunakan perintah berikut:
arduino
Copy code
git config --global user.name "Nama Anda"
git config --global user.email "email@example.com"
Membuat Repositori:

Buat direktori baru untuk proyek Anda.
Masuk ke direktori tersebut melalui terminal.
Jalankan perintah berikut untuk inisialisasi repositori Git:
csharp
Copy code
git init
Menambahkan dan Mengommit Perubahan:

Tambahkan file yang ingin Anda ikuti dengan Git menggunakan perintah git add:
csharp
Copy code
git add nama_file
Setelah menambahkan perubahan, komit perubahan tersebut ke repositori dengan perintah git commit:
sql
Copy code
git commit -m "Pesan komit"
Melihat Status:

Untuk melihat status perubahan dalam repositori Anda, gunakan perintah:
lua
Copy code
git status
Melihat Riwayat Perubahan:

Anda dapat melihat riwayat komit menggunakan perintah:
bash
Copy code
git log
Cabang (Branches):

Git memungkinkan Anda untuk bekerja pada cabang berbeda dalam repositori. Untuk membuat dan beralih ke cabang baru, gunakan perintah berikut:
Copy code
git branch nama_cabang
git checkout nama_cabang
Menggabungkan Cabang:

Setelah selesai dengan perubahan di cabang baru, Anda dapat menggabungkannya kembali ke cabang utama dengan perintah:
sql
Copy code
git checkout nama_cabang_utama
git merge nama_cabang
Push dan Pull ke Repositori Jarak Jauh:

Untuk berkolaborasi dengan orang lain, Anda bisa mengunggah (push) perubahan ke repositori jarak jauh dan menarik (pull) perubahan yang ada di repositori jarak jauh. Gunakan perintah git push dan git pull.
Kloning Repositori:

Untuk mengambil salinan repositori yang sudah ada, gunakan perintah:
bash
Copy code
git clone URL_repositori
