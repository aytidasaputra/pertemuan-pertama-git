# GIT

- tool yang sering digunakan dalam pengembangan perangkat lunak
- Wajib dikuasai oleh programmer zaman kekinian
- Tapi... ini apaan sih?

## GIT 
- Sistem pengontrol versi (Version Control System)
- Diciptakan oleh Linus Torvald (Pembuat OS Linux)
- Mencatat setiap perubahan file pada proyek yang dikerjakan (baik sendiri maupun ramai-ramai)
- Dikenal dengan distributed revision control

## MANFAAT GIT
- Mesin waktu dari kode yang dituliskan di dalam folder (repository)
- Menyimpan riwayat perubahan file dalam bentuk sejumlah commit, bahkan bisa melihat dilakukan oleh siapa dan kapan
- Bisa membuat cabang dari fitur kode yang akan dibuat, tanpa perlu dilakukan di tempat utama yang kita miliki, disebut dengan istilah branch
- Setelah cabang dirasa ingin diimplementasikan ke kode utama, bisa melakuan penggabungan atas kode yang sudah dibuat, disebut dengan merge

## Github

- Sebuah layanan komputasi awan untuk menyimpan & mengelola repositori git
- Diakuisisi oleh Microsoft pada tahun 2018
- Bisa menaruh unlimited proyek yang bersifat publik maupun privat

## gh
- Sebuah tool command-line yang dibuat oleh github
- Digunakan untuk mempermudah hidup apabila menggunakan platform github

## Istilah dalam Git

- **repo(sitory)**	Folder project kita berada
- **remote**	sumber lain yang memiliki repo, di luar komputer kita
- **clone**	mengambil repo dari sumber remote
- **commit**	menyimpan / merekam (snapshot) kode dari repo
- **branch**	cabang dari sebuah commit
- **checkout**	proses untuk berpindah dari satu commit / satu cabang ke commit / cabang lainnya
- **merge**	proses untuk menggabungkan branch
- **push**	mengirimkan commit ke repo (biasanya remote repo)
- **pull**	mengambil commit dari repo (biasanya remote repo)
- **fork(ing)**	membuat kopi / duplikat dari repo publik orang lain (beserta rekam jejaknya)
(sebagai jembatan antara repo original dengan repo yang diduplikat)
**pull request**	permintaan untuk menggabungkan (merge) kode
(umumnya digunakan ketika ingin menggabungkan kode repo kita ke repo sumber fork)