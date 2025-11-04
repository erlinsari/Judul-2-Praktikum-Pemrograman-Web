Tugas akhir praktikum pemrograman web 2

**Cara Pembuatan**

    ```bash
    #Inisialisasi Git
    git init

    #Atur Nama Branch Utama
    git branch -M main

    #Commit awal(bikin index.html dan style.css)
    git add .
    git commit -m "Commit pertama kali"

    #Commit Section Navigasi
    git add .

    #Commit Home
    git add .
    git commit -m "nambah add home section"
    
    #Commit about dan styling base section
    git add .
    git commit -m "tambah about dan styling base section"

    #Commit skill section
    git add .
    git commit -m "nambah skill section"

    #Commit project section
    git add .
    git commit -m "tambah project section"

    #Commit section experience
    git add .
    git commit -m "tambah section experience"

    #Commit Footer dan kontak
    git add .
    git commit -m "tambah kontak dan footernya"

    #Buat dan pindah ke branch baru
    git checkout -b styling-experiment

    #Commit perubahannya (mengubah warna)
    git add style.css
    git commit -m "pink ke biru theme"

    #Kembali ke branch awal
    git checkout main

    #Merge Branch
    git merge styling-experiment

    #Commit README.md
    git add README.md
    git commit -m "Dokumen readme"

    #Menghubungkan ke github
    git remote add origin [https://github.com/erlinsari/Judul-2-Praktikum-Pemrograman-Web.git](https://github.com/erlinsari/Judul-2-Praktikum-Pemrograman-Web.git)

    #Push github
    git push -u origin main

    #Push branch
    git push origin styling-experiment

    ```

---

**Cara Penggunaan**

1.  **Clone repository ini:**
    ```bash
    git clone [https://github.com/erlinsari/Judul-2-Praktikum-Pemrograman-Web.git](https://github.com/erlinsari/Judul-2-Praktikum-Pemrograman-Web.git)
    ```

2.  **Masuk ke direktori proyek:**
    ```bash
    cd Judul-2-Praktikum-Pemrograman-Web
    ```

3.  **Buka file `index.html`:**
    Klik dua kali file `index.html` di folder untuk membukanya di browser.

---

**Struktur Commit**

Ini merupakan hasil dari `git log --graph --oneline` yang **sebenarnya**, yang menunjukkan semua proses commit, branch, dan merge:

Proses pengembangan website ini dilakukan secara bertahap agar setiap perubahan dapat dilacak dengan jelas melalui commit berikut:

Berikut hasil dari git log --graph --oneline

    ```bash
    H:\TEMP\portofolio-erlin>git log --graph --oneline
    a85704 (HEAD -> main, origin/main) Dokumen readme
    5525e40 Dokumen readme
    753549c (origin/styling-experiment, styling-experiment) tambah kontak dan footernya
    54604e1 tambah section experience
    68c4913 tambah project section
    3184217 tambah skill section
    f5b887b tambah about dan styling base section
     8903e7a nambah add home section
    a5e9ea3 Commit pertama kali
    ```

---

**Branching dan Merging**
Pengembangan fitur baru dilakukan melalui branch eksperimental agar tidak mengganggu versi utama.
Terdapat dua branch utama dalam proyek ini:

main :Berisi versi stabil dari website.

styling-experiment :Digunakan untuk eksperimen penambahan section kontak dan footer.

Setelah proses pengujian dan revisi selesai, branch styling-experiment di-merge kembali ke branch utama main.