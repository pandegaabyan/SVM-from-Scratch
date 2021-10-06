# Project AI - Breast Cancer Classification using SVM from Scratch
### Pandega Abyan Zumarsyah

Pada project ini, saya melakukan klasifikasi tipe Breast Cancer menggunakan SVM (Support Vector Machine). SVM dipilih karena sangat terkenal dan performanya cukup bagus. Selain itu, saya pribadi juga ingin belajar lebih terkait SVM ini. Sementara itu, data terkait Breast Cancer didapatkan dari kaggle dengan nama Breast Cancer Wisconsin. 

Datanya memiliki dua kelas yaitu Benign/jinak dan Malignant/ganas. Terdapat 30 fitur, di antaranya radius_mean, texture_mean, radius_worst, dan radius_se. Namun, di awal, perlu pengolahan untuk memilih fitur apa saja yang akan digunakan. Pemilihan itu berdasarkan pada nilai cross-correlation setiap fitur dengan yang lain. Setelah itu, datanya dipisah antara training dan testing. 

Kemudian, masuk ke tahap training. Pada training ini, persamaan dasar dari SVM dioptimasi menggunakan metode Stochastic Gradient Descent (SGD). SGD memang banyak digunakan untuk optimasi SVM. Dalam training SVM dengan SGD ini, parameter seperti learning rate dan regularization perlu diatur agar hasilnya maksimal. 

Dalam pengerjaannya, saya awalnya mempelajari dataset yang ada beserta fitur-fiturnya. Itu penting untuk menentukan fitur yang tepat. Kemudian, saya mempelajari SVM mulai dari konsep, jenis, sampai implementasinya dengan optimasi berbasis SGD. Meski saya juga mempelajari kode yang ada di referensi, kode di sini tidak hanya copy-paste dari referensi. Dari berbagai kode yang ada, saya melakukan penyederhanaan dan improvement. Bagian kode yang saya kembangkan sendiri juga banyak. Referensi saya di antaranya:
- Terkait Dataset: https://www.kaggle.com/priyanka841/breast-cancer-wisconsin
- Konsep SVM dengan SGD: https://svivek.com/teaching/lectures/slides/svm/svm-sgd.pdf
- Konsep SVM dengan SGD: https://towardsdatascience.com/solving-svm-stochastic-gradient-descent-and-hinge-loss-8e8b4dd91f5b
- Konsep SVM dan kode: https://medium.com/deep-math-machine-learning-ai/chapter-3-support-vector-machine-with-math-47d6193c82be
- Konsep SVM dan kode: https://medium.com/@saishruthi.tn/support-vector-machine-using-numpy-846f83f4183d
- Konsep SVM Soft Margin: https://youtu.be/IjSfa7Q8ngs
- Konsep SVM (Stanford Lecture): https://youtu.be/8xbnLHn4jjQ
