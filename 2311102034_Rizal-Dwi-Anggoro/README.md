<div align="center">
  <br />
  <h1>LAPORAN PRAKTIKUM <br>APLIKASI BERBASIS PLATFORM</h1>
  <br />
  <h3>MODUL 1 <br> GIT</h3>
  <br />
  <img src="assets/logo_telkom.jpeg" alt="Logo" width="300"> 
  <br />
  <br />
  <br />
  <h3>Disusun Oleh :</h3>
  <p>
    <strong>Rizal Dwi Anggoro</strong><br>
    <strong>2311102034</strong><br>
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

Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang 
diciptakan oleh Linus Torvalds. Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang 
dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS 
terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.  

### UNGUIDED :

**1. Installasi Git**
   
Langkah pertama adalah melakukan instalasi Git pada komputer. Untuk mengecek apakah Git sudah terinstall atau belum, gunakan perintah berikut pada terminal: git --version

![Screenshot Git](assets/1%20cek%20git.png)

**2. Inisialisasi Repository Git**

Setelah Git terinstall, langkah berikutnya adalah melakukan inisialisasi repository Git pada folder project menggunakan perintah: git init

![Screenshot Git](assets/2%20git%20init.png)

**3. Menambahkan File ke Staging Area**
Setelah repository dibuat, langkah selanjutnya adalah menambahkan file ke staging area.
Jika ingin menambahkan semua file yang ada pada folder, gunakan perintah: git add .
Jika hanya ingin menambahkan file tertentu saja, gunakan: git add namafile

![Screenshot Git](assets/3%20tambah%20file.png)

![Screenshot Git](assets/3%201%20git%20add%20txt.png)


**4. Melakukan Commit**

Setelah file berhasil ditambahkan ke staging area, langkah berikutnya adalah melakukan commit untuk menyimpan perubahan pada repository lokal. commandnya : git commit -m "Initial commit"

![Screenshot Git](assets/4%20git%20commit.png)

Commit digunakan untuk mencatat perubahan yang telah dilakukan pada project.

**5. Membuat Repository di GitHub**
Selanjutnya membuat repository baru di GitHub dengan cara:

- Login ke akun GitHub

- Klik New Repository

- Isi nama repository dan deskripsi sesuai kebutuhan

![Screenshot Git](assets/5%20buka%20github%20new%20repo.png)

![Screenshot Git](assets/5%201%20sesuaikan%20repo.png)

**6. Menghubungkan Repository Lokal dengan GitHub**
Setelah repository GitHub dibuat, hubungkan repository lokal dengan repository GitHub menggunakan perintah: git remote add origin https://github.com/usernameanda/namarepo.git

![Screenshot Git](assets/6%20remote%20github.png)

**7. Mengirim File ke GitHub**
Langkah terakhir adalah mengirimkan file dari repository lokal ke repository GitHub menggunakan perintah: git push -u origin master

![Screenshot Git](assets/7%20git%20push.png)

Perintah ini akan mengupload seluruh commit yang ada di repository lokal ke repository GitHub.
