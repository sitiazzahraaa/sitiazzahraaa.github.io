---
layout: post
title: "HTML Link dan Lists"
---

HTML LINK dan LISTS - Penjelasan tentang link dan list pada html

<li><b>LIST dalam HTML</b></li>
List merupakan cara penulisan yang sering digunakan untuk membuat daftar berurutan. Terdapat 3 macam list yang ada di HTML yaitu <b>ordered list</b>, <b>unordered list</b> dan <b>description list</b>. Cara membuat list di HTML tentunya berbeda-beda sesuai jenisnya. Ketiga macam list HTML tersebut juga memiliki tampilan dan fungsi yang berbeda.<br><br>Perbedaan penulisan ketiga jenis ini terdapat pada pembuka dan penutupnya saja. Sedangkan untuk membuat item pada ordered dan unordered list menggunakan elemen yang sama yaitu < li > ... < /li >. Untuk mengetahui lebih dalam masing-masing list tersebut kita akan bahas satu-persatu.
<ol type="1">
    <b><li>Ordered List</li></b>
    Ordered list adalah jenis list berurutan yang ditampilkan dengan menggunakan angka atau nomor atau huruf. Ordered list biasa digunakan untuk menampilkan daftar item yang membutuhkan penomoran. Ordered list atau list angka/nomor dibuat dengan menggunakan tag < ol >. Penulisan item-item list tersebut menggunakan tag < li > yang diletakkan diantara tag pembuka < ol > dan tag penutup < /ol >. Ordered list juga memiliki beberapa atribut yaitu huruf (a, b, c dst), huruf kapital (A, B, C dst), huruf romawi kecil (i, ii, iii dst), huruf romawi kapital (I, II, III dst), dan angka (1, 2, 3 dst).
    <b><li>Unordered List</li></b>
    Unordered list adalah jenis list yang tidak berurutan yang ditampilkan dengan menggunakan simbol. Unordered list digunakan untuk menampilkan daftar list yang tidak memerlukan angka pengurutan. Unordered list atau list simbol dibuat dengan menggunakan tag < ul >. Sama dengan list sebelumnya, item-item ini ditulis dengan menggunakan tag < li > yang terletak didalam elemen < ul >. contoh simbol * , - dsb.
    <b><li>Description List</li></b>
    Description list adalah jenis list yang digunakan untuk menampilkan istilah dan penjelasannya seperti kampus. Description list jarang digunakan jika dibandingkan 2 jenis list sebelumnya. Jika kita hanya perlu 2 tag pada ordered dan unordered list, maka untuk menulis description list kita membutuhkan 3 tag HTML yaitu tag < dl > , tag < dt > dan tag < dd >. Tag < dl > digunakan untuk mendefinisikan bahwa kode tersebut adalah description list. Tag < dt > digunakan untuk mengapit istilah (term). Tag < dd > digunakan untuk mengapit penjelasannya (description).
</ol>
<li><b>LINK dalam HTML</b></li>
Link atau <i>Hyperlink</i> adalah elemen HTML yang berfungsi menghubungkan suatu halaman web ke halaman web yang lain. Elemen ini bisa diklik, dan nanti akan membuka halaman lain sesuai alamat URL yang diberikan. Tidak hanya untuk menghubungkan halaman, link juga punya fungsi lain seperti <i>scroll top</i>, download file, menjalankan fungsi javascript, dll. 

<img src="/assets/images/link pick.jpg" width="300px">
<i>pict by petani.kode.com</i>

Berdasarkan alamat URL ynag dituju, link pada HTML dibagi menjadi dua kelompok;

<ol type="1">
    <b><li>Internal Link</li></b>
    Internal link adalah link yang menuju ke domain atau halaman web itu sendiri. Masih berada didalam web, namun berpindah halaman-<i>page</i>.
    <b><li>External Link</li></b>
    External link adalah link menuju domain lain. Biasanya digunakan untuk menghubungkan halaman yang satu dengan yang lainnya dalam satu atau domain.
</ol>