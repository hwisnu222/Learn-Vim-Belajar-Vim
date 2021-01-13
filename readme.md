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

:w name_file.txt = membuat file dengan nama
     
atau juga membuat file didalam folder
   
:w ./folder1/folder2/name-file.txt
 
untuk membuat file didalam folder yang sama

:w %:h/name-file.txt

:Ex (explore)=kemudian ketik tombol "d". Dan beri nama folder

gg = memindahkan kursor ke awal kode

GG = memindahkan kursor ke akhir kode

dd = menghapus kode 1 line pada posisi kursor berada

4k = memindahkan kursor ke 4 baris keatas. kursor akan dipindahkan ke baris sesuai nomor

d4k = menghapus kode 4 baris dari kursor

{ = memindahkan kursor ke kurung kurawal atas, begitupun sebaliknya

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
````

## Membuka terminal

```
Mode Normal / INSERT 

ctrl+t
```

## Multi Cursor

```
Mode Normal

ctrl+arrow down  atau ctrl+arrow up

untuk keluar dari multi kursor tekan Q(shift+q)

```

## Mengubah lebar dan tinggi screen

```
mode normal

letakan kursor pada screen yang akan diubah lebar atau tingginya

kemudian tekan 

ctrl+arrow < > ^ 

misal : ctrl+ arrow keatas = digunakkan untuk mengatur ketinggian screen
```
## Mengaktifkan nerdtree

```
ctrl+z
```



❤ happy day
