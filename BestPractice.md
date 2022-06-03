## GIT COMMANDS

GIT LOG = Untuk melihat history perubahan (id, message, author, date)
GIT ADD = Untuk menambahkan perubahan ke staging
GIT INIT = Inisialisasi git (.git -> CODEOWNERS, template PR)
GIT PUSH = Push dari lokal ke upstream
GIT COMMIT = Untuk menyimpan perubahan yang akan di push ke branch lokal (git commit --amend -> untuk merubah commit message)
GIT STATUS = Untuk mengecek perubahan yang dilakukan dalam level file changes, mengecek apakah branchnya uptodate
GIT PULL = Untuk mengambil perubahan yang ada di upstream dan menggabungkan dengan branch di lokal
GIT MERGE = Untuk menggabungkan 2 branch yang berbeda
GIT STASH = Untuk menyimpan perubahan sementara ke lokal
GIT FETCH = Untuk mengambil perubahan terbaru dari upstream
GIT REBASE = Untuk menggabungkan perubahan ke lokal dalam satu tree yang sama
GIT REMOTE = Untuk menambahkan, mengubah, menghapus upstream baru
GIT RESTORE = Untuk mengembalikan perubahan ke state awal
GIT RESET = Untuk mengembalikan state ke commit tertentu
GIT CHECKOUT = Untuk berpindah ke branch, commit, atau tag & mengembalikan file state ke awal, Untuk membuat branch baru dan langsung pindah
GIT DIFF = Untuk mengecek perubahan yang dilakukan di level kode
GIT BRANCH = Untuk membuat branch baru, mengubah nama branch, menghapus branch

## BEST PRACTICE

1. Minta akses ke upstream (github, gitlab, azure, bitbucket)
2. Git clone
3. Git checkout -b feature/T123-login
4. Code changes
5. Git status
6. Git diff
6. Git add
7. Git commit -m "Create login feature"
8. Git fetch origin
9. Git rebase origin/master
10. Git push origin feature/T123-login
11. Create Pull request
12. Request review
13. Approved -> Merged
14. Git checkout master
15. Git fetch origin
16. Git rebase origin/master
17. Git checkout -b feature/T124-register