# Submission 1: Spam SMS Detection
Nama:Andreas Natanael Bunyamin

Username dicoding:andreasnb12

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [*SMS Spam Collection Dataset*](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/data) |
| Masalah | SMS (*Short Message Service*) tetap menjadi salah satu metode komunikasi yang populer di seluruh dunia, terutama karena hampir setiap perangkat seluler dapat menerima dan mengirim SMS. Mengirim SMS secara massal dapat dilakukan dengan mudah dan murah, sehingga praktik spam SMS menjadi masalah yang signifikan. Pesan-pesan spam seringkali mengandung penipuan, iklan yang tidak diinginkan, atau bahkan mengandung *malware* yang berpotensi merusak. |
| Solusi machine learning |  Metode-metode tradisional dalam mengatasi spam SMS seperti pemblokiran atau *filtering* seringkali tidak cukup efektif karena *spammer* terus mencari cara untuk mengelabui filter tersebut. Untuk itu, diperlukan peran otomasi machine learning dalam menyaring pesan spam. Dengan menggunakan model machine learning, sistem dapat mempelajari pola-pola yang kompleks dan mengidentifikasi pesan-pesan yang kemungkinan besar adalah spam. |
| Metode pengolahan | Untuk mengolah dataset *SMS Spam Collection*, pertama-tama dilakukan *data cleaning* untuk *missing value* dan *duplicate data*, selanjutnya dilakukan *Label Encoding* untuk feature label agar data dapat diproses dengan baik oleh model.  |
| Arsitektur model | Model dibuat menggunakan layer TextVectorization, layer embedding, Bidirectional LSTM, 2 hidden layer dan 1 output layer.  |
| Metrik evaluasi | Metrik evaluasi yang digunakan pada model ialah BinaryAccuracy, TruePositive, FalsePositive, TrueNegative, FalseNegative sebagai evaluator model. |
| Performa model | Model menghasilkan BinaryAccuracy sebesar 98%, TruePositive 124, FalsePositive 2, TrueNegative 943, dan FalseNegative 15. Dapat dilihat bahwa model memiliki tingkat akurasi yang tinggi dalam kasus ini. |
