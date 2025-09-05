# BRANet
 BRANet: Lightweight bottleneck residual attention network for enhanced image denoising by Jibin Deng*, Ming Zhao* is submitted to Neural Networks, 2025.

**All codes will be published after the paper is accepted.**

# Prerequisites:
python

tensorflow

keras

opencv-python

scikit-image

# Denoising Training
For train the BRANet, please run:

python mainimprovement.py

# Denoising Testing

For test the BRANet, please run:

python mainimprovement.py --pretrain sigma (e.g., 15, 25, 35 and 50)/model_50.h5 --only_test True

# Denoising Datasets
The gray train dataset "Train400" you can download here (Selected in the paper):

https://www.dropbox.com/s/8j6b880m6ddxtee/TNRD-Codes.zip?dl=0&file_subpath=%2FTNRD-Codes%2FTrainingCodes4denoising%2FFoETrainingSets180

The color train dataset "BSD500" you can download here (Selected in the paper):

https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/resources.html

The real-world train dataset "PolyU" you can download here (Selected in the paper):

https://github.com/csjunxu/PolyU-Real-World-Noisy-Images-Dataset

The real-world test dataset "CC" you can download here (Selected in the paper):

https://github.com/csjunxu/MCWNNM_ICCV2017

The real-world test dataset "Nam" you can download here (Selected in the paper):

https://github.com/GuoShi28/CBDNet/tree/master/testsets/Nam_patches