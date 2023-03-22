# Monet Style Transfer

### [Source](https://www.kaggle.com/competitions/gan-getting-started) | [Project](https://www.kaggle.com/code/chongzhenjie/monet-style-transfer-cyclegan-pytorch-lightning)

### Description: Use GANs to generate Monet-style images.

* Applied image augmentation to dataset consisting of photos and Monet paintings, and implemented CycleGAN in PyTorch Lightning to perform photo-to-Monet translation.
* Built CycleGAN using generators with the U-Net architecture, and PatchGAN discriminators. 

### Model Results.

The below images show the results of adding the Monet style to photos at different points of training. The original photos are placed above the transformed photos for comparison. It can be seen that the model learnt the geometric elements of the photos at the first epoch, and the colors of the photos at epoch 30. The final results at epoch 180 are displayed in the last image.

![epoch1](https://user-images.githubusercontent.com/77932796/226842135-5e5bca8b-5876-4286-a757-8e9a1bc87093.png)
![epoch30](https://user-images.githubusercontent.com/77932796/226842403-36792c39-2955-41ad-a7e4-015815317dd2.png)
![epoch180](https://user-images.githubusercontent.com/77932796/226842158-dd469fbc-1812-4892-8be0-02e34d50eb53.png)
