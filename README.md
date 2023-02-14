# Covid and Pneumonia Image Classification 

For this project, I use the dataset from Chowdhury et al., which contains 3886 images and indicates whether each image is COVID-19, viral pneumonia, or normal. This dataset precisely contains 1200 Covid images, 1345 viral pneumonia images, and 1341 regular images. This dataset is meaningful because the images can build machine learning models to accurately predict which images are COVID-19 without having to use expensive equipment or involve medical practitioners to diagnose people with COVID-19. Thus, clinics and medical programs that use the traditional RT-PCR method of diagnosis can benefit from this dataset by using this as an alternative diagnosis method, as this is less costly and the information is more accessible.

Based on my results, the first model had the highest accuracy score at 96.8, followed by the VGG-16 model at 94.34% accuracy, and finally the MLP model with 93.83% accuracy coming in last. Overall, I found that the most important hyperparameters for changing the scores were: The number of layers, epochs, learning rate of the optimizer, pooling type, and relu activation function type. What had increaased the scores the most was increasing epochs to around 20, decreasing the number of pooling and Conv2d layers, setting the learning rate to 0.001, setting the pooling layer to max pooling, and using the default Relu (over leaky ReLu or parametric).

References:

M.E.H. Chowdhury, T. Rahman, A. Khandakar, R. Mazhar, M.A. Kadir, Z.B. Mahbub, K.R. Islam, M.S. Khan, A. Iqbal, N. Al-Emadi, M.B.I. Reaz, “Can AI help in screening Viral and COVID-19 pneumonia?” arXiv preprint, 29 March 2020, https://arxiv.org/abs/2003.13145
