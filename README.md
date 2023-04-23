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
Keadaan awal point score sedang berada pada 0.
![start](https://user-images.githubusercontent.com/101118033/233864642-3ed24215-68f9-40ca-ad94-38ef15591999.png)

Point score akan bertambah +1 jika bergerak dengan salah satu arah selama tidak berubah arah.
![1-up](https://user-images.githubusercontent.com/101118033/233864660-eddb3998-5cfc-4824-966f-afed2912e9ff.png)

Jika berubah arah maka point score akan bertambah lagi.
![2-right](https://user-images.githubusercontent.com/101118033/233864664-83f893ee-f0fb-4bfb-91c6-92ab573fcfa6.png)

Selama arah tersebut sama, point score akan terus +0.
![3-left](https://user-images.githubusercontent.com/101118033/233864669-d2274f75-271f-4526-aac5-5bd73933c059.png)

Dan bertambah kembali +1 jika arah benda berubah.
![4-down](https://user-images.githubusercontent.com/101118033/233864675-de66158d-ef14-41c2-a195-b512415c0527.png)

# Demo
https://user-images.githubusercontent.com/101118033/233864725-4eac837b-6528-4c29-8693-b4ce1429debe.mp4
