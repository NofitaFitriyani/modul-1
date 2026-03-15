<div align="center">
  <br />

  <h1>LAPORAN PRAKTIKUM <br>
  APLIKASI BERBASIS PLATFORM
  </h1>

  <br />

  <h3>MODUL II GIT
  </h3>

  <br />

  <img src="Images/Logo Telkom.png" alt="Logo" width="300">

  <br />
  <br />
  <br />

  <h3>Disusun Oleh :</h3>

  <p>
    <strong>Andreas Besar Wibowo</strong><br>
    <strong>2311102198</strong><br>
    <strong>S1 IF-11-REG01</strong>
  </p>

  <br />

  <h3>Dosen Pengampu :</h3>

  <p>
    <strong>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</strong>
  </p>
  
  <br />
    <h4>Asisten Praktikum :</h4>
    <strong>Apri Pandu Wicaksono </strong> <br>
    <strong>Rangga Pradarrell Fathi</strong>
  <br />

  <h3>LABORATORIUM HIGH PERFORMANCE
 <br>FAKULTAS INFORMATIKA <br>UNIVERSITAS TELKOM PURWOKERTO <br>2026</h3>
</div>

<hr>

## Dasar Teori

### Pengenalan Git
Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds. Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

### Instalasi Git
Untuk menginstall git, anda bisa membuka link berikut ini [Installer Git](https://git-scm.com/download/win) untuk mengunduh Aplikasi Git terlebih dahulu. Setelah berhasil melakukan instalisasi anda dapat mengecek versi git yang sudah ada di laptop anda dengan menggunakan command `git --version`
![Gambar 1](Images/Instalisasi%20Git.png)

### Penggunaan Git
#### 1. Membuat repositori baru
Untuk membuat repositaru baru, gunakan perintah dibawah ini:
```cmd
git init modul-1
```

Perintah `git init` akan membuat sebuah direktori bernama .git di dalam proyek yang akan dikerjakan. Direktori ini digunakan Git sebagai database untuk menyimpan perubahan yang kita lakukan.

#### 2. Menambahkan isi repositori
Untuk menambahkan suatu file ke dalam repositori, kita langsung dapat menambahkan file yang kita inginkan ke dalam folder projek yang telah kita buat.

touch test.txt adalah perintah untuk membuat satu file baru yaitu test.txt, echo “Halo Git” >> test.txt adalah perintah untuk mengisi file test.txt dengan “Halo Git”, lalu gunakan perintah cat test.txt untuk melihat apa isi yang ada pada file test.txt

Namun harus diingat bahwa untracked files menandakan bahwa file tersebut belum disimpan dalam catatan repository kita, untuk menyimpannya, kita bisa menggunakan perintah git add test.txt

Dapat kita lihat bahwa sekarang file test.txt siap untuk disimpan, namun data belum benar-benar tersimpan sampai kita melakukan perintah `git commit -m “pesan commit”`. Setelah perintah `git commit`, maka git akan menyimpan semua perubahan yang ada, dan dapat dilihat dengan menggunakan perintah `git status`.

#### 3. Membuat repositori online
Pada tahap ini kita akan menggunakan tempat penyimpanan repositori online yang cukup popular, yaitu Github untuk menyimpan hasil pekerjaan kita. Pastikan kita sudah memiliki akun Github, dan sudah masuk kedalam akun kalian. Langkah yang harus kalian lakukan adalah sebagai berikut:

1. Buka link berikut ini [Buat Repositori](https://github.com/new)
2. Isi detail dari repository yang akan kalian buat.
3. Lalu klik tombol “Create a repository”.

#### 4. Menyimpan hasil pekerjaan di repositori online
Setelah membuat repositori pada Github, sekarang kita dapat menyimpan hasil pekerjaan yang telah kita buat kedalam Github. Untuk melakukan itu, lakukan langkah-langkah berikut:
1. Ketikan perintah ini, sesuaikan dengan username dan repository Anda: `git remote add origin https://github.com/usernameanda/namarepo.git` Perintah ini akan menambahkan repositori online yang ada pada Github kedalam daftar repositori jarak jauh yang ada.
2. Untuk mengirimkan data yang ada di komputer kalian ke repositori jarak jauh, gunakan perintah ini: `git push -u origin master`

#### 5. Clone repositori milik orang lain  
Untuk dapat bekerja sama dengan orang lain, kita dapat melakukan cloning repositori orang lain, berikut ini caranya:
1. Buka repositori yang akan di-clone pada Github, lalu klik tombol clone.
2. Copy text yang sesuai dengan repositori anda, ini merupakan url dari repositori tujuan yang akan di clone.
3. Buka command prompt dan ketikan perintah ini `git clone [url repositori tujuan]`

## Tugas
### 1. Melakukan setup repository via CLI

### Hasil
1. Kita harus membuat folder terlebih dahulu di File Manager yang berisikan file Txt untuk test
![Hasil 1](Images/Membuat%20Folder%20di%20File%20Manager.png)
2. Kita Buat Repositori pada GitHub terlebih dahulu.
2. Kita melakukan prompt pada CMD sebagai berikut
![Hasil 2](Images/Proses%20CLI.png)
Gambar tersebut memperlihatkan proses penggunaan Git melalui Command Prompt untuk menginisialisasi repository, menambahkan file, melakukan commit, menghubungkan repository lokal dengan GitHub, dan mengunggah project ke repository GitHub.

3. Setelah berhasil, File yang tadi ada di File manager akan masuk ke repositori Github
![Hasil 3](Images/Hasil%20Akhir.png)

