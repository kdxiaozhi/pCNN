# Per-Pixel CNN (PCNN) for high-resolution imagery classification
This project aims to classify high-resolution images by ultilizing deep convolutional neural networks. If you find this to be helpful, please cite our paper ["Spectral–spatial feature extraction for hyperspectral image classification: A dimension reduction and deep learning approach,IEEE Transactions on Geoscience and Remote Sensing 54 (8), 4544-4554"](http://ieeexplore.ieee.org/abstract/document/7450160/). Thanks!

## Step.1: Generate image patch-based traning dataset using "generate_dataset.m"
In this step, 10% of available samples were selected to train CNN models. 



## Step.2: Train a 5-layer CNN with "vai_train_rs_cnn.m"



## Step.3: Predict the whole map's labels with the well-trained CNN
