<div align="center">
  <br />
  <h1>LAPORAN PRAKTIKUM <br>APLIKASI BERBASIS PLATFORM</h1>
  <br />
  <h3>MODUL 1 <br> GIT</h3>
  <br />
  <img src="assets/logo.jpeg" alt="Logo" width="300"> 
  <br />
  <br />
  <br />
  <h3>Disusun Oleh :</h3>
  <p>
    <strong>Muhammad Hamzah Haifan Ma'ruf</strong><br>
    <strong>2311102091</strong><br>
    <strong>S1 IF-11-01</strong>
  </p>
  <br />
  <h3>Dosen Pengampu :</h3>
  <p>
    <strong>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</strong>
  </p>
  <br />
  <br />
    <h4>Asisten Praktikum :</h4>
    <strong> Apri Pandu Wicaksono </strong> <br>
    <strong>Rangga Pradarrell Fathi</strong>
  <br />
  <h3>LABORATORIUM HIGH PERFORMANCE
 <br>FAKULTAS INFORMATIKA <br>UNIVERSITAS TELKOM PURWOKERTO <br>2026</h3>
</div>

---

## 1. Landasan Teori

**Git** merupakan sistem kontrol versi terdistribusi (Distributed Version Control System) yang digunakan oleh pengembang perangkat lunak untuk mencatat serta melacak perubahan pada file proyek. Dengan Git, riwayat perubahan kode dapat dipantau dengan mudah sehingga memudahkan proses kolaborasi antar developer. Sementara itu, **GitHub** adalah layanan berbasis web yang menyediakan hosting untuk repositori Git, sehingga proyek dapat disimpan, dikelola, dan diakses secara online.

**Command Line Interface (CLI)** adalah antarmuka berbasis teks yang memungkinkan pengguna menjalankan berbagai perintah langsung ke sistem komputer. Pada praktikum ini, CLI seperti Command Prompt atau Terminal dimanfaatkan untuk menjalankan perintah Git secara langsung, yang umumnya lebih cepat dan efisien dibandingkan menggunakan antarmuka grafis.

---

## 2. Setup Repository melalui CLI

Berikut merupakan tahapan yang dilakukan untuk melakukan inisialisasi serta menghubungkan repositori lokal dengan repositori di GitHub menggunakan CLI:

### Langkah 1: Membuat Repository Baru di GitHub

![Langkah 1](assets/1.png)

Tahapan pertama adalah membuat repository baru pada GitHub. Repository ini berfungsi sebagai tempat penyimpanan proyek secara online, sehingga seluruh file dan kode yang dibuat dapat tersimpan dengan aman serta dapat diakses melalui internet.

### Langkah 2: Melihat Panduan Perintah Git

![Langkah 2](assets/2.png)

Setelah repository berhasil dibuat, GitHub akan menampilkan beberapa instruksi berupa perintah Git. Perintah-perintah tersebut digunakan untuk menghubungkan proyek yang ada di komputer lokal dengan repository yang sudah dibuat di GitHub.

### Langkah 3: Membuat Folder Proyek dan File

![Langkah 3](assets/3.png)
Pada tahap ini, dibuat sebuah folder proyek pada komputer lokal. Di dalam folder tersebut kemudian ditambahkan file yang nantinya akan diunggah ke repository GitHub.

### Langkah 4: Membuka CMD pada Direktori Proyek

![Langkah 4](assets/4.png)

Selanjutnya, buka Command Prompt (CMD) atau Terminal dan pastikan lokasi direktori aktif berada pada folder proyek yang telah dibuat. Hal ini penting agar perintah Git yang dijalankan diterapkan pada proyek yang benar.

### Langkah 5: Menjalankan Perintah Git di Terminal (Push ke GitHub)

![Langkah 5](assets/5.png)

Pada langkah ini, jalankan perintah Git sesuai dengan panduan yang diberikan oleh GitHub. Proses dimulai dengan menginisialisasi repository lokal menggunakan `git init`, kemudian menambahkan file menggunakan `git add`, membuat commit dengan `git commit`, menghubungkan repository lokal dengan repository GitHub melalui `remote`, dan terakhir mengunggah file menggunakan `git push`.

### Langkah 6: Repository Berhasil Diperbarui

![Langkah 6](assets/6.png)

Terakhir, periksa halaman repository di GitHub untuk memastikan bahwa file yang telah di-*push* dari komputer lokal sudah berhasil muncul di repository.

---

## Referensi

- [Materi Modul 1](https://drive.google.com/file/d/1sAJR4AconN_aZjvLF-GTY0DM-e84pL63/view?usp=sharing)