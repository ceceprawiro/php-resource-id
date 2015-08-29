---
title: "Bagaimana menginstal PHP? Versi PHP mana yang digunakan?"
read_time: "4 min"
updated: "August 29, 2015"
group: "intro"
permalink: "/faq/intro/php-installation/"
---

Instalasi lokal PHP biasanya mudah. Tetapi bagi pengguna baru yang mengawali PHP ini mungkin tidak begitu jelas.

Dalam kebanyakan kasus, Anda dapat menggunakan versi stabil terbaru dari **PHP 5.6** untuk menulis kode baru. Pada server yang dapat diakses publik, versi PHP Anda mungkin beberapa versi di belakang stabil terbaru dari [php.net][php.net]. Hal ini dikarenakan kompatibilitas sistem operasi atau kebijakan perusahaan penyedia hosting. Tetapi janganlah hal ini sampai menghentikan Anda. Di kebanyakan kasus, PHP yang dirilis sangatlah stabil.

## Instalasi Windows

Untuk sistem operasi Windows, Anda dapat men-download binari PHP dan kode sumber dari [windows.php.net][windows-php net]. Banyak juga tersedia paket _all-in-one_ yang berisi PHP, MySQL dan web server seperti Apache atau Nginx. Misalnya:

* [XAMPP][xampp]
* [WAMP][wamp]
* [WPN XM][wpn-xm]
* [Zend Server CE][zend-server]

## Instalasi Linux/Unix

Instalasi PHP di Linux atau sistem operasi berbasis Unix lainnya sebagian besar tergantung pada distribusi yang Anda gunakan. Banyak distribusi Linux yang tersedia tetapi sebagian besar Anda menginstal PHP menggunakan manajer paket (_package manager_).

### Distribusi berbasis Debian

Distribusi Linux berbasis Debian termasuk Debian, Ubuntu. Distribusi berbasis Debian menggunakan manajer paket apt untuk menginstal paket.

```bash
> apt-get install php5
```

### Distribusi berbasis Fedora

Termasuk di dalamnya distribusi seperti Fedora, CentOS, RedHat dan lain-lain. Fedora distribusi menggunakan manajer paket yum untuk paket instalasi.

```bash
> yum install php5
```

Selain paket _all-in-one_ seperti [XAMPP][xampp] dan [AMPPS][ampps], Anda juga dapat menginstal LAMP server dengan Apache, MySQL dan PHP dengan memeriksa `lamp-server` untuk distribusi Anda. Biasanya versi PHP di distribusi Linux adalah beberapa versi di belakang rilis stabil terbaru di PHP.net. Alih-alih kompilasi dan membangun PHP dari kode sumber, Anda dapat menggunakan banyak alternatif pihak ke-3 seperti [dotdeb][dotdeb] untuk Debian, [repositori Ondrej Sury][ondrej-sury-repository] untuk Ubuntu dan [repositori REMI][remi-repository] untuk distribusi berbasis Fedora.

Untuk kompilasi dari sumber kode, periksa [manual PHP][php-manual] untuk mencari tahu petunjuk instalasi di sistem operasi umum berbasis Unix..

## Mac

Instalasi PHP di Mac sudah termasuk dalam OS X.

Semua dalam satu paket untuk Mac OS X:

* [MAMP][MAMP]

Paket _all-in_one_ yang independen terhadap sistem operasi:

* [Ammps][ammps]

## Cara lain instalasi PHP

Cara yang direkomendasikan dan lebih maju dari pengembangan PHP adalah dengan menggunakan software virtualisasi seperti [Virtual Box][virtual-box] dan [Vagrant][vagrant].

[php.net]: http://php.net
[windows-php net]: http://windows.php.net
[xampp]: http://apachefriends.org
[wamp]: http://www.wampserver.com/en/
[wpn-xm]: http://wpn-xm.org/
[zend-server]: http://www.zend.com/en/products/server-ce/
[ammps]: http://www.ampps.com/
[dotdeb]: https://www.dotdeb.org/
[ondrej-sury-repository]: https://launchpad.net/~ondrej
[remi-repository]: http://blog.famillecollet.com/
[php-manual]: http://php.net/manual/en/install.unix.php
[mamp]: http://www.mamp.info/en/downloads/
[ammps]: http://www.ampps.com/
[virtual-box]: https://www.virtualbox.org
[vagrant]: http://vagrantup.com
