# Modul-3

### Points And Currency

Points adalah fitur dimana player akan mendapatkan point ketika melakukan sesuatu (untuk kasus top-down shooter biasanya point berupa "enemy killed")

Currency adalah fitur dimana player bisa mendapatkan currency (bisa uang/science point/material)

## Let's Make It !! 

### 1. Game Object 

karena currency adalah sesuatu yang bisa didapatkan berarti kita membutuhkan **Game Object** yang nantinya akan bisa ditabrak untuk mendapatkannya

### 2.collider

currency bisa ditabrak/ di-collect, fungsi collider disini untuk mendeteksi apakah player sedang berada dalam jangkauan object currency nya.

### 3.Manager

currency dan points perlu di manage, arsitektur yang relatif mudah untuk digunakan adalah menggunakan manager untuk menyimpan nilai dari currency/point yang sudah dikumpulkan.

### 4.UI

UI disini berfungsi untuk menampilkan jumlah currency/points yang sudah dimiliki player

### 5. Events

event berfungsi untuk komunikasi antar script. design pattern seperti ini juga biasa digunakan untuk mengurangi **dependency pada script**
