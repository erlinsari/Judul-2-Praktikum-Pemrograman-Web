Ini adalah proyek website portfolio pribadi yang dibuat untuk memenuhi tugas tugas akhir praktikum pemrograman web 2.

**Cara Pembuatan**

1.  **Inisialisasi Git**
    ```bash
    git init
    ```

2.  **Atur Nama Branch Utama**
    ```bash
    git branch -M main
    ```

3.  **Commit awal(bikin index.html dan style.css)**
    ```bash
    git add .
    git commit -m "Commit pertama kali"
    ```

4.  **Commit Section Navigasi**
    ```bash
    git add .
    git commit -m "add navbar"
    ```

5.  **Commit Home**
    ```bash
    git add .
    git commit -m "nambah add home section"
    ```

6.  **Commit about dan styling base section**
    ```bash
    git add .
    git commit -m "tambah about dan styling base sectiong"
    ```

7.  **Commit skill section**
    ```bash
    git add .
    git commit -m "nambah skill section"
    ```

8.  **Commit project section**
    ```bash
    git add .
    git commit -m "tambah project section"
    ```

9.  **Commit section experience**
    ```bash
    git add .
    git commit -m "tambah section experience"
    ```

10.  **Commit Footer dan kontak**
    ```bash
    git add .
    git commit -m "tambah kontak dan footernya"
    ```

11.  **Buat dan pindah ke branch baru**
    ```bash
    git checkout -b styling-experiment
    ```

12.  **Commit perubahannya**
    ```bash
    git add style.css
    git commit -m "pink ke biru theme"
    ```

13.  **Kembali ke branch awal**
    ```bash
    git checkout main
    ```

14.  **Merge Branch**
    ```bash
    git merge styling-experiment
    ```

15.  **Commit README.md**
    ```bash
    git add README.md
    git commit -m "Dokumen readme"
    ```

16.  **Menghubungkan ke github**
    ```bash
    git remote add origin https://github.com/erlinsari/Judul-2-Praktikum-Pemrograman-Web.git
    ```

17.  **Push github**
    ```bash
    git push -u origin main
    ```

18.  **Push branch**
    ```bash
    git push origin styling-experiment
    ```

**Cara Penggunaan**

1.  **Clone repository ini:**
    ```bash
    git clone [https://github.com/erlinsari/portfolio-website.git](https://github.com/erlinsari/portfolio-website.git)
    ```

2.  **Masuk ke direktori proyek:**
    ```bash
    cd portfolio-website
    ```

3.  **Buka file `index.html`:**
    Klik dua kali file `index.html` di folder untuk membukanya di browser.

**Struktur Commit**
Proses pengembangan website ini dilakukan secara bertahap agar setiap perubahan dapat dilacak dengan jelas melalui commit berikut:

Ini merupakan hasil dari git log --graph --oneline

H:\TEMP\portofolio-erlin>git log --graph --oneline
* 0a85704 (HEAD -> main, origin/main) Dokumen readme
* 5525e40 Dokumen readme
* 753549c (origin/styling-experiment, styling-experiment) tambah kontak dan footernya
* 54604e1 tambah section experience
* 68c4913 tambah project section
* 3184217 tambah skill section
* f5b887b tambah about dan styling base section
* 8903e7a nambah add home section
* a5e9ea3 Commit pertama kali

**Branching dan Merging**
Pengembangan fitur baru dilakukan melalui branch eksperimental agar tidak mengganggu versi utama.
Terdapat dua branch utama dalam proyek ini:

main :Berisi versi stabil dari website.

styling-experiment :Digunakan untuk eksperimen penambahan section kontak dan footer.

Setelah proses pengujian dan revisi selesai, branch styling-experiment di-merge kembali ke branch utama main.
