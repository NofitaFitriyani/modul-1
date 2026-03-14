

<div align="center">
  <br />
  <h1>LAPORAN PRAKTIKUM <br>APLIKASI BERBASIS PLATFORM</h1>
  <br />
  <h3>MODUL 1 <br> GIT</h3>
  <br />
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2F1.bp.blogspot.com%2F-vb7jyBjK-sM%2FXXfKp51LrjI%2FAAAAAAAACts%2FEjcXzlgZwSswNWXsBHMyX-6aav1mjA77QCPcBGAYYCw%2Fs1600%2FLogo_Telkom_University_potrait.png&f=1&nofb=1&ipt=9d030d54102ea96369d39fe491220e0536195abc8ee443279c1a420302206400" alt="Logo Telkom" width="300"> 
  <br /><br /><br />
  
  <h3>Disusun Oleh :</h3>
  <p>
    <strong>Didik Setiawan</strong><br>
    <strong>2311102030</strong><br>
    <strong>IF-11-REG-01</strong>
  </p>
  <br />
  
  <h3>Dosen Pengampu :</h3>
  <p><strong>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</strong></p>
  <br />
  
  <h4>Asisten Praktikum :</h4>
  <strong>Apri Pandu Wicaksono</strong> <br>
  <strong>Rangga Pradarrell Fathi</strong>
  <br />
  
  <h3>LABORATORIUM HIGH PERFORMANCE<br>FAKULTAS INFORMATIKA<br>UNIVERSITAS TELKOM PURWOKERTO<br>2026</h3>
</div>

---

## DASAR TEORI

Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds. Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.



## UNGUIDED

### 1. Clone Repository Modul 1

Langkah pertama adalah melakukan clone repository modul 1 dari GitHub ke komputer lokal.

```bash
git clone https://github.com/Aplikasi-Berbasis-Platform-S1IF-11-01/modul-1.git 
```
![Alt 1](https://raw.githubusercontent.com/didiksetia1/asset/refs/heads/main/Screenshot%202026-03-13%20170247.png)


### 2.masuk ke folder repository 

Setelah proses clone selesai, masuk ke folder repository dengan perintah:

```bash
cd modul-1

```
![Alt 2](https://raw.githubusercontent.com/didiksetia1/asset/refs/heads/main/Screenshot%202026-03-13%20170306.png)

### 3. Membuat Folder Sesuai NIM dan Nama dan masuk ke foldernya
Di dalam folder modul-1, buat folder baru dengan format NIM_Nama:
```bash
mkdir 2311102030_Didik-Setiawan
cd 2311102030_Didik-Setiawan


```
![Alt 3](https://raw.githubusercontent.com/didiksetia1/asset/refs/heads/main/Screenshot%202026-03-13%20170321.png)

### 4. Membuat File Teks dan Melakukan Commit

```bash
echo "test" > test.txt
git status
git add test.txt
git commit -m "menambahkan test.txt"



```
![Alt 4](https://raw.githubusercontent.com/didiksetia1/asset/refs/heads/main/Screenshot%202026-03-13%20170405.png)



### 5. Melakukan Push ke Remote Repository
Setelah commit berhasil dibuat, kirim perubahan ke remote repository (branch main) dengan perintah:
![Alt 5](https://raw.githubusercontent.com/didiksetia1/asset/refs/heads/main/Screenshot%202026-03-13%20170416.png)



