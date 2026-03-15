<div align="center">
  <br />
  <h1>LAPORAN PRAKTIKUM <br>APLIKASI BERBASIS PLATFORM</h1>
  <br />
  <h3>MODUL 1 <br> GIT</h3>
  <br />
  <img src="assets/Logo_Telkom_University_potrait.png" alt="Logo" width="300"> 
  <br />
  <br />
  <br />
  <h3>Disusun Oleh :</h3>
  <p>
    <strong>Arjun Werdho Kumoro</strong><br>
    <strong>2311102009</strong><br>
    <strong>IF-11-REG01</strong>
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


### DASAR TEORI :

Git merupakan salah satu sistem pengendali versi (Version Control System / VCS) yang digunakan dalam pengembangan perangkat lunak dan dibuat oleh Linus Torvalds. Sistem ini berfungsi untuk merekam serta melacak setiap perubahan yang terjadi pada file atau kode dalam suatu proyek, baik yang dikerjakan secara individu maupun oleh tim.

Selain itu, Git termasuk jenis distributed version control system, yang berarti seluruh riwayat dan database proyek tidak hanya tersimpan pada satu server pusat, tetapi juga tersalin pada setiap komputer pengembang yang menggunakan repositori tersebut. Dengan sistem ini, kolaborasi menjadi lebih mudah dan risiko kehilangan data dapat diminimalkan.

### UNGUIDED :

**1. Installasi Git**
   
Cek apakah Git sudah terinstall atau belum, gunakan perintah berikut pada terminal: git --version

![foto](assets/2.png)

**2. Inisialisasi Repository Git**

Selanjutnya adalah melakukan inisialisasi repository Git pada folder project menggunakan perintah: git init

![foto](assets/3.png)

**3. Menambahkan File ke Staging Area**
Setelah repository dibuat, langkah selanjutnya adalah menambahkan file ke staging area.
Jika ingin menambahkan semua file yang ada pada folder, gunakan perintah: git add .
Jika hanya ingin menambahkan file tertentu saja, gunakan: git add namafile

![foto](assets/4.png)

masukan email dan username pada github fungsinya untuk menyambungkan antara cmd dengan github

![foto](assets/5.png)


**4. Melakukan Commit**

Setelah file berhasil ditambahkan ke staging area, langkah berikutnya adalah melakukan commit untuk menyimpan perubahan pada repository lokal. commandnya : git commit -m "Initial commit"

![foto](assets/6.png)

Commit digunakan untuk mencatat perubahan yang telah dilakukan pada project.

**5. Membuat Repository di GitHub**
Selanjutnya membuat repository baru di GitHub dengan cara:

- Login ke akun GitHub

- Klik New Repository

- Isi nama repository dan deskripsi sesuai kebutuhan

![foto](assets/7.png)

**6. Menghubungkan Repository Lokal dengan GitHub**
Setelah repository GitHub dibuat, hubungkan repository lokal dengan repository GitHub menggunakan perintah: git remote add origin https://github.com/Arjunwk/Tugas-Praktikum-ABP

**7. Mengirim File ke GitHub**
Langkah terakhir adalah mengirimkan file dari repository lokal ke repository GitHub menggunakan perintah: git push -u origin master

![foto](assets/8.png)

Perintah ini akan mengupload seluruh commit yang ada di repository lokal ke repository GitHub.

