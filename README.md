# Signature-Forgery-Detection
# About
Authenticating is a tedious process that requires us to be meticulous with no point of failure. We find this to be unrealistic because as humans, it’s in our nature to make mistakes, but computers don’t. Identifying a signature whether it is fraudulent or not is a critical task in many fields, including banking, legal, and forensic applications. Hence, it is vital for us to look into this problem and come up with solutions to tackle this problem.
# Problem Formulation
- What is the probability of a signature image that is real or forged.
# Setting up
Download the required package/libraries by running 
`pip install -r requirements.txt`
# Dataset
Obtained from Kaggle. [link](https://www.kaggle.com/datasets/robinreni/signature-verification-dataset)
# Model Used
- Logistic Regression from sklearn
- Convolutional Neural Network (CNN)
# Conclusion
- MSE & SSIM are simple tools which can be used to identify differences in the images
- Logistic regression can be used to do binary classification, similar to our project
- Logistic regression is very sensitive to outliers
- CNN is a great model for image classification
- A skilled forger might be able to bypass MSE, SSIM and logistic regression but not CNN
# Recommendation
- Include more dataset
# What we learnt
- What is CNN and its applications.
- How to use CNN
- Structural Similarity Index Measure(SSIM)
- MSE of images
- Logistics Regression
- Ways to plot graphs
- Ways to pre-process an image dataset 
# Contributors
- Kenneth
- Yee Jian
- Huai Zhi
# References
- https://github.com/Harshitb1/AxisBankAiChallenge
- https://www.kaggle.com/datasets/robinreni/signature-verification-dataset
- https://medium.com/swlh/signet-detecting-signature-similarity-using-machine-learning-deep-learning-is-this-the-end-of-1a6bdc76b04b
- https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2021/06/image-classification-using-convolutional-neural-network-with-python/&sa=D&source=docs&ust=1681562028887982&usg=AOvVaw0EYUYTQ7lXfKma_3KmtH-U
- https://www.analyticsvidhya.com/blog/2021/06/image-classification-using-convolutional-neural-network-with-python/
- https://www.channelnewsasia.com/singapore/man-forge-documents-nus-degree-get-jobs-38-companies-890881
- https://seaborn.pydata.org/
- https://www.tensorflow.org/