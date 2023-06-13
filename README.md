# image-compression-pca
Compression and Reconstruction of Colour Image Using Principal Component Analysis PCA

# Introduction

Principal Component Analysis (PCA) is a statistical procedure used to reduce the number of features within a dataset. This is often useful if you have a lot of variables within your data that are correlated, or if you need to reduce the size of your dataset. Here, I use PCA to reduce the size of an image.

## How PCA Works

Principal Component Analysis finds the linear combinations of variables that explain the most variation within the data and and have the lowest reconstruction error. There are multiple principal components and each principal component explains some percentage of the variation within the data. The first principal component always explains the most variation, followed by the second, etc. Generally, you can greatly reduce the size of your data, while still retaining most of its information, by using enough principal components to explain 99% of the variation in your data.

## Conclusion
Using first 100 Principal Components, a good image can be recontructed.
