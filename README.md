# Praktikum Mata Kuliah Natural Language Processing
Ini adalah bahan untuk praktikum mata kuliah pilihan NLP tentang speech recognition.

## Daftar isi
- Dasar-dasar pengolahan sinyal
- Sinyal gabungan
- Sinyal suara dan wicara
- Transformation Fourier
- Short Time Fourier Transform (STFT)
- Mel Frequency Cepstral Coefficient (MFCC)
- Multilayer Perceptron

## Persiapan
- Install jupyter-notebook. Bisa menggunakan anaconda atau melalui pip install jupyter
- Install library yang dibutuhkan
- Download data audio yang disediakan

## Data
Folder data disiapkan, tetapi datanya disimpan di tempat terpisah. Download sesuai dengan petunjuk pada slide praktikum!

## Library yang dibutuhkan
- numpy
- matplotlib
- sounddevice
- scipy
- pandas
- sklearn
- tensorflow

## Note
- Jika modul tensorflow tidak bisa diinstall, upgrade pythonnya ke python 3.8
- Jika modul tensorflownya tidak bisa dipanggil waktu menyusun Multi Layer Perceptronnya, ganti kode 

        import tensorflow as tf
    dengan 

        import tensorflow.compat.v1 as tf
        tf.disable_v2_behavior() 

Heavily adopted from https://github.com/linerocks/mlid6/blob/master/Signal%20Processing%20Crash%20Course.ipynb
