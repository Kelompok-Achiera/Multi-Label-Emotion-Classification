# Multi-Label Emotion Classification Menggunakan Naive Bayes

Ketua   : Aprialdy Sembiring (11S18024)

Anggota :
- Fitry Yunita Aritonang (11S18020)
- Ivan Johannes Alexander (11S18026)
- Ananda Amelia Siregar (11S18044)
- Maxvania Alarice Manurung (11S18050)
- Ika Fransiska Rehulina Perangin Angin (11S18053)

## Links

- [Google Drive](https://drive.google.com/drive/folders/1nAzxcnC7PCtUsQghJek-iAbXVXKbvDUY?usp=sharing)
- [Dataset (go_emotions by Hugging Face)](https://huggingface.co/datasets/go_emotions)

Try our code Online! [Click Here!](https://github.com/Kelompok-Achiera/Multi-Label-Emotion-Classification#online-code---google-colab-use-guide)

## Datasets
Dataset adalah kumpulan data yang berbentuk himpunan data yang berasal dari informasi-informasi lampau yang siap untuk dikelola menjadi informasi baru. Sebuah dataset harus memiliki tujuan yang bersifat comparable, repeatable, dan verifiable. Pada proyek ini, dataset yang digunakan adalah go_emotions dataset oleh Hugging Face.

Dataset go_emotions milik Hugging face adalah dataset yang terdiri dari 85 ribu komentar berbahasa Inggris dalam situs reddit yang sudah dilabelkan dengan 27 jenis emosi ditambah 1 emosi netral. Dataset ini mendukung pengolahan data untuk sebuah multi-label classification, dimana pada dataset ini, sebuah data bisa memiliki lebih dari satu jenis label emosi didalamnya. Berikut adalah daftar jenis label emosi yang terdapat pada dataset go_emotions.

go_emotions by [HuggingFace](https://huggingface.co/)

- Terdiri dari 27 emosi dan 1 emosi netral
- Bersumber dari komentar pada situs web social media reddit berbahasa Inggris 

> special thanks to dataset publisher [Joe Davidson](https://github.com/joeddav) under [Apache License 2.0](https://github.com/google-research/google-research/blob/master/LICENSE)

### Rumusan Masalah
Bagaimana penerapan MultiLabel Emotion Classification dengan menggunakan Naive Bayes?

### Tujuan pengerjaan proyek
Melakukan identifikasi secara otomatis terhadap  label emosi yang paling dominan dari kalimat  yang terdapat pada dataset.

### Scope
Penelitian dilakukan menggunakan metode Naive  Bayes dengan	menggunakan bahasa  pemrograman python3 dimana dataset yang  digunakan adalah dataset go_emotions dari  Hugging_Face

### Hasil yang diharapkan
Hasil pengerjaan proyek ini diharapkan mampu  untuk mengidentifikasi bermacam-macam label  emosi dalam dataset yang disediakan dengan  Multi-Label Emotion Classification Menggunakan Naive bayes.

# Alasan Pemilihan Studi Kasus dan Metodenya

### Mengapa Multi-Label Emotion Classification?
Multi-Label Classification merupakan metode klasifikasi untuk melakukan prediksi kemungkinan label untuk suatu teks tertentu ataupun bertugas untuk pemodelan prediktif yang melibatkan keluaran label kelas yang diberikan beberapa masukan.

Semakin berkembangnya kemajuan teknologi  menjadikan media sosial sebagai wadah untuk mengekspresikan emosi penggunanya. Emosi merupakan perasaan intens yang berasal dari suasana hati yang ditujukan pada suatu hal. Pengklasifikasian emosi dapat dilakukan dengan metode Multi-Label Classification yang memiliki banyak manfaat seperti mengidentifikasi kepuasan pelanggan terhadap layanan yang diberikan, memprediksi penjualan produk, memantau emosi pengguna, dan lainnya.


### Mengapa Metode Naive Bayes?
Naive Bayes merupakan metode pengklasifikasian atau pengelompokan data berdasarkan probabilitas. Kami memilih metode Naive Bayes karena metode ini merupakan salah satu algoritma klasifikasi yang memiliki waktu pemrosesan yang cepat dan mendapatkan nilai error yang lebih kecil bila diterapkan pada kumpulan data (dataset) yang besar. Naive Bayes digunakan untuk mengklasifikasikan sebuah teks dan digunakan dalam metode machine learning yang menggunakan probabilitas.
Naive Bayes  didasarkan  pada  asumsi  penyederhanaan  bahwa  nilai  atribut  secara kondisionalsaling  bebas  jika  diberikan  nilai output.  Dengan  kata  lain,  diberikan  nilai output, probabilitas  mengamati  secara  bersama  adalah  produk  dari  probabilitas  individu. Keuntungan penggunaan Naive Bayes adalah bahwa metode ini hanya membutuhkan jumlah data pelatihan (Training Data) yang kecil untuk menentukan estimasi paremeter yang diperlukan dalam proses pengklasifikasian.  Dalam  metode  Naive  Bayes data  String  yang  bersifat  konstan  dibedakan dengan data numerik yang  bersifat kontinyu, perbedaan ini akan terlihat pada saat menentukan nilai probabilitas setiap kriteria baik itu kriteria dengan nilai data string maupun kriteria dengan nilai data numerik. 

Maka dari itu, dengan menggunakan metode Naive Bayes pada proyek ini, diharapkan mampu melakukan deteksi emosi pada dataset secara tepat dan sesuai, sehingga tujuan utama dari proyek ini terpenuhi, yaitu dapat mengetahui melakukan identifikasi secara otomatis terhadap label emosi yang paling dominan dari kalimat yang terdapat pada dataset.

# Online Code - Google Colab use Guide

1. Pastikan sudah menyiapkan file dataset. Dapat diperoleh dari [sini](https://github.com/Kelompok-Achiera/Multi-Label-Emotion-Classification/tree/main/dataset/dummy_data%20raw) 
2. Buka [Link](https://colab.research.google.com/drive/1tP32K917Gua9BmL7BqB2ccO6l8I_BSg2?usp=sharing) Google Colab
3. Upload file dataset pada kolom upload file /content/sample-data/nama-file-dataset.csv

![googlecolab](https://user-images.githubusercontent.com/72435408/142966061-c52349c2-0e78-42d5-9f24-df7fc2c19e1b.PNG)

4. Jika tampilan folder sudah seperti gambar diatas, maka code program siap untuk dijalankan.
