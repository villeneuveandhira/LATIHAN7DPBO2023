# LATIHAN7DPBO2023
Modifikasi kode yang sudah diberikan, dengan ketentuan sebagai berikut:<br />
- Pemain mengendalikan bola. Setiap kali bola bergerak, skor pemain bertambah +1.
- Skor hanya bertambah jika pemain berbelok, bukan bergerak berurutan. Detail:<br />
    &nbsp; (1). Saat pertama kali membuka program, pemain bergerak ke arah manapun, skor +1.<br />
    &nbsp; (2). Setelah pemain bergerak, dia harus bergerak ke arah lain agar skornya +1. Jika menekan tombol yang sama, skor tetap (+0).<br />
    &nbsp; (3). Contoh, pemain membuka program, lalu bergerak ke kanan dan berhenti, maka skor bertambah +1. Jika pemain bergerak ke arah atas, bawah, atau kiri, maka skor bertambah +1. Namun, jika pemain bergerak ke kanan lagi, maka skor +0.<br />
    &nbsp; (4). Bagaimana jika urutannya, kanan - atas - kiri - kanan? Kanan yang kedua tetap +1, karena pergerakan pemain sebelumnya adalah kiri, sehingga tidak dianggap berurutan.<br />
- [BONUS] Buatlah sistem game yang menambahkan satu kotak atau objek apapun secara acak. Jika pemain menyentuh objek tersebut, skor bertambah +5 atau +10, lalu objek akan berpindah lagi ke posisi lain secara acak.
- Belajar untuk meng-compile secara manual, bukan di-run via IDE. Hal ini bertujuan untuk membantu saat presentasi TMD nanti.
- Deadline: 25 April 2023 (Extended).
- Tidak perlu menggunakan UML selama desain dan penamaan file masih jelas serta mengikuti contoh kode yang diberikan.
- Program dikumpulkan pada repository publik GitHub dengan nama “LP7...DPBO2023”, dengan … diisi kelas (C1/C2).
- Struktur folder:<br />
    &nbsp; -> src<br />
    &nbsp; -> Screenshot / Video<br />
    &nbsp; -> ReadME.md<br />
- File README berisi desain program, penjelasan alur, dan dokumentasi saat program dijalankan (screenshot / record).

# FORMAT Janji
Saya Villeneuve Andhira Suwandhi NIM 2108067 mengerjakan Latihan 7
dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan.
Aamiin.

# Documentation
Keadaan awal point score sedang berada pada 6.
![start](https://user-images.githubusercontent.com/101118033/233863456-6b2aef25-1843-4f4d-ae3e-e983ccaa4e27.png)

Point score akan bertambah +1 jika bergerak dengan salah satu arah selama tidak berubah arah.
![1-up](https://user-images.githubusercontent.com/101118033/233863505-ed7350bd-3ccb-425d-9f66-6447e7a1bbef.png)

Jika berubah arah maka point score akan bertambah lagi.
![2-right](https://user-images.githubusercontent.com/101118033/233863506-08e30225-72e5-440d-8f64-6c8c6efab052.png)

Selama arah tersebut sama, point score akan terus +0.
![3-left](https://user-images.githubusercontent.com/101118033/233863507-51711af0-32b9-4cb8-b056-353f59e4f6cd.png)

Dan bertambah kembali +1 jika arah benda berubah.
![4-down](https://user-images.githubusercontent.com/101118033/233863509-7d633775-eea2-45ef-8d9c-f55f2a72086e.png)
