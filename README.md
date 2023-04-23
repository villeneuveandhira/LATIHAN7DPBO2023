# LATIHAN7DPBO2023
Modifikasi kode yang sudah diberikan, dengan ketentuan sebagai berikut:<br />
- Pemain mengendalikan bola. Setiap kali bola bergerak, skor pemain bertambah +1.
- Skor hanya bertambah jika pemain berbelok, bukan bergerak berurutan. Detail:
    &nbsp; Saat pertama kali membuka program, pemain bergerak ke arah manapun, skor +1.
Setelah pemain bergerak, dia harus bergerak ke arah lain agar skornya +1. Jika menekan tombol yang sama, skor tetap (+0).
Contoh, pemain membuka program, lalu bergerak ke kanan dan berhenti, maka skor bertambah +1. Jika pemain bergerak ke arah atas, bawah, atau kiri, maka skor bertambah +1. Namun, jika pemain bergerak ke kanan lagi, maka skor +0.
Bagaimana jika urutannya, kanan - atas - kiri - kanan? Kanan yang kedua tetap +1, karena pergerakan pemain sebelumnya adalah kiri, sehingga tidak dianggap berurutan.
- [BONUS] Buatlah sistem game yang menambahkan satu kotak atau objek apapun secara acak. Jika pemain menyentuh objek tersebut, skor bertambah +5 atau +10, lalu objek akan berpindah lagi ke posisi lain secara acak.
- Belajar untuk meng-compile secara manual, bukan di-run via IDE. Hal ini bertujuan untuk membantu saat presentasi TMD nanti.
- Deadline: 25 April 2023 (Extended).
- Tidak perlu menggunakan UML selama desain dan penamaan file masih jelas serta mengikuti contoh kode yang diberikan.
- Program dikumpulkan pada repository publik GitHub dengan nama “LP7...DPBO2023”, dengan … diisi kelas (C1/C2).
- Struktur folder:
src
Screenshot / Video
ReadME.md
- File README berisi desain program, penjelasan alur, dan dokumentasi saat program dijalankan (screenshot / record).

# FORMAT Janji
Saya Villeneuve Andhira Suwandhi NIM 2108067 mengerjakan Latihan 7
dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan.
Aamiin.

Keseluruhan kode tetap sama hanya saja ada perubahan pada controller.java dimana menandai tombol yang di tekan
dengan angka yang nantinya akan menentukan player berubat atau tidak.
bila angka nya tetap sama maka player tidak berbelok dan bila berubah maka player berbelok dan menambah point
