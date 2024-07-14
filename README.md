# Breast Cancer Classification using SVM from Scratch

The Breast Cancer data was sourced from Kaggle under the name Breast Cancer Wisconsin. The dataset consists of two classes: Benign and Malignant. It includes 30 features such as radius_mean, texture_mean, radius_worst, and radius_se. Initially, feature selection was performed based on the cross-correlation values between each feature. Subsequently, the data was split into training and testing sets.

Moving to the training phase, the basic SVM equation was optimized using Stochastic Gradient Descent (SGD). SGD is commonly used for SVM optimization. Parameters such as learning rate and regularization were fine-tuned to achieve optimal results in SVM training with SGD.

References:
- Dataset: https://www.kaggle.com/priyanka841/breast-cancer-wisconsin
- SVM with SGD: https://svivek.com/teaching/lectures/slides/svm/svm-sgd.pdf
- SVM with SGD: https://towardsdatascience.com/solving-svm-stochastic-gradient-descent-and-hinge-loss-8e8b4dd91f5b
- SVM and code: https://medium.com/deep-math-machine-learning-ai/chapter-3-support-vector-machine-with-math-47d6193c82be
- SVM and code: https://medium.com/@saishruthi.tn/support-vector-machine-using-numpy-846f83f4183d
- SVM Soft Margin: https://youtu.be/IjSfa7Q8ngs
- SVM (Stanford Lecture): https://youtu.be/8xbnLHn4jjQ
