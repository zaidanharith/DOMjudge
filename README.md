# Cara Install Domjudge dengan Docker dan Ubuntu Server

Created by : [Zaidan Harith](https://github.com/zaidanharith)

Instagram : [@zaidanharith\_](https://instagram.com/zaidanharith_)

## 1. Instalasi Ubuntu Server dengan Virtual Machine (VirtualBox)

Bagi kalian yang sistem operasinya selain Linux (Ubuntu), kalian bisa men-_download_ dan meng-_install_ Virtual Machine terlebih dahulu agar bisa menjalankan Ubuntu Server di sistem operasi kalian. Untuk Virtual Machine yang akan digunakan adalah Oracle VirtualBox.

Untuk instalasi Ubuntu Server dan Oracle VirtualBox, kalian bisa mengikuti tutorial Youtube berikut :

[Tutorial Instalasi Ubuntu Server dan VirtualBox](https://youtu.be/ElNalqvVaPw?feature=shared)

Video by : [babarehner](https://www.youtube.com/@babarehner)

## 2. Instalasi NGINX di Ubuntu Server

Setelah Ubuntu Server di-_install_ di dalam Virtual Machine (VirtualBox), kita perlu meng-_install_ NGINX di dalam Ubuntu Server agar dapat menjalankan Web Server. Langkah-langkah instalasi adalah sebagai berikut :

1. Pada Ubuntu Server, ketikkan `sudo apt update` agar Ubuntu Server lebih _update_.
2. NGINX dapat di-_install_ dengan mengetik `sudo apt -y install nginx`.
3. NGINX sudah terpasang di Ubuntu Server. Untuk mengecek apakah NGINX sudah berjalan atau belum, ketikkan `sudo systemctl status nginx`. Apabila berhasil, tampilan Ubuntu Server akan seperti berikut :

![NGINX: Status Berhasil](nginx-status.png)

4. Untuk menjalankan NGINX pada Web Browser, ketikkan alamat IP pada URl. Alamat IP Server dapat diketahui dengan mengetik `ip a`. Tampilan Web Browser apabila NGINX berhasil berjalan seperti berikut :

![NGINX: Tampilan Web](nginx-web.png)

> Sebelum kita lanjut ke langkah selanjutnya, agar mempermudah kalian dalam mengikuti langkah ini dan ke depannya, kita akan menghubungkan Ubuntu Server ini dengan terminal yang ada di sistem operasi kita dengan menggunakan SSH. Agar dapat terhubung dengan Ubuntu Server, pada terminal di sistem operasi kalian, ketikkan _command_ berikut :`ssh [username ubuntu server]@[alamat ip]>` > <br>
> Contoh : `ssh zaidanharith@192.168.123.456>` > <br>
> Ketik _Enter_ dan kalian akan diminta memasukkan _password_ Ubuntu Server untuk _username_ tersebut. Setelah memasukkan _password_, terminal kalian sudah berhasil terhubung ke Ubuntu Server. Oleh karena itu, untuk mengikuti beberapa langkah ke depannya, kalian disarankan untuk mengggunakan Ubuntu Server di terminal sistem operasi kalian.

## 3. Instalasi Docker di Ubuntu Server

Langkah instalasi Docker di dalam Ubuntu Server :

1.

## 4. Instalasi Domserver di Ubuntu Server dengan Docker
