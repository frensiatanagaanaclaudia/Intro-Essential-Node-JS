1.Mohon jelaskan apa itu Node.js? Apa perbedannya dengan JavaScript?Pengertian dari Node.js adalah runtime untuk menggunakan javascript di sisi server sedangkan Javascript adalah bahasa pemogramannya.

2.Mohon jelaskan arsitektur dari Node.js?
Arsitektur dari Node.js:
    1. Engine V8
Engine V8  milik Google merupakan sebuah compiler JavaScript yang dibuat menggunakan bahasa pemrograman C++. V8 terdiri dari 3 komponen :
Compiler yaitu mengubah JavaScript menjadi bahasa pemrograman lain.
Optimizer yaitu menciptakan sebuah abstract sytax tree yang akan diubah menjadi static single assignment dan dioptimasi
Garbage collector yaitu V8 yang membagi penyimpanan menjadi 2 yaitu penyimpanan baru merupakan tempat menaruh output ari compiler ketia penyimpanan baru sudah penuh garbage collector yang memindahkan objek – objek lama ke penyimpanan lama agar kinerja Node.js
    2. Libuv library
Library C++ mengelola operasi asynchronous I/O (input/output) di Node.js dan main event loop. Didalam terdapat thread pool reserve yang menangani thread setiap operasi I/O
    3. Design Pattern
Terdapat 2 jenis design pattern yang digunakan oleh Node.js yaitu object pool dan façade :

Object pool yaitu design pattern yang berisi kumpulan object yang dapat digunakan task tertentu
Façade yaitu design pattern yang memberikan tampilan antarmuka untuk body kodenya

3.Apa perbedaan antara Built-in Module, External Module, dan Custom Module pada Node.js?
Dari segi pengertian:
-Built-in Module:Satu set modul bawaan yang dapat Anda gunakan tanpa instalasi lebih lanjut.
-External Module:Modul Node pihak ketiga yang dikembangkan oleh pengembang Node yang tersedia melalui ekosistem Node.
-Custom Module:Modul sejenis paket yang berisi fungsi atau metode tertentu untuk digunakan ketika di import.

4.Sebutkan salah satu contoh dari Built-in Module, External Module, dan Custom Module pada Node.js?
-Built in module: timers,punycode,https,https,fs,domain.
-External module : npm nodemon,npm express,npm install.
-Custom module: membuat module lalu melakukan import.
