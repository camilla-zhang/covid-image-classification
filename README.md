# Covid and Pneumonia Image Classification 

This project was submitted to the **COVID Image Classification Hackathon** competition for my Advanced Projects in Machine Learning course. I use image data from Chowdhury et. al (2020) to detect when lungs X-rays show covid postivity, viral pneumonia, or healthy lungs. I then run at three hyper-tuned prediction models to try to predict the image classification - (1) VGG 16, (2) CNN, and (3) MLP. Finally, I discuss which models performed better and point out relevant hyper-parameter values for successful models.

Based on my results, the first model had the highest accuracy score at 96.8, followed by the VGG-16 model at 94.34% accuracy, and finally the MLP model with 93.83% accuracy coming in last. Overall, I found that the most important hyperparameters for changing the scores were: The number of layers, epochs, learning rate of the optimizer, pooling type, and relu activation function type. What had increaased the scores the most was increasing epochs to around 20, decreasing the number of pooling and Conv2d layers, setting the learning rate to 0.001, setting the pooling layer to max pooling, and using the default Relu (over leaky ReLu or parametric).

References:

M.E.H. Chowdhury, T. Rahman, A. Khandakar, R. Mazhar, M.A. Kadir, Z.B. Mahbub, K.R. Islam, M.S. Khan, A. Iqbal, N. Al-Emadi, M.B.I. Reaz, “Can AI help in screening Viral and COVID-19 pneumonia?” arXiv preprint, 29 March 2020, https://arxiv.org/abs/2003.13145
