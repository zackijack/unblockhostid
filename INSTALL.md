# Cara Install
Sebelumnya, download filenya dulu melalui link ini [unblockhostid-master.zip](https://github.com/gvoze32/unblockhostid/archive/master.zip), kemudian lanjut cara dibawah.

## Windows

Jalankan UNBLOCKHOSTID.exe dengan "Run as administrator", klik Apply, selesai.

*Note: Mungkin akan terdeteksi sebagai virus, oleh karena itu matikan antivirus sebelum menggunakan.*

## Android

#**Root**#

**Manual**

Copy file hosts.

Buka folder /etc dan paste.

Akan ada peringatan replace, pilih replace.

Restart hp.

File hosts telah berhasil diinstall, silahkan cek sendiri dengan cara membuka website yang ada di daftar.

**Aplikasi**

Bisa juga melalui aplikasi AdAway yang bisa didownload [disini](https://f-droid.org/repo/org.adaway_61.apk)

Lalu install seperti biasa.

Buka dan grant akses root

Hapus semua centang pada hosts sources

```1.``` Klik add lalu menuju ke [GitCDN](https://raw.githack.com/) kemudian paste link berikut di kolom yang sudah disediakan (Thx to @alfaindomart)

```
https://github.com/gvoze32/unblockhostid/blob/master/hosts
```
Kemudian akan muncul link dibawah "Use this URL in production"

```2``` Atau kamu bisa langsung menggunakan ini

```
https://gitcdn.xyz/repo/gvoze32/unblockhostid/master/hosts
```

Salin salah satu kode diatas lalu kembali ke AdAway dan tambahkan

Centang opsi "Allow Redirections" di Settings (Thx to @TrixPone)

Apply.. Selesai..

#**Non-Root**#

Sebelumnya. install Hosts Go terlebih dahulu
https://play.google.com/store/apps/details?id=dns.hosts.server.change

Buka aplikasinya, klik "Hosts Setting", Pilih filenya (file hosts yang telah di download), kemudian start

## Linux / BSD / macOS

Buka terminal, lalu ketik atau salin kode di bawah ini

```
curl -sfLS https://gitcdn.xyz/repo/gvoze32/unblockhostid/master/hosts >> /etc/hosts
```
