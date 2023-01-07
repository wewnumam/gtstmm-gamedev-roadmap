# Game Programmer Roadmap

<table>
  <tr>
    <th>Roadmap</th>
    <th>Table of contents</th>
  </tr>
  <tr>
    <td>
      <img src="https://i.imgur.com/3WvcOw0.jpg" alt="game-programming-map"/>
    </td>
    <td>

Table of contents
- [Game Programmer Roadmap](#game-programmer-roadmap)
- [Mathematics](#mathematics)
    - [Matrices](#matrices)
    - [Delta Time](#delta-time)
    - [Unit and Scaling Vectors](#unit-and-scaling-vectors)
    - [Dot and Cross Products](#dot-and-cross-products)
    - [Scalar Manipulation](#scalar-manipulation)
- [Physics](#physics)
    - [Kinematics](#kinematics)
    - [Kinetics](#kinetics)
    - [Force](#force)
    - [Collision](#collision)
    - [Projectiles](#projectiles)
    - [Flowchart](#flowchart)
    - [Git and Github](#git-and-github)
- [Programming](#programming)
  - [Algorithm and Data Structure](#algorithm-and-data-structure)
    - [Algorithm](#algorithm)
    - [Data Structure](#data-structure)
  - [Programming Language](#programming-language)
    - [C#](#c)
    - [Javascript](#javascript)
    - [C++](#c-1)
    - [Lua](#lua)
  - [Design Patterns](#design-patterns)
    - [Creational](#creational)
    - [Structural](#structural)
    - [Behavioral](#behavioral)
  - [Game Patterns](#game-patterns)
    - [Sequence](#sequence)
  - [Clean Code](#clean-code)
    - [Meaningful Names](#meaningful-names)
    - [Functions](#functions)
    - [Objects](#objects)
    - [Read Documentation](#read-documentation)
- [Game Engine](#game-engine)
    - [GDevelop](#gdevelop)
    - [LÖVE 2D](#löve-2d)
    - [Godot](#godot)
    - [Unreal Engine](#unreal-engine)
    - [CryEngine](#cryengine)
  - [Unity](#unity)
    - [Scripting](#scripting)
    - [Input](#input)
    - [Animation and Movement](#animation-and-movement)
    - [Graphics](#graphics)
    - [UI](#ui)
    - [Sound and Music](#sound-and-music)
    - [Behavior and AI](#behavior-and-ai)
    - [Monetization](#monetization)
- [Game Physics](#game-physics)
  - [Rigid-Body Dynamics](#rigid-body-dynamics)
    - [Realtime Simulation](#realtime-simulation)
    - [Particles](#particles)
    - [2D Rigid-Body](#2d-rigid-body)
    - [3D Rigid-Body](#3d-rigid-body)
    - [Connection Objects](#connection-objects)
    - [Physics Engine](#physics-engine)
  - [Physical Modeling](#physical-modeling)
    - [Aircraft](#aircraft)
    - [Ships and Boats](#ships-and-boats)
    - [Cars and Hovercraft](#cars-and-hovercraft)
    - [Guns and Explosion](#guns-and-explosion)
    - [Sports](#sports)
  - [Digital Physics](#digital-physics)
    - [Touch Screen](#touch-screen)
    - [GPS](#gps)
    - [3D Display](#3d-display)
    - [Optical Tracking](#optical-tracking)
    - [Sound](#sound)
- [Computer Graphics](#computer-graphics)
  - [Light and Shadow](#light-and-shadow)
    - [Shadow Map](#shadow-map)
    - [Light Source](#light-source)
  - [Shader](#shader)
    - [Rendering Equation](#rendering-equation)
    - [Reflection](#reflection)
    - [Mapping](#mapping)
- [Advance Topics](#advance-topics)
  - [Artificial Intelligence](#artificial-intelligence)
    - [Machine Learning](#machine-learning)
  - [Online Multiplayer](#online-multiplayer)
    - [Server](#server)
    - [Networking](#networking)
</table>

# Mathematics

Pelajari lebih lanjut:
- [Math for Game Developer by Jorge Rodriguez](https://youtube.com/playlist?list=PLW3Zl3wyJwWOpdhYedlD-yCB7WQoHf-My)
- [Essential Mathematics For Aspiring Game Developers](https://www.youtube.com/watch?v=DPfxjQ6sqrc)
- ...

### Matrices

Matriks adalah struktur matematika yang terdiri dari baris dan kolom yang terorganisir dengan cara tertentu. Matriks biasa digunakan dalam pemrograman game untuk menyimpan dan mengubah data koordinat, transformasi, dan rotasi.

### Delta Time

 Delta waktu adalah perbedaan waktu antara frame saat ini dan frame sebelumnya dalam game. Delta waktu digunakan untuk mengontrol kecepatan objek dan animasi dalam game, terutama saat game dijalankan di komputer yang memiliki performa yang berbeda.

### Unit and Scaling Vectors

Unit adalah satuan standar yang digunakan dalam game untuk menyimpan dan mengolah data. Vektor penskalaan adalah vektor yang menggambarkan skala objek dalam game. Vektor penskalaan biasa digunakan untuk mengubah ukuran objek dalam game.

### Dot and Cross Products

Produk titik adalah hasil perkalian dari dua vektor yang memiliki arah yang sama. Produk silang adalah hasil perkalian dari dua vektor yang memiliki arah yang berlawanan. Kedua jenis produk ini biasa digunakan dalam pemrograman game untuk menentukan arah dan orientasi objek dalam game.

### Scalar Manipulation

Manipulasi skalar adalah proses mengubah nilai skalar (misalnya, ukuran, kecepatan, atau intensitas) dari objek dalam game. Manipulasi skalar biasa digunakan untuk mengontrol aspek-aspek tertentu dari objek dalam game, seperti ukuran, kecepatan, atau intensitas.


# Physics

Pelajari lebih lanjut:
- [Physics by CrashCourse](https://www.youtube.com/playlist?list=PL58rKAc12lkJZ_AEYekzyKqFtiFXPD2g8)
- ...

### Kinematics

Kinematika adalah cabang fisika yang mempelajari gerak tanpa memperhatikan penyebab gerak tersebut. Kinematika biasa digunakan dalam pemrograman game untuk menghitung dan mengontrol gerakan objek dalam game.

### Kinetics

Kinetika adalah cabang fisika yang mempelajari gerak serta penyebab gerak tersebut, seperti gaya yang bekerja pada objek. Kinetika biasa digunakan dalam pemrograman game untuk menghitung dan mengontrol gerakan objek yang dipengaruhi oleh gaya.

### Force

Gaya adalah interaksi fisik antara dua atau lebih objek yang dapat menyebabkan perubahan gerak pada objek tersebut. Gaya biasa digunakan dalam pemrograman game untuk mengontrol dan menghitung perubahan gerak objek yang terpengaruh oleh gaya.

### Collision

Tumbukan adalah interaksi fisik antara dua objek yang menyebabkan perubahan kecepatan, arah, dan bentuk objek tersebut. Tumbukan biasa digunakan dalam pemrograman game untuk mengontrol dan menghitung perubahan gerak objek yang terpengaruh oleh tumbukan.

### Projectiles

Proyektil adalah objek yang terkena pengaruh gravitasi saat terbang di udara. Proyektil biasa digunakan dalam pemrograman game untuk menghitung dan mengontrol gerakan objek seperti peluru atau roket.


### Flowchart

Flowchart adalah diagram yang menggambarkan alur kerja dari sebuah proses atau sistem secara sederhana. Sebagai game programmer, Anda perlu memahami flowchart untuk membantu Anda mengorganisir dan memvisualisasikan alur kerja pengembangan game.

Berikut ini adalah komponen-komponen penting dalam flowchart:

- Start/End: Merupakan simbol yang menandakan awal dan akhir dari sebuah proses.

- Input/Output: Merupakan simbol yang menandakan proses input atau output data.

- Decision: Merupakan simbol yang menandakan adanya pilihan atau keputusan yang harus diambil dalam proses.

- Process: Merupakan simbol yang menandakan adanya tindakan atau proses yang dilakukan dalam alur kerja.

- Connector: Merupakan simbol yang menghubungkan satu elemen flowchart dengan elemen lainnya.

- Document: Merupakan simbol yang menandakan adanya dokumen atau informasi yang diperlukan dalam proses.

- Data: Merupakan simbol yang menandakan adanya data yang diolah dalam proses.

- Subprocess: Merupakan simbol yang menandakan adanya proses yang lebih detil dalam alur kerja.

Dengan memahami komponen-komponen flowchart ini, Anda akan dapat membuat flowchart yang efektif untuk membantu Anda mengorganisir dan memvisualisasikan alur kerja pengembangan game.

### Git and Github

Git adalah sistem kontrol versi yang digunakan untuk mengelola perubahan pada file-file yang terkait dengan sebuah proyek. Github adalah platform hosting yang menyediakan layanan Git secara online, sehingga Anda dapat menyimpan dan mengelola proyek Anda secara terpusat di internet.

Sebagai game programmer, Anda perlu memahami Git dan Github untuk membantu Anda mengelola dan mengontrol perubahan pada kode sumber game Anda. Berikut ini adalah beberapa hal yang perlu Anda ketahui tentang Git dan Github:

- Repositori: Repositori adalah tempat penyimpanan proyek yang menggunakan Git. Setiap perubahan pada proyek tersebut akan dicatat oleh Git, sehingga Anda dapat melihat perubahan tersebut dan mengembalikannya jika diperlukan.

- Branch: Branch adalah versi terpisah dari sebuah proyek yang dapat diubah-ubah secara independen dari versi utama proyek. Branch biasanya digunakan untuk mengembangkan fitur baru atau memperbaiki bug tanpa mengganggu versi utama proyek.

- Commit: Commit adalah tindakan menyimpan perubahan pada proyek ke dalam repositori Git. Setiap commit akan menyimpan perubahan yang terjadi pada proyek, sehingga Anda dapat melihat perubahan tersebut dan mengembalikannya jika diperlukan.

- Push: Push adalah tindakan mengirim perubahan pada repositori Git ke server hosting seperti Github. Dengan push, Anda dapat menyimpan perubahan pada proyek di server hosting sehingga dapat diakses oleh anggota tim lain.

- Pull request: Pull request adalah permintaan untuk menggabungkan perubahan pada branch ke dalam branch utama proyek. Pull request biasanya digunakan untuk meminta persetujuan dari anggota tim lain sebelum perubahan tersebut diintegrasikan ke dalam branch utama proyek.

Dengan memahami Git dan Github, Anda akan dapat mengelola dan mengontrol perubahan pada kode sumber game Anda dengan lebih efektif, serta memudahkan kerja tim dalam pengembangan game.

Pelajari lebih lanjut:
- [Git & Github	oleh Web Programming UNPAS](https://www.youtube.com/playlist?list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf)
- ...

# Programming

## Algorithm and Data Structure

Algoritma adalah serangkaian langkah yang diikuti untuk menyelesaikan suatu masalah. Struktur data adalah cara penyimpanan dan pengelolaan data yang efisien. Sebagai game programmer, Anda perlu memahami algoritma dan struktur data untuk membantu Anda menyelesaikan masalah yang muncul dalam pengembangan game.

Berikut ini adalah beberapa hal yang perlu Anda ketahui tentang algoritma dan struktur data:

- Pencarian dan sortir: Pencarian adalah proses menemukan data yang dicari dalam sekumpulan data yang lebih besar. Sortir adalah proses mengurutkan data dari yang terkecil hingga yang terbesar atau sebaliknya. Pencarian dan sortir biasa digunakan dalam pemrograman game untuk mencari dan mengurutkan data yang diperlukan.

- Stack dan queue: Stack adalah struktur data yang menyimpan data dengan prinsip "last in, first out" (LIFO). Queue adalah struktur data yang menyimpan data dengan prinsip "first in, first out" (FIFO). Stack dan queue biasa digunakan dalam pemrograman game untuk mengelola data yang harus diproses secara berurutan.

- Linked list dan array: Linked list adalah struktur data yang terdiri dari elemen-elemen yang saling terhubung. Array adalah struktur data yang terdiri dari elemen-elemen yang disimpan dalam blok memori yang terpisah. Linked list dan array biasa digunakan dalam pemrograman game untuk menyimpan dan mengelola data.

- Tree dan graph: Tree adalah struktur data yang terdiri dari node-node yang terhubung dengan pola hierarkis. Graph adalah struktur data yang terdiri dari node-node yang terhubung dengan pola tidak teratur. Tree dan graph biasa digunakan dalam pemrograman game untuk menyimpan dan mengelola data yang memiliki hubungan antar elemen.

Dengan memahami algoritma dan struktur data, Anda akan dapat menyelesaikan masalah yang muncul dalam pengembangan game dengan lebih efektif, serta membuat program yang lebih cepat dan efisien.

Pelajari lebih lanjut:
- [Data Structures and Algorithms Full Course](https://www.youtube.com/watch?v=CBYHwZcbD-s)
- [Learn DS & Algorithms by Programiz](https://www.programiz.com/dsa)
- ...

### Algorithm

Algoritma adalah serangkaian langkah yang diikuti untuk menyelesaikan suatu masalah. Algoritma dapat dibuat dengan menggunakan bahasa pemrograman atau pseudocode, yang merupakan representasi sederhana dari kode program yang dapat dipahami oleh manusia. Algoritma biasanya dibuat dengan memperhatikan keefektifan dan keefisienan dalam menyelesaikan masalah.

Berikut ini adalah beberapa jenis algoritma yang sering digunakan:

- Algoritma bruteforce: Algoritma bruteforce adalah algoritma yang mencoba semua kemungkinan solusi satu per satu hingga menemukan solusi yang tepat. Algoritma bruteforce biasanya memiliki waktu eksekusi yang lama, tetapi mudah dipahami dan diterapkan.

- Algoritma divide and conquer: Algoritma divide and conquer adalah algoritma yang memecah masalah menjadi submasalah yang lebih kecil, kemudian menyelesaikan submasalah tersebut secara terpisah dan menggabungkannya menjadi solusi akhir. Algoritma divide and conquer biasanya memiliki waktu eksekusi yang lebih cepat daripada algoritma bruteforce, tetapi lebih sulit dipahami dan diterapkan.

- Algoritma greedy: Algoritma greedy adalah algoritma yang selalu memilih pilihan terbaik saat ini tanpa memperhatikan dampaknya pada masa depan. Algoritma greedy biasanya digunakan untuk mencari solusi masalah yang memiliki banyak pilihan dengan cara mengambil pilihan yang terbaik pada setiap langkah.

- Algoritma dynamic programming: Algoritma dynamic programming adalah algoritma yang menyimpan hasil perhitungan submasalah untuk digunakan kembali dalam menyelesaikan masalah utama. Algoritma dynamic programming biasanya memiliki waktu eksekusi yang lebih cepat daripada algoritma divide and conquer, tetapi lebih sulit dipahami dan diterapkan.

- Algoritma backtracking: Algoritma backtracking adalah algoritma yang mencoba semua kemungkinan solusi satu per satu dengan memutar kembali ke solusi sebelumnya jika solusi tersebut tidak memenuhi syarat. Algoritma backtracking biasanya digunakan untuk mencari solusi masalah yang memiliki banyak pilihan atau kondisi.

- Algoritma heuristik: Algoritma heuristik adalah algoritma yang menggunakan perkiraan atau asumsi untuk menyelesaikan masalah dengan lebih cepat. Algoritma heuristik biasanya memiliki waktu eksekusi yang lebih cepat daripada algoritma bruteforce, tetapi tidak selalu menghasilkan solusi yang optimal.

- Algoritma genetika: Algoritma genetika adalah algoritma yang menggunakan prinsip evolusi untuk mencari solusi masalah dengan cara menggabungkan dan memutarbalikkan solusi yang ada. Algoritma genetika biasanya digunakan untuk mencari solusi masalah yang tidak memiliki solusi pasti atau memiliki banyak pilihan.

Dengan memahami jenis-jenis algoritma ini, Anda akan dapat memilih algoritma yang tepat untuk menyelesaikan masalah yang muncul dalam pengembangan game.

### Data Structure

Struktur data adalah cara penyimpanan dan pengelolaan data yang efisien. Struktur data dapat berupa linear atau tidak linear, tergantung pada bagaimana data tersebut disimpan dan diakses.

Berikut ini adalah beberapa jenis struktur data yang sering digunakan:

- Array: Array adalah struktur data yang terdiri dari elemen-elemen yang disimpan dalam blok memori yang terpisah. Array biasanya digunakan untuk menyimpan data yang memiliki indeks yang terurut secara kontinu.

- Linked list: Linked list adalah struktur data yang terdiri dari elemen-elemen yang saling terhubung. Linked list biasanya digunakan untuk menyimpan data yang memiliki jumlah elemen yang tidak terbatas atau data yang sering mengalami perubahan.

- Stack: Stack adalah struktur data yang menyimpan data dengan prinsip "last in, first out" (LIFO). Stack biasanya digunakan untuk mengelola data yang harus diproses secara berurutan.

- Queue: Queue adalah struktur data yang menyimpan data dengan prinsip "first in, first out" (FIFO). Queue biasanya digunakan untuk mengelola data yang harus diproses secara berurutan.

- Tree: Tree adalah struktur data yang terdiri dari node-node yang terhubung dengan pola hierarkis. Tree biasanya digunakan untuk menyimpan dan mengelola data yang memiliki hubungan antar elemen.

- Graph: Graph adalah struktur data yang terdiri dari node-node yang terhubung dengan pola tidak teratur.

- Hash table: Hash table adalah struktur data yang menggunakan fungsi hash untuk menyimpan dan mengakses data dengan lebih cepat. Hash table biasanya digunakan untuk menyimpan dan mencari data yang memiliki banyak elemen dengan cepat.

- Heap: Heap adalah struktur data yang terdiri dari node-node yang terhubung dengan pola hierarkis dengan aturan tertentu. Heap biasanya digunakan untuk mengelola data yang memiliki prioritas tertentu, seperti data yang harus diproses lebih dahulu.

Dengan memahami jenis-jenis struktur data ini, Anda akan dapat memilih struktur data yang tepat untuk menyimpan dan mengelola data yang diperlukan dalam pengembangan game.

## Programming Language

### C#

C# (C Sharp) adalah bahasa pemrograman yang dikembangkan oleh Microsoft. C# biasanya digunakan untuk membuat aplikasi desktop dan game untuk platform Windows, serta aplikasi mobile dan game dengan menggunakan framework seperti Unity. C# memiliki sintaks yang mirip dengan bahasa pemrograman C++, tetapi lebih mudah dipahami dan lebih aman untuk digunakan.

### Javascript

JavaScript adalah bahasa pemrograman yang digunakan untuk membuat aplikasi web dan game HTML5. JavaScript biasanya digunakan untuk membuat game sederhana yang dapat dimainkan di browser web, serta game yang dapat diunduh dan dimainkan di platform seluler.

### C++

C++ adalah bahasa pemrograman yang dikembangkan dari bahasa C. C++ biasanya digunakan untuk membuat game yang membutuhkan kecepatan eksekusi yang tinggi, seperti game konsol atau game PC yang memiliki grafik yang rumit. C++ juga sering digunakan untuk membuat game dengan menggunakan framework seperti Unreal Engine.

### Lua

Lua sering digunakan sebagai bahasa skrip dalam game. Lua adalah bahasa pemrograman yang ringan dan mudah dipelajari. Lua biasanya digunakan untuk membuat game yang membutuhkan skrip yang mudah diubah-ubah, seperti game RPG atau game strategi. 

## Design Patterns

Design pattern adalah pola atau cara umum yang sering digunakan untuk menyelesaikan masalah yang sama dalam pengembangan perangkat lunak. Design pattern membantu programmer menyelesaikan masalah dengan cara yang sudah teruji dan terbukti efektif, sehingga mempermudah proses pengembangan dan meningkatkan kualitas perangkat lunak.

Design pattern dapat dikelompokkan menjadi tiga jenis, yaitu Creational, Structural, dan Behavioral. 

Pelajari lebih lanjut:
- [Design Patterns by Refactoring Guru](https://refactoring.guru/design-patterns)
- ...

### Creational

Creational design pattern adalah design pattern yang membantu programmer dalam mengelola proses pembuatan objek. Creational design pattern berguna untuk mengatur proses pembuatan objek yang rumit, sehingga memudahkan programmer dalam membuat objek sesuai kebutuhan.

### Structural

Structural design pattern adalah design pattern yang membantu programmer dalam mengelola struktur objek atau kelas. Structural design pattern berguna untuk mengatur struktur objek atau kelas yang rumit, sehingga memudahkan programmer dalam mengelola objek atau kelas sesuai kebutuhan.

### Behavioral

Behavioral design pattern adalah design pattern yang membantu programmer dalam mengelola interaksi dan respons objek. Behavioral design pattern berguna untuk mengatur interaksi dan respons objek yang rumit, sehingga memudahkan programmer dalam mengelola objek sesuai kebutuhan.

## Game Patterns

Pelajari lebih lanjut:
- [Game Programming Patterns by Bob Nystrom](https://gameprogrammingpatterns.com/contents.html)
- ...

### Sequence

Game patterns sequence adalah pola atau cara umum yang sering digunakan dalam pengembangan game untuk mengelola kejadian atau tindakan yang terjadi dalam game. Game patterns sequence biasanya digunakan untuk mengelola kejadian atau tindakan yang terjadi secara berurutan, seperti kejadian yang terjadi ketika pemain memainkan game.

Contoh game patterns sequence adalah pola "main menu - level select - gameplay - game over" yang sering digunakan dalam game. Pola ini menggambarkan kejadian yang terjadi ketika pemain memulai game, memilih level, bermain game, dan game over.

Game patterns sequence berguna untuk membantu programmer mengelola kejadian atau tindakan yang terjadi dalam game dengan lebih efisien, sehingga memudahkan proses pengembangan game dan meningkatkan kualitas game.

## Clean Code

Clean code adalah kode yang mudah dipahami, mudah dibaca, dan mudah diubah. Clean code membantu programmer dalam mengelola proyek perangkat lunak dengan lebih efektif, sehingga mempermudah proses pengembangan dan meningkatkan kualitas perangkat lunak.

Pelajari lebih lanjut:
- [Clean Code	by Robert C. Martin](https://www.oreilly.com/library/view/clean-code-a/9780136083238/)
- [Code Complete by Steve McCinnell](https://www.oreilly.com/library/view/code-complete-2nd/0735619670/)

### Meaningful Names

Meaningful names adalah penamaan yang sesuai dengan fungsi atau tujuan dari kode tersebut. Meaningful names membantu programmer dalam memahami kode dengan lebih mudah, sehingga mempermudah proses debugging dan maintenance.

### Functions

Functions adalah bagian kode yang dapat dipanggil untuk menjalankan tugas tertentu. Functions membantu programmer dalam memisahkan kode yang terkait dengan tugas yang berbeda, sehingga memudahkan proses debugging dan maintenance.

- Functions harus memiliki nama yang menggambarkan tugas yang dilakukan. Contohnya: "calculateTotalScore" untuk menghitung total skor, atau "displayWelcomeMessage" untuk menampilkan pesan selamat datang.

- Functions harus memiliki ukuran yang sesuai, yaitu tidak terlalu panjang namun tidak terlalu pendek. Idealnya, sebuah function hanya melakukan satu tugas yang spesifik dan tidak terlalu rumit.

- Functions harus menggunakan parameter yang sesuai, yaitu tidak terlalu banyak namun tidak terlalu sedikit. Parameter harus memberikan informasi yang cukup untuk menjalankan tugas yang diminta function tersebut.

### Objects

Objects adalah entitas yang memiliki atribut (properti) dan behavior (method). Objects membantu programmer dalam memisahkan kode yang terkait dengan entitas yang berbeda, sehingga memudahkan proses debugging dan maintenance.

- Objects harus memiliki nama yang menggambarkan entitas yang merepresentasikan. Contohnya: "Player" untuk menggambarkan pemain, atau "Enemy" untuk menggambarkan musuh.

- Objects harus memiliki atribut (properti) yang sesuai, yaitu tidak terlalu banyak namun tidak terlalu sedikit. Atribut harus memberikan informasi yang cukup tentang entitas tersebut.

- Objects harus memiliki behavior (method) yang sesuai, yaitu tidak terlalu banyak namun tidak terlalu sedikit. Behavior harus memberikan informasi tentang tindakan yang dapat dilakukan oleh entitas tersebut.

### Read Documentation

Membaca dokumentasi adalah kemampuan penting bagi seorang game programmer karena dokumentasi merupakan sumber informasi yang tersedia tentang suatu teknologi, framework, atau library yang digunakan dalam pengembangan game. Dengan membaca dokumentasi, Anda dapat memahami cara kerja suatu teknologi, framework, atau library, serta mengetahui fitur-fitur yang tersedia dan cara menggunakannya.

Selain itu, membaca dokumentasi juga membantu Anda dalam menyelesaikan masalah yang muncul selama proses pengembangan game. Banyak masalah yang dapat diatasi dengan membaca dokumentasi resmi yang tersedia, seperti cara menggunakan suatu fitur atau cara mengatasi error yang muncul.

Oleh karena itu, kemampuan membaca dokumentasi sangat penting bagi seorang game programmer agar dapat memahami cara kerja teknologi yang digunakan, serta menyelesaikan masalah yang muncul selama proses pengembangan game.

Pelajari lebih lanjut:
- [PROGRAMMING TIPS oleh Web Programming UNPAS](https://www.youtube.com/playlist?list=PLFIM0718LjIWFcpbvAFK4fDJdx75JrDds)
- ...

# Game Engine

Game engine adalah perangkat lunak yang digunakan untuk membuat game dengan menyediakan beragam fitur seperti rendering, fisika, audio, input, dan lain-lain. Game engine membantu programmer dalam mengelola proses pengembangan game dengan lebih efektif, sehingga mempermudah proses pembuatan game dan meningkatkan kualitas game.

### GDevelop

GDevelop adalah game engine yang mudah digunakan untuk membuat game 2D. GDevelop menyediakan fitur drag-and-drop yang memudahkan programmer dalam membuat game tanpa harus menulis kode. GDevelop juga menyediakan fitur visual scripting yang membantu programmer dalam mengelola logika game dengan lebih mudah.

### LÖVE 2D

LÖVE 2D adalah game engine yang digunakan untuk membuat game 2D dengan menggunakan bahasa pemrograman Lua. LÖVE 2D menyediakan fitur rendering, audio, input, dan lain-lain yang membantu programmer dalam membuat game 2D sesuai kebutuhan.

### Godot

Godot adalah game engine yang digunakan untuk membuat game 2D dan 3D. Godot menyediakan fitur visual scripting yang membantu programmer dalam mengelola logika game dengan lebih mudah. Godot juga menyediakan fitur rendering, fisika, audio, dan lain-lain yang membantu programmer dalam membuat game 2D dan 3D sesuai kebutuhan.

### Unreal Engine

Unreal Engine adalah game engine yang digunakan untuk membuat game 2D dan 3D dengan grafik yang rumit. Unreal Engine menyediakan fitur rendering, fisika, audio, dan lain-lain yang membantu programmer dalam membuat game 2D dan 3D sesuai kebutuhan. Unreal Engine juga menyediakan fitur visual scripting yang membantu programmer dalam mengelola logika game dengan lebih mudah.

### CryEngine

CryEngine adalah game engine yang digunakan untuk membuat game 2D dan 3D dengan grafik yang rumit. CryEngine menyediakan fitur rendering, fisika, audio, dan lain-lain yang membantu programmer dalam membuat game 2D dan 3D sesuai kebutuhan. CryEngine juga menyediakan fitur visual scripting yang membantu programmer dalam mengelola logika game dengan lebih mudah.

## Unity

Unity Engine adalah game engine yang digunakan untuk membuat game 2D dan 3D. Unity Engine menyediakan fitur rendering, fisika, audio, dan lain-lain yang membantu programmer dalam membuat game sesuai kebutuhan. Unity Engine juga menyediakan fitur visual scripting yang membantu programmer dalam mengelola logika game dengan lebih mudah.

Berikut ini adalah beberapa hal yang perlu Anda ketahui tentang Unity Engine sebagai game programmer:

- Unity Engine menggunakan bahasa pemrograman C# sebagai bahasa utama. Sebaiknya Anda memahami dasar-dasar bahasa pemrograman C# sebelum mulai belajar Unity Engine.

- Unity Engine menyediakan fitur editor visual yang membantu programmer dalam mengelola game dengan lebih mudah. Anda perlu memahami cara menggunakan fitur editor visual ini, seperti menambahkan objek, mengatur komponen, dan lain-lain.

- Unity Engine menyediakan fitur fisika yang membantu programmer dalam mengelola interaksi objek dalam game. Anda perlu memahami cara mengatur fisika objek dalam game, seperti gravitasi, tumbukan, dan lain-lain.

- Unity Engine menyediakan fitur animasi yang membantu programmer dalam mengelola gerakan objek dalam game. Anda perlu memahami cara mengatur animasi objek dalam game, seperti menambahkan animasi, mengatur kecepatan animasi, dan lain-lain.

- Unity Engine menyediakan fitur audio yang membantu programmer dalam mengelola suara dalam game. Anda perlu memahami cara menambahkan audio, mengatur volume audio, dan lain-lain.

Pelajari lebih lanjut:
- [Unity Learn by Unity](https://learn.unity.com/)
- [Unity Beginner Tutorials by	Brackeys](https://www.youtube.com/playlist?list=PLPV2KyIb3jR5QFsefuO2RlAgWEz6EvVi6)
- ...

### Scripting

Scripting adalah bagian dari Unity yang memungkinkan programmer untuk menulis kode untuk mengontrol game. Anda perlu memahami cara menulis kode di Unity dengan bahasa pemrograman C# atau UnityScript.

### Input

Input adalah bagian dari Unity yang membantu programmer dalam mengelola interaksi pengguna dengan game. Anda perlu memahami cara mengelola input pengguna, seperti mengatur aksi tombol, mengelola gerakan mouse, dan lain-lain.

### Animation and Movement

Animation and movement adalah bagian dari Unity yang membantu programmer dalam mengelola gerakan objek dalam game. Anda perlu memahami cara mengelola animasi dan gerakan objek dalam game, seperti menambahkan animasi, mengatur kecepatan animasi, dan lain-lain.

### Graphics

Graphics adalah bagian dari Unity yang membantu programmer dalam mengelola tampilan game. Anda perlu memahami cara mengelola grafik dalam game, seperti menambahkan efek visual, mengatur warna, dan lain-lain.

### UI

UI (user interface) adalah bagian dari Unity yang membantu programmer dalam mengelola interaksi pengguna dengan game. Anda perlu memahami cara mengelola UI dalam game, seperti menambahkan elemen UI seperti tombol, teks, dan gambar, mengatur posisi elemen UI, dan lain-lain. Dengan memahami cara mengelola UI, Anda dapat membuat game yang mudah digunakan oleh pengguna.

### Sound and Music

Sound and music adalah bagian dari Unity yang membantu programmer dalam mengelola suara dan musik dalam game. Anda perlu memahami cara menambahkan audio, mengatur volume audio, dan lain-lain.

### Behavior and AI

Behavior and AI adalah bagian dari Unity yang membantu programmer dalam mengelola tingkah laku dan kecerdasan buatan dalam game. Anda perlu memahami cara mengelola tingkah laku dan kecerdasan buatan dalam game, seperti menambahkan AI, mengatur tingkah laku musuh, dan lain-lain.

### Monetization

Monetization adalah bagian dari Unity yang membantu programmer dalam mengelola cara mendapatkan uang dari game. Anda perlu memahami cara mengelola monetisasi dalam game, seperti menambahkan iklan, menjual item dalam game, dan lain-lain.

# Game Physics

Pelajari lebih lanjut:
- [Physics for Game Developers](https://www.oreilly.com/library/view/physics-for-game/9781449361037/)
- ...

## Rigid-Body Dynamics

Rigid-body dynamics adalah bagian dari fisika game yang mengelola interaksi antara objek yang memiliki massa dan momentum yang tidak bisa diubah. Rigid-body dynamics membantu programmer dalam mengelola gerakan objek dalam game sehingga terlihat lebih realistis.

### Realtime Simulation

Realtime simulation adalah proses mengelola gerakan objek dalam game secara real-time. Proses ini membantu programmer dalam mengelola gerakan objek yang terlihat lebih realistis.

### Particles

Particles adalah objek kecil yang digunakan dalam game untuk mengelola efek seperti asap, debu, dan lain-lain. Particles membantu programmer dalam menambahkan efek visual dalam game.

### 2D Rigid-Body

2D rigid-body adalah objek yang hanya memiliki massa dan momentum dalam satu dimensi. 2D rigid-body membantu programmer dalam mengelola gerakan objek dalam game 2D.

### 3D Rigid-Body

3D rigid-body adalah objek yang memiliki massa dan momentum dalam dua dimensi. 3D rigid-body membantu programmer dalam mengelola gerakan objek dalam game 3D.

### Connection Objects

Connection objects adalah objek yang menghubungkan dua objek lainnya. Connection objects membantu programmer dalam mengelola interaksi antara objek dalam game.

### Physics Engine

Physics engine adalah perangkat lunak yang digunakan untuk mengelola fisika dalam game. Physics engine membantu programmer dalam mengelola gerakan objek dalam game secara real-time.

## Physical Modeling

Physical modeling adalah bagian dari fisika game yang mengelola interaksi objek dalam game dengan mempertimbangkan properti fisik yang sesuai dengan objek tersebut. Physical modeling membantu programmer dalam mengelola gerakan objek dalam game sehingga terlihat lebih realistis.

### Aircraft

Aircraft adalah objek yang digunakan untuk mengelola pesawat dalam game. Physical modeling membantu programmer dalam mengelola gerakan pesawat dalam game dengan mempertimbangkan properti fisik seperti lift, drag, dan lain-lain.

### Ships and Boats

Ships and boats adalah objek yang digunakan untuk mengelola kapal dan perahu dalam game. Physical modeling membantu programmer dalam mengelola gerakan kapal dan perahu dalam game dengan mempertimbangkan properti fisik seperti buoyancy, drag, dan lain-lain.

### Cars and Hovercraft

Cars and hovercraft adalah objek yang digunakan untuk mengelola mobil dan hovercraft dalam game. Physical modeling membantu programmer dalam mengelola gerakan mobil dan hovercraft dalam game dengan mempertimbangkan properti fisik seperti traction, drag, dan lain-lain.

### Guns and Explosion

Guns and explosion adalah objek yang digunakan untuk mengelola senjata dan ledakan dalam game. Physical modeling membantu programmer dalam mengelola gerakan senjata dan ledakan dalam game dengan mempertimbangkan properti fisik seperti momentum, kekuatan ledakan, dan lain-lain.

### Sports

Sports adalah objek yang digunakan untuk mengelola olahraga dalam game. Physical modeling membantu programmer dalam mengelola gerakan olahraga dalam game dengan mempertimbangkan properti fisik seperti kinerja atlet, gaya guling, dan lain-lain. Dengan memahami physical modeling, Anda dapat membuat game olahraga yang terlihat lebih realistis.

## Digital Physics

Digital physics adalah bagian dari fisika game yang mengelola interaksi objek dalam game dengan menggunakan teknologi digital. Digital physics membantu programmer dalam mengelola gerakan objek dalam game sehingga terlihat lebih realistis.

### Touch Screen

Touch screen adalah teknologi yang memungkinkan pengguna untuk mengontrol game dengan menyentuh layar. Digital physics membantu programmer dalam mengelola interaksi pengguna dengan game melalui layar sentuh.

### GPS

GPS (Global Positioning System) adalah teknologi yang memungkinkan pengguna untuk mengetahui posisi geografisnya. Digital physics membantu programmer dalam mengelola interaksi pengguna dengan game melalui GPS.

### 3D Display

3D display adalah teknologi yang memungkinkan pengguna untuk melihat game dalam bentuk 3D. Digital physics membantu programmer dalam mengelola interaksi pengguna dengan game melalui 3D display.

### Optical Tracking

Optical tracking adalah teknologi yang memungkinkan pengguna untuk mengontrol game dengan menggerakkan objek di depan kamera. Digital physics membantu programmer dalam mengelola interaksi pengguna dengan game melalui optical tracking.

### Sound

Sound adalah teknologi yang memungkinkan pengguna untuk mengelola suara dalam game. Digital physics membantu programmer dalam mengelola interaksi pengguna dengan game melalui suara.


# Computer Graphics

Computer graphics adalah bagian dari game programming yang mengelola tampilan visual dalam game. Computer graphics membantu programmer dalam mengelola grafik dalam game sehingga terlihat lebih realistis.

## Light and Shadow

Light and shadow adalah bagian dari computer graphics yang mengelola cahaya dan bayangan dalam game. Light and shadow membantu programmer dalam menambahkan realisme pada game dengan memperhitungkan interaksi cahaya dengan objek.

### Shadow Map

Shadow map adalah teknik yang digunakan dalam computer graphics untuk mengelola bayangan dalam game. Shadow map membantu programmer dalam menambahkan realisme pada game dengan memperhitungkan interaksi cahaya dengan objek.

Shadow map menggunakan teknik pencahayaan yang disebut "depth map" untuk menyimpan informasi jarak antara sumber cahaya dan objek dalam game. Depth map ini kemudian digunakan untuk menentukan apakah suatu titik dalam game terkena cahaya atau tidak. Jika titik tersebut terkena cahaya, maka bayangan tidak akan muncul. Sebaliknya, jika titik tersebut tidak terkena cahaya, maka bayangan akan muncul.

### Light Source

Light source adalah sumber cahaya yang digunakan dalam computer graphics untuk mengelola cahaya dalam game. Light source membantu programmer dalam menambahkan realisme pada game dengan memperhitungkan interaksi cahaya dengan objek.

Light source dapat berupa lampu, sinar matahari, atau sumber cahaya lainnya. Light source dapat memiliki berbagai properti seperti intensitas cahaya, warna cahaya, dan lain-lain. Dengan memahami shadow map dan light source, Anda dapat membuat game yang terlihat lebih realistis dengan menambahkan bayangan dan cahaya yang sesuai.

## Shader

Shader adalah bagian dari computer graphics yang mengelola pencahayaan dan efek visual dalam game. Shader membantu programmer dalam menambahkan realisme pada game dengan memperhitungkan interaksi cahaya dengan objek dan menambahkan efek visual seperti refleksi, transparansi, dan lain-lain.

### Rendering Equation

Rendering equation adalah persamaan matematis yang digunakan dalam computer graphics untuk mengelola pencahayaan dan efek visual dalam game. Rendering equation membantu programmer dalam menambahkan realisme pada game dengan memperhitungkan interaksi cahaya dengan objek dan menambahkan efek visual seperti refleksi, transparansi, dan lain-lain.

### Reflection

Reflection adalah efek visual yang muncul ketika cahaya mengenai suatu permukaan dan terrefleksi kembali ke penonton. Reflection dapat ditambahkan ke dalam game dengan menggunakan rendering equation dan memperhitungkan interaksi cahaya dengan permukaan yang terkena.

### Mapping

Mapping adalah teknik yang digunakan dalam computer graphics untuk mengelola pencahayaan dan efek visual dalam game. Mapping membantu programmer dalam menambahkan realisme pada game dengan memperhitungkan interaksi cahaya dengan objek dan menambahkan efek visual seperti refleksi, transparansi, dan lain-lain.

Mapping dapat menggunakan berbagai teknik seperti texture mapping, bump mapping, dan lain-lain. Dengan memahami rendering equation, reflection, dan mapping, Anda dapat membuat game yang terlihat lebih realistis dengan menambahkan efek pencahayaan dan visual yang sesuai.


# Advance Topics

## Artificial Intelligence

Artificial intelligence (AI) adalah bagian dari game programming yang mengelola tingkah laku dan keputusan dari objek dalam game. AI membantu programmer dalam menambahkan realisme pada game dengan memperhitungkan tingkah laku dan keputusan yang sesuai dengan objek tersebut.

### Machine Learning

Machine learning adalah bagian dari artificial intelligence yang menggunakan teknik pembelajaran mesin untuk memprediksi tingkah laku dan keputusan dari objek dalam game. Machine learning membantu programmer dalam menambahkan realisme pada game dengan memperhitungkan tingkah laku dan keputusan yang sesuai dengan objek tersebut.

Untuk menggunakan machine learning dalam game, programmer harus memiliki pengetahuan tentang teknik pembelajaran mesin seperti regresi, klasifikasi, dan clustering. Selain itu, programmer juga harus memiliki pengetahuan tentang cara mengolah data dan mengimplementasikannya dalam game.

Dengan memahami artificial intelligence dan machine learning, Anda dapat membuat game yang terlihat lebih realistis dengan menambahkan tingkah laku dan keputusan yang sesuai dengan objek dalam game.

## Online Multiplayer

Online multiplayer adalah bagian dari game programming yang mengelola interaksi antar pengguna dalam game secara online. Online multiplayer membantu programmer dalam menambahkan fitur multiplayer ke dalam game sehingga pengguna dapat bermain bersama secara online.

Untuk menggunakan online multiplayer dalam game, programmer harus memiliki pengetahuan tentang teknik networking seperti TCP/IP, UDP, dan HTTP. Selain itu, programmer juga harus memiliki pengetahuan tentang cara mengelola server dan mengimplementasikannya dalam game.

### Server

Server adalah bagian dari online multiplayer yang mengelola koneksi antar pengguna dalam game. Server membantu programmer dalam menjaga koneksi antar pengguna tetap stabil dan memungkinkan pengguna untuk bermain bersama secara online.

### Networking

Networking adalah bagian dari online multiplayer yang mengelola komunikasi antar pengguna dalam game. Networking membantu programmer dalam mengirim dan menerima data antar pengguna sehingga pengguna dapat bermain bersama secara online.