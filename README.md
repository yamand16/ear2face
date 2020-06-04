# Ear2Face: Deep Biometric Modality Mapping

This is the GitHub repository of our preliminary work on deep biometric modality mapping. Since DNA is crucial factor in the appearance of our biometric modalities such as face and ear, there is an implicit relationship between them. In this work, our aim is to investigate the relationship between ear and face using only visual data. Since the used datasets are small and has low variance, there is obviously "dataset fit" problem. However, although there is a kind of dataset bias problem, the results are still promising because the relationship between ear and face can learn via generative models even if for a specific dataset.

The other interesting point is that the model can generate glasses and/or emotions. However, these things are not reconstructed correctly for all images. Probably, one of the main reason is low variance in dataset. Therefore, the GAN model learns several certain variances to generate the data.

Note: The reconstructed face images in Fig. 1 is not reconstructed version of input ear. The input and output images in Fig. 1 are selected randomly in order to basically represent just process. However, the images in Fig. 4 are generated by our model using test data. As mentioned in the paper, the subjects in the subject dependent test set 1 and 2 exist in train data. However the images are not same. There are more than one images for each person. However, the subjects in the subject independent test set do not exist in train set. So, the model has not seen them.

Note 2: We will upload more reconstructed examples.

Note 3: The codes, weights and related information for train & test data will be provided soon.
