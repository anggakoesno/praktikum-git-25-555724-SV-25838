# Praktikum Git
### A. Deskripsi Proyek
Landing page dari sebuah website manajemen pesanan warung makan yang bernama “Warung Nusantara”. 

### B. Cara Menjalankan
1. Jalankan perintah: git clone https://github.com/anggakoesno/praktikum-git-25-555724-SV-25838.git
2. Buka folder proyek
3. Buka file landingpage.html di browser

### C. Tampilan Halaman
![image alt](img/gambar-landing-page.png)

### D. Dokumentasi Perintah Git
| Perintah | Contoh | Fungsi |
| -------- | ------ | ------ |
| git init | ![image alt](img/git_init.png) | Inisialisasi repository lokal |
| git remote add origin [url_repositori] | ![image alt](img/git_remote.png) | Menghubungkan repositori Git lokal ke repositori jarak jauh (contohnya GitHub) |
| git add | ![image alt](img/git_add.png) | Menambahkan ("." -> semua) file ke area staging |
| git commit | ![image alt](img/git_commit.png) | Menyimpan perubahan (dari file yang berada di staging) dengan pesan konvensional |
| git branch -M [nama_branch] | ![image alt](img/git_branch_-M.png) | Mengubah (-M) nama branch utama (dari default master) menjadi main |  
| git push (-u) origin [nama_branch] | ![image alt](img/git_push.png) | Mengunggah hasil commit dari lokal ke repository jarah jauh (contohnya GitHub). Gunakan "-u" saat push pertama kali untuk menghubungkan branch lokal ke remote|
| git branch [nama_branch] | ![image alt](img/git_branch_nama-branch.png) | Membuat branch baru yang bernama "[nama_branch]" |
| git checkout [nama_branch] | ![image alt](img/git_checkout.png) | Pindah ke branch yang bernama "[nama_branch]" |
| git merge [nama_branch] | ![image alt](img/git_merge.png) | Menyatukan perubahan dari branch saat ini ke branch yang bernama "[nama_branch]" (biasanya )
| git rebase | ![image alt](img/git_rebase.png) | Merapikan atau menggabungkan rangkaian komit ke atas komit dasar yang baru |

### E. Dokumentasi Lainnya
#### 1. Hasil git log --oneline --graph
##### a. Rangkaian commit pertama
![image alt](img/git_log_oneline_graph_1.png)

##### b. Rebase interaktif
![image alt](img/git_log_oneline_graph_2.png)

#### 2. Branch protection rule
![image alt](img/branch_protection_rule.png)