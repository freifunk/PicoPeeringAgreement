# Pico Peering Agreement v1.0 #

## Pendahuluan ##

Pada saat ini, telah banyak tumbuh RT/RW-net (community network), akan tetapi mereka terpisah satu sama lain secara geografis dan sosial, dan tidak membentuk jaringan yang koheren. Dokumen ini berusaha untuk mengkaitkan pulau-pulau jaringan ini dengan memberikan sebuah template base line untuk kesepakatan peering antar individu pemilik node - Pico Peering Agreement.

PPA adalah salah satu cara untuk memformalkan interaksi antar dua peer. Pemilik dari node dapat mengklaim (memberitahukan) hak kepemilikannya dengan cara mendeklarasikan keinginan mereka untuk mendonasikan pertukaran data secara cuma-cuma / gratis melalui jaringan mereka.

PPA di maintain di http://picopeer.net sebuah group sukarelawan dari seluruh dunia. Dokumen ini dimaksudkan untuk template untuk dokumen dan lisensi peering skala-kecil.

## Perjanjian ##

### 1. Free Transit: ###

* Pemilik setuju untuk memberikan transit gratis melalui jaringan mereka..
* Pemikik setuju untuk tidak memodifikasi atau mengubah data pada saat data melalui jaringan mereka..

### 2. Komunikasi Terbuka: ###

* Pemilik setuju untuk mempublikasikan informasi yang dibutuhkan agar terjadi peering.
* Informasi ini harus di lakukan tanpa perlu lisensi.
* Pemilik setuju agar dapat dihubungi dan dapat memberikan sedikitnya sebuah alamat e-mail.

### 3.Tidak ada Garansi: ###

* Tidak ada garansi dari servis level.
* Servis diberikan apa adanya, tanpa garansi maupun liability apapun.
* Servis dapat di turunkan atau di putuskan setiap waktu tanpa pemberitahuan.

### 4. Terms dari Penggunaan: ###

* Pemilik berhak untuk memformulasikan 'acceptable use policy'
* Hal ini mungkin atau mungkin tidak mengandung informasi tentang servis tambahan yang dapat diberikan (sebagai tambahan dari servis akses dasar)
* Pemilik bebas untuk memformulasikan kebijakan ini selama tidak berlawanan dengan poin 1 s/d 3 dari perjanjian ini (lihat point 5).

### 5. Tamban Lokal: ###

(untuk di isi secara ad-hoc oleh pemilik node pada saat dokumen ini di implementasikan)

## Definisi dari istitilah ##

* Pemilik: Pemilik dari node mempunyai hak untuk mengoperasikan peralatan jaringan mereka dan untuk mendonasikan sebagian dari fungsinya untuk FreeNetwork
* Transit: Transit adalah pertukaran data ke dalam, ke luar atau melalui sebuah jaringan
* Free Transit: Free transit berarti pemilik tidak akan men-charge data yang transit maupun memodifikasi data.
* Free Network: The Free Network adalah sejumlah resource hardware dan software yang saling terinterkoneksi, yang mana FreeTransit di donasikan oleh pemilik dari resource tersebut
* Servis: Service terdiri dari Free transit dan Servis tambahan
* Servis Tambahan: Dalam PPA, servis tambahan adalah apapun di luar Free Transit. Contoh, keberadaan DHCP server, web server atau mail server

## PPA dalam praktek ##

PPA sebaiknya di implementasikan dalam format data yang dapat dibaca menurut standard di database di node jaringan komunitas untuk memfasilitasi interkoneksi automatis dari node.