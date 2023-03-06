# cpsc482codingassignment
fine-tuning two pre-trained models on sample of HPA single cell dataset 

attached jupyter notebook contains end-to-end process of data loading, processing, image augmentation, model training and fine-tuning. each section is labeled accordingly, and the bottom part (DINO pre-training) is the code that I was unable to get working. 

code for data pre-processing and image augmentation inspired by the following approaches: https://www.kaggle.com/code/ligtfeather/bottleneck-transformers-for-visual-recognition/notebook and https://www.kaggle.com/code/thedrcat/hpa-single-cell-classification-eda

if downloading code for usage, you will need to download the sample data for training and testing from here: 
https://www.kaggle.com/datasets/thedrcat/hpa-cell-tiles-sample-balanced-dataset (training)
https://www.kaggle.com/datasets/thedrcat/hpa-cell-tiles-test-with-enc-dataset (testing)

replacing path names as appropriate should be the only changes necessary to reproduce my code on a local system. 
