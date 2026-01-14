---
title: Handmade Hero oleh Casey Muratori: Apa yang Kita Dapat dalam Lima Hari Pembelajaran Intensif (Bagian 1)
date: 2026-01-13T12:42:09.268Z
---


Bagi seorang penggiat komputer, _programmer_, atau _computer scientist_ yang ingin atau baru pertama kali mencoba terjun ke dunia  grafik komputer (_Computer graphic_) pasti menjumpai dan akan sering menjumpai disebagian besar API _graphic rendering_ tutorial (vulkan, openGL dll.), sebagai mukadimah, menjelaskan cara menggambar segitiga pertama dilayar _display_ Anda. 
Seperti tugas yang mudah bukan! Ini dapat dianggap "_hello world!_" didunia  grafik komputer sebagaimana MNIST untuk _machine learning_.
![image.png](https://raw.githubusercontent.com/triilman25/tinymind-blog/main/assets/images/2026-01-14/1768374803397.png "Vulkan Tutorial oleh Alexander Overvoorde (2025)")
 
Tugas yang tampak mudah ini merupakan landasan pengenalan yang penting kepada Anda tentang bagaimana data disusun dan dimanipulasi; bagaimana CPU berkomunikasi dengan kartu grafis yang menangani data yang akan ditampilkan di layar display Anda; serta bagaimana sistem koordinat kartesius (_Cartesian Coordinate System_) yang dipelajari dalam matematika dasar saling terkait dan mempengaruhi. 

Jika Anda menganggap menggambar segitiga akan sangat mudah, Anda tidak salah dan saya pun akan berpikir begitu jika kita menggunakan alat yang tepat, karena dalam ilmu komputer alat-alat _all in one_, _swiss army knife_, atau peningkat produktivitas dalam pemrograman selalu memiliki komunitas yang aktif mengembangkannya. Anda dapat dengan mudah menggunakan Python dengan library seperti _turtle_ untuk menggambar grafik sederhana, atau yang lebih powerful seperti _manim_ yang dapat membuatkan Anda animasi segitiga dan berbagai bentuk geometri lainnya berotasi, bertranslasi, bertransformasi dan teknik animasi lainnya (channel youtube [3Blue1Brown][a1] merupakan mahakarnya edukasi visual yang dibuat menggunakan manim).

Jadi, _apa yang dilakukan __Handmade Hero__ disini? apa sangkut pautnya grafik komputer dan Handmade Hero? Bukannya Handmade Hero hanya proyek __game development__?_

Jika Anda awam atau tidak tahu Handmade Hero itu apa, pertanyaan pertama dan kedua di atas yang mungkin akan terlintas dibenak Anda. Jika Anda seorang programmer dan masih terlalu baru di dunia ilmu komputer, serta masih tahap belajar dan sedikit tahu tentang Handmade Hero dan game development, Anda akan banyak belajar tentang hubungan yang tidak terpisahkan antara _game development_ dan grafik komputer selama mengikuti tutorial Handmade Hero.

[Handmande Hero][a2] merupakan kompilasi _video streaming_ dari Casey Muratori, seorang veteran di dunia game development--Anda dapat melihat lebih jauh bio [Casey dan proyek yang dikerjakannya][a3], dia juga seorang karib dari _indie game developer_ seperti [Jonathan Blow][a4]--yang direkam selama tiga tahun _streaming_-nya di platform _twitch_ sekitar akhir tahun 2014 - 2017. Ini merupakan upaya inisiatif Casey dalam mengajarkan kaum muda dan developer pemula untuk dapat membuat game mereka sendiri tanpa bergantung pada _game engine_ atau library pihak ketiga--sepenuhnya dari dasar dan hanya bergantung pada API bawaan yang disediakan sistem operasi Windows. Ada banyak hal yang diajarkan Handmade Hero, tetapi pembahasan ini akan dipersempit hanya pada 5 hari pertama yang dibagi menjadi 2 bagian. Bagian __pertama__ sebagai pengenalan dan bagian __kedua__ lebih teknis kearah analisis kode dan fungsinya.

Apa yang akan didapat selama mengikuti 5 hari pembelajaran intensif Handmade Hero? Seperti pada pembuka blog ini, yang akan Anda dapat dari tutorial selama 5 hari ini adalah pondasi dasar untuk membuat segitiga pertama Anda menggunakan bahasa pemrograman C. Handmade Hero sendiri tidak menekankan secara eksplisit pada pembuatan segitiga pertama atau grafik geometri spesifik tetapi Anda mendapatkan hal yang sama terkait bagaimana Anda dapat membuat jendela (_window_), memuat/menggambar objek didalamnya, dan membuat animasi objek sederhana.

_tidak ada yang spesial, dan apa bedanya dengan menggunakan python yang lebih mudah digunakan?_ 

Seperti pada tujuan dari Handmade hero "_build from scratch_" atau buat semuanya dari awal, tutorial ini tidak menawarkan produktivikas dan kemudahan ketika menggunakan python, tetapi lebih menekankan pada bagaimana Anda tidak hanya memahami grafik dari komputer itu sendiri melalui serangkaian manipulasi data dan penempatan koordinat pixel di layar display Anda, juga bagaimana data itu diproses oleh CPU dan di teruskan ke Kartu grafis melalui penggunaan API bawaan Windows. Di sini juga Anda belajar bagaimana cara membaca kode dengan abstraksi rendah ditingkat bahasa Assembly, bagaimana cara melakukan _debugging_ menggunakan Visual Studio, melakukan optimasi kode, memahami _layout memory_/tata letak memory,menemukan _memory leak_/kebocoran memori dan skema atau trik-trik lainnya pada tingkat low-level dengan abstraksi yang lebih rendah yang akan menguatkan pemahaman Anda secara umum dalam ilmu komputer (bukan hanya soal game dan grafik komputer).

Ketika menggunakan abstraksi yang lebih tinggi pada kerangka kerja Anda, maka tingkatan lain yang seharusnya Anda ketahui akan tetap terselubung dan membuat Anda bergantung pada orang lain yang juga akan bergantung pada orang lain lainnya dan akan terus seperti ini dalam siklus rekursi yang semakin dalam. Anda kehilangan pemahaman dasar yang seharusnya dimiliki setiap _programmer_. Itulah kenapa python bukan menjadi solusi pada proyek Handmade Hero (kurang dari segi performa, juga terlalu banyak [abstraksi][a5]). Ini bukan soal segitiga di layar display Anda tetapi ini tentang Anda sendiri sebagai _programmer_. Inilah yang akan Anda dapat dalam 5 hari pemrograman intensif.[] 

 

[a1]: https://www.youtube.com/@3blue1brown
[a2]: https://guide.handmadehero.org/
[a3]: https://caseymuratori.com/about
[a4]: https://en.wikipedia.org/wiki/Jonathan_Blow
[a5]: https://youtu.be/eyx25adnN6A?si=GgxYSLv4j_kXISyH