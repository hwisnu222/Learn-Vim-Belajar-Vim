# Learn Vim || Belajar VIM

## Mode dalam vim

NORMAL =    ESC 

INSERT = i

VISUAL = v


## perintah pada vim

untuk melakukan perintah dibawah ini terlebih dahulu ubah kedalam mode normal.
dan setiap perintah menggunakan tanda titik sama dengan pada awal perintah

```
:q = untuk keluar dari vim

:q! = digunakkan untuk keluar dari kode editor tanpa menyimpan perubahan pada file

:w = untuk menyimpan perubahan file

:wq untuk menyimpan perubahan sekaligus keluar dari kode editor


```

## Copy paste code

```
Mode visual

copy = y

cut = d

paste = p

untuk mempaste dibawah kode mengukan p(kecil). untuk sebelum kode menggunakan P(besar)
```

## Copy paste dari system ke vim atau sebaliknya

untuk melakukan perintah dibawah terlebih dahulu daftarkan ke register dulu.

copy paste kode dibawah ke init.vim

```
set termencoding=utf-8

set encoding=utf-8
```

```
Mode normal

Copy dari vim ke system

"+y (tanda plusnya juga ikut ditekan)

untuk mempastenya menggunakkan seperti bisasanya yaitu dengan ctrl+v

cara paste dari system ke vim

"+p (tanda plusnya juga ikut ditekan)

```

## Split

split secara vertical

```
Mode normal

ketikan perintah dibawah

untuk split secara vertical

:vsp

untuk split secara horizontal

:sp


```

## Pindah antar screen split

```
Mode Normal

ctrl+ww

atau bisa juga menggunakkan dibawah ini

ctrl+k = untuk pindah kursor keatas

ctrl+j = untuk pindah kursor kebawah

ctrl+h = untuk pindah kursor ke arah kiri

ctrl+l = untuk pindah kursor ke kanan
```

## Membuka terminal

```
Mode Normal / INSERT 

ctrl+t
```

## Mengubah lebar dan tinggi screen

```
mode normal

letakan kursor pada screen yang akan diubah lebar atau tingginya

kemudian tekan 

ctrl+arrow < > ^ 

misal : ctrl+ arrow keatas = digunakkan untuk mengatur ketinggian screen
```




❤ happy day
