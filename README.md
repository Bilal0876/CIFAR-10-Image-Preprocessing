# IDL-A2-L1S22BSCS0213
Deep learning image preprocessing techniques demonstrated on CIFAR-10 dataset
# CIFAR-10 Image Preprocessing Techniques

This project demonstrates 5 essential image preprocessing techniques used in deep learning, applied to the CIFAR-10 dataset.

Preprocessing Techniques

1. Normalization - Scales pixel values to [0, 1] range
2. Contrast Enhancement (CLAHE) - Adaptive histogram equalization
3. Noise Reduction - Gaussian blur for smoothing
4. Sharpening - Edge enhancement using convolution
5. Grayscale Conversion** - RGB to single-channel transformation

Dataset:
CIFAR-10- 60,000 32×32 color images in 10 classes

CIFAR-10 on Kaggle: https://www.kaggle.com/c/cifar-10/data

Dataset Setup
1. Download CIFAR-10 from the link above
2. Extract to `data/` folder
3. Ensure structure:
```
   data/
   ├── train/
   │   ├── 1.png
   │   ├── 2.png
   │   └── ...
   └── trainLabels.csv
   |___test/
       |_1.png
       |_2.png
