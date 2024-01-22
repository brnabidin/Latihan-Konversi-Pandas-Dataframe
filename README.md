# Latihan-Konversi-Pandas-Dataframe

Tahapan Latihan
Pandas memiliki fungsi untuk mengubah data dari berbagai jenis menjadi dataframe. Tahapan dalam mengubah data menjadi dataframe adalah sebagai berikut:

- Persiapkan dataset yang akan dikonversi.
- Impor library Pandas.
- Gunakan fungsi read_csv() untuk mengonversi data.

Codelab
Pertama kita bisa buka Google Colab, dengan mengunjungi tautan colab.research.google.com. Anda bisa menekan tombol Notebook Baru pada halaman pertama.

![20200430140224d920072d867534a5f2e0aed6bc5440ee](https://github.com/brnabidin/Latihan-Konversi-Pandas-Dataframe/assets/67081096/3990a3ac-a020-4516-953f-1c891afddaf6)

Colab memiliki direktori yang menyimpan berkas-berkas umum yang dapat dipakai untuk berbagai keperluan. Berkas-berkas bawaan tersebut disimpan dalam sebuah direktori bernama ‘sample_data’.

Untungnya, notebook pada Colab kita memiliki berkas csv yang dapat kita pakai untuk mencoba library pandas. Anda juga bisa melihat beberapa berkas bawaan yang disediakan Colab dengan menggunakan library os.

![1](https://github.com/brnabidin/Latihan-Konversi-Pandas-Dataframe/assets/67081096/a8b291e1-cd67-490d-bc05-5ac5a245d6e8)

Pada notebook baru, kita akan melakukan Import library pandas dan memberikan alias pd untuk library tersebut. Memberikan alias pd terhadap library pandas adalah praktek yang umum dilakukan para pengembang ML.

![2](https://github.com/brnabidin/Latihan-Konversi-Pandas-Dataframe/assets/67081096/bbcd1341-1fd3-4e4b-95c1-39b175d7ff61)

Pada latihan ini kita akan mencoba melakukan konversi dari berkas ‘california_housing_train.csv’ yang merupakan bawaan dari Colab. Untuk mengubah berkas csv menjadi dataframe, kita menggunakan fungsi read_csv() pada library pandas kemudian menyimpannya pada sebuah variabel yaitu df.

![image](https://github.com/brnabidin/Latihan-Konversi-Pandas-Dataframe/assets/67081096/9165c7d8-a13e-49a6-95ac-6a63c42d9cbf)

Untuk melihat apakah konversi berhasil, Anda bisa memanggil fungsi head() pada dataframe. Lalu jalankan cell tersebut dengan klik tombol run ![20201002172024b268cca4d74c205519f3247968799487](https://github.com/brnabidin/Latihan-Konversi-Pandas-Dataframe/assets/67081096/1c50af05-ff07-4be3-9ebf-c3439c7d4716)
di sebelah kiri. Fungsi head() akan menampilkan 5 baris teratas dari sebuah dataframe. 

Jika keluaran dari cell seperti di bawah, maka selamat, Anda berhasil melakukan konversi.

![20200430141515bc3e5f07d2baea9d00b348eea83d723d](https://github.com/brnabidin/Latihan-Konversi-Pandas-Dataframe/assets/67081096/ea4d694c-99c2-463f-93a7-c355dc160e34)

