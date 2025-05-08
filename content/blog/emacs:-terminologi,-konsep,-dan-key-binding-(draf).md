---
title: Emacs: Terminologi, Konsep, dan Key Binding (draf)
date: 2025-04-25T03:30:37.969Z
---




## Apa itu EMACS?
EMACS atau GNU EMACS merupakan teks editor gratis, dikembangkan sejak [tahun 1976][wiki1] yang dapat disandingkan dengan teks editor seperti VI (Vim dan Neovim merupakan turunan teks editor ini). EMACS merupakan teks editor yang masih aktif dikembangkan dengan fitur yang kaya seperti halnya teks editor modern seperti VS Code. EMACS dapat dikatakan sebagai editor yang matang, sangat dapat dikustomisasi, dan dikembangkan dengan bahasa pemrogramannya sendiri yang disebut sebagai *emacs lisp* (file konfigurasinya juga menggunakan *emacs lisp* dengan ekstensi file *.el*). 

[wiki1]: https://id.wikipedia.org/wiki/Emacs

Bagi pengguna VS Code yang tidak asing dengan ekstensi yang sangat membantu untuk menyesuaikan lingkungan pengembangan semudah mendowload file, fitur seperti ini juga tersedia pada EMACS yang memiliki beberapa *repository package* yang dapat diunduh untuk mempermudah pengguna ketika menggunakan EMACS. Dua repository EMACS yang populer seperti *elpa* (official dari pengembang EMACS) dan *melpa* (non-official) yang sangat mencukupi kebutuhan user untuk tugas-tugas pemrograman sederhana ataupun kompleks. Pada versi 29+, EMACS telah mendukung konfigurasi *tree-sitter*--konfigurasi syntax highlight modern--secara *default* yang memungkinkan EMACS menyediakan *syntax highlight* pada bahasa pemrograman baru yang tidak tersedia pada repository EMACS.

EMACS tersedia pada beberapa jenis platform seperti GNU/Linux, BSDs, Windows, macOS, dan yang terbaru adalah Android. Kasus yang paling logis EMACS tersedia pada perangkat android tidak lain untuk menyediakan dukungan pada perangkat dengan ChromeOS dan bukan mobile--akan sangat berlebihan *overkill* jika hanya digunakan untuk perangkat mobile.
## Terminologi pada EMACS
EMACS memiliki keunikan tersendiri termasuk pemakaian istilah teknis terkait cara EMACS mengontrol atau memanipulasi teks serta proses teknis lainnya yang sangat jauh berbeda dengan teks editor lain. EMACS tidak berbagai terminologi yang sama pada sebagian besar teks editor modern dan berbagai sedikit terminologi yang sama dengan VI atau Vim, sisanya memiliki terminologi yang berbeda karena karakteristik EMACS yang berbeda dengan text editor lain. Berikut konsep dan istilah yang anda dapatkan ketika menggunakan EMACS:

- *frame* dan *window*. Karena alasan historis dimana desktop komputer saat EMACS pertama kali diperkenalkan masih belum memiliki GUI (*Graphical User Interface*) seperti halnya desktop modern dengan banyak window aplikasi yang dapat dibuka dalam satu waktu, EMACS menggunakan istilah *frame* untuk istilah *window* pada desktop modern dan *window* pada EMACS merujuk pada *buffer* lain yang terbuka pada frame yang sama seperti halnya jendela split pada VI dan turunannya.
- *Buffer*. Semua file pada EMACS disebut *buffer*, karena setiap teks yang dapat ditulis pada EMACS sifatnya sementaray (*temporary*). Bahkan baris command yang berada di *frame* bawah yang digunakan untuk melakukan kontrol, kustomisasi, dan hal mekanisme lainnya disebut *mini-buffer*. *Buffer* disebut file ketika *buffer* di simpan di dalam *persitent storage* atau penyimpanan permanen.
- *Kill*. sama  dengan *cut* atau memotong karakter, word, text, file, atau direktory. Text atau file yang di *kill* akan tersimpan di dalam *kill-ring*.
- *Kill-ring*. memiliki konsep yang sama dengan *clipboard* atau boleh dibilang merupakan *clipboard* itu sendiri dan dapat di diakses di luar lingkungan pengembangan EMACS (berbeda dengan VI atau Vim yang membutuhkan extra command untuk melakukan hal yang sama diluar lingkungan pengembangannya). *Kill-ring* sendiri memiliki mekanisme yang sama dengan clipboard windows 11 yang dapat menyalin dan menyimpan teks/item lebih dari satu.
- *Yank*. sama dengan *paste* yang mengambil teks terakhir dari *kill-ring*.
- *kill-ring-save*. dapat diartikan sebagai *copy* yang menyalin teks tanpa menghapusnya ke *kill-ring*.
- *region*. Merupakan bagian teks yang di blok oleh cursor.
- *dired*. Merupakan file manager EMACS.

## Key Binding 



(Draf)

|[🌳My Link Tree](https://lynx.boo/triilman)|[If this blog interesting, give me stars](https://github.com/triilman25/tinymind-blog "Don't give me stars if you feel sorry or because of relationships. Your advice more meaningful to me")|[📧MY EMAIL](https://letterbird.co/ilmanfattah25)|
|:---|:---:|---:|

[![GitHub Repo stars](https://img.shields.io/github/stars/triilman25/tinymind-blog?style=for-the-badge&labelColor=%23dfe4ea&color=%23ffffff&link=https%3A%2F%2Fgithub.com%2Ftriilman25%2Ftinymind-blog)](https://github.com/triilman25/tinymind-blog "Because this blogs just using one repository, so the stars are accumulated result of all of blogs.") 
![HackerNews User Karma](https://img.shields.io/hackernews/user-karma/triilman?style=for-the-badge&color=orange)


![Written-By-Human-Not-By-AI-Badge-white.png](https://github.com/triilman25/tinymind-blog/blob/main/assets/images/2024-10-26/1729917860180.png?raw=true)