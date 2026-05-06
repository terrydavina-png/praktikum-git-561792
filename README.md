<img width="576" height="274" alt="Screenshot 2026-05-06 051703" src="https://github.com/user-attachments/assets/49083788-dee8-4c28-89be-5d3d0a4bc7c2" />
Gambar diatas adalah output dari log --oneline --graph
<img width="1920" height="1020" alt="Screenshot 2026-05-06 114957" src="https://github.com/user-attachments/assets/3548dc42-bdc3-486e-9b9e-f06c0f7f9230" />
Gambar diatas adalah setting dari branch protection rule

**Website jual bibit tanaman sederhana**
Project ini merupakan website jual bibit yang didesain sederhana sebagai bagian dari praktikum Git dan GitHub.  Website ini berisi desain awal landing page dengan fitur didalamnya terdapat navbar, hero section, card produk, dan footer, serta dibuat agar responsive. Website ini juga dibuat untuk mencoba mengimplementasikan dark mode.

**fitur**
- Navbar navigasi
- Footer dengan informasi kontak
- Tampilan responsive sederhana
- Dark mode styling

**Cara menjalankan**
1. Clone repository ini:
   git clone https://github.com/terrydavina-png/repo.git

2. Masuk ke folder project:
   cd praktikum-git-561792

3. Buka file index.html di browser

**Screenshot Website**
<img width="1920" height="1020" alt="Screenshot 2026-05-06 220912" src="https://github.com/user-attachments/assets/d140912a-158c-4e65-a80c-28f5a52545aa" />


**Dokumentasi Git**
Beberapa perintah Git yang digunakan dalam project ini :
1. git clone
Digunakan untuk menyalin repository dari GitHub ke komputer lokal. Dengan perintah ini, seluruh isi project beserta riwayat commit akan ikut terunduh sehingga kita bisa langsung mulai bekerja secara lokal.

2. git add
Digunakan untuk menambahkan perubahan file ke staging area. Staging area adalah tempat sementara sebelum perubahan benar-benar disimpan menjadi commit.

3. git commit
Digunakan untuk menyimpan perubahan yang sudah ada di staging area ke dalam repository. Setiap commit harus memiliki pesan yang jelas agar riwayat perubahan mudah dipahami.

4. git status
Digunakan untuk melihat kondisi repository saat ini, seperti file yang berubah, file yang sudah di-stage, dan file yang belum dilacak (untracked).

5. git log
Digunakan untuk melihat riwayat commit dalam bentuk ringkas. Opsi --graph membantu memvisualisasikan percabangan (branch) yang terjadi.

6. git branch
Digunakan untuk membuat branch baru. Branch memungkinkan pengembangan fitur dilakukan secara terpisah tanpa mengganggu branch utama (main).

7. git checkout
Digunakan untuk berpindah ke branch tertentu agar kita bisa bekerja di branch tersebut.

8. git checkout -b
git checkout -b feature/footer

Digunakan untuk membuat branch baru sekaligus langsung berpindah ke branch tersebut dalam satu perintah.

9. git push
Digunakan untuk mengirim commit dari lokal ke repository di GitHub. Perintah ini biasanya digunakan setelah selesai melakukan commit.

10. git push --force
Digunakan untuk memaksa update ke repository remote dengan menimpa riwayat commit sebelumnya. Perintah ini digunakan setelah melakukan rebase atau perubahan history, dan harus digunakan dengan hati-hati karena dapat menghapus riwayat commit di remote.

11. git pull
Digunakan untuk mengambil perubahan terbaru dari repository remote dan menggabungkannya ke branch lokal.

12. git merge
Digunakan untuk menggabungkan perubahan dari satu branch ke branch lain. Biasanya digunakan saat menggabungkan fitur ke branch utama.

13. Resolusi Konflik
Saat terjadi konflik, Git akan menandai bagian yang bermasalah seperti berikut:

<<<<<<< HEAD
=======
>>>>>>> branch

Konflik diselesaikan dengan mengedit kode secara manual, lalu menjalankan:
git add .
git commit

14. git rebase
Digunakan untuk memindahkan commit ke atas base branch terbaru. Rebase membantu menjaga riwayat commit tetap rapi dan linear.

15. git rebase -i (interactive rebase)
Digunakan untuk mengedit beberapa commit terakhir, seperti menggabungkan (squash) beberapa commit menjadi satu. Fitur ini sangat berguna untuk merapikan riwayat commit sebelum dipush.

16. git rebase --continue
Digunakan untuk melanjutkan proses rebase setelah konflik berhasil diselesaikan.

17. git rebase --skip
Digunakan untuk melewati commit tertentu yang bermasalah saat proses rebase berlangsung.

 18. git rebase --abort
Digunakan untuk membatalkan proses rebase dan mengembalikan repository ke kondisi sebelum rebase dimulai.

19. git commit --amend
Digunakan untuk mengubah commit terakhir, baik dari segi isi maupun pesan commit.

20. git reset
Digunakan untuk membatalkan commit tanpa menghapus perubahan pada file. Perubahan akan tetap ada di staging area sehingga bisa di-commit ulang.

21. .gitignore
File .gitignore digunakan untuk menentukan file atau folder yang tidak ingin dimasukkan ke dalam repository, seperti:

node_modules/
*.log
.DS_Store


