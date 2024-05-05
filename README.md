# Reflection

![1.2](images/1.2.png)

* Fungsi `spawner.spawn(...);` menambahkan tugas *asynchronous* ke *executor*. "hey hey!!!" berada di luar fungsi jadi akan dieksekusi segera setelah tugas *asynchronous* dihasilkan, tetapi sebelum menunggu timer untuk selesai. Karena tugas *asynchronous* membutuhkan waktu untuk menyelesaikan, pesan "hey hey!!!" akan dicetak terlebih dahulu.