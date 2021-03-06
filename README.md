# My convex Hull Library
### IF2211 Strategi Algoritma
Program ini digunakan untuk menampilkan visualisasi tes linear separability dataset dengan menggunakan algoritma divide and conquer.
Tentu saja, program ini utamanya dibuat untuk memenuhi Tugas Kecil 2 IF2211 Strategi Algoritma

Dibuat oleh :
Hilda Carissa Widelia 13520164

## Table of Contents
- [My Convex Hull](#my-convex-hull-library)
  - [Table of Contents](#table-of-contents)
  - [Setup](#setup)
  - [Cara Menggunakan Program](#cara-menggunakan-program)
  - [Contact Me](#contact-me)

## Setup
Berikut langkah untuk setup :
1. Clone repository github ini
2. Masuk folder src
3. Jika belum meng-install library numpy, pandas, matplotlib, dan sklearn silakan ikuti langkah langkah di [sini](#install-packages)
4. Untuk meng-compile program, tinggal tekan button Run All yang ada di bagian atas layar 

### Install Packages
Masukkan keempat perintah dibawah ini di terminal untuk menginstall packages yang dibutuhkan
  ```sh
  pip install numpy
  pip install pandas
  pip install matplotlib
  pip install -U scikit-learn
  ```

## Cara menggunakan program
1. buka folder src
2. buka file ch.ipynb
3. run cell pertama, input nama dataset yang diinginkan, dataset yang tersedia ada iris, wine, dan breast-cancer. Jika user memasukkan input yang tidak sesuai, maka akan digunakan dataset iris.
( input box berada di bagian atas jika menggunakan visual studio code )
4. untuk mengubah kolom yang akan dibandingkan, ubah line 6, 7, dan 10 pada blok 3 dengan index kolom yang sesuai, kolom paling kiri memiliki index 0, dan indexnya bertambah satu ke kanan
 ```sh
    plt.xlabel(data.feature_names[[kolom untuk data di absis]])
    plt.ylabel(data.feature_names[kolom untuk data di ordinat])
    ...
    bucket = bucket.iloc[:,[<kolom absis, kolom ordinat>]].values
  ```
5. Jangan lupa ubah line 5 yang berisi judul sesuai dengan judul yang diinginkan
  ```sh
    plt.title([Judul yang diinginkan])
  ```
6. Tekan run pada blok cell kedua lalu ketiga

## Contact Me
- [Hilda Carissa Widelia](https://github.com/hcarissa)