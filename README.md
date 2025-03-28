### Reflection Subscriber-1
1. Mutex hanya dapat mengizinkan satu thread untuk mengakses data. RwLock memungkinkan banyak thread untuk membaca data secara bersamaan. RwLock juga mencegah data race, data bisa dipanggil oleh banyak thread tetapi hanya satu thread yang bisa menulis

2. Dengan lazy_static variabel statik hanya diinisialisasi satu kali saat pertama kali akses bukan saat kompilasi. Selain itu, lazy_static juga memungkinkan penggunaan global sehingga variabel statik yang diinisialisasi bisa diakses dari mana saja di program.