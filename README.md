# GAN_Practice
**GAN image generation**
Based on UAL CCI Coding 3: Exploring to Machine Intelligence week 5 notes https://git.arts.ac.uk/rfiebrink/ExploringMachineIntelligence_Spring2023/blob/main/week5/dcgan.ipynb.  

I modified the discriminator model to be compatible with images of shape (123, 56, 56, 3). The number of EPOCHS is 930 (got errors when trying with 5000). More layers were added to the generator. At the beginning, the output images were grey and unclear. Colours and shapes began to appear after a few iterations. The results showed shapes of donut.  

![Image text](https://github.com/RebeccaSY/GAN_Practice/blob/main/Images/predict_image_epoch_0930.png)  
![Image text](https://github.com/RebeccaSY/GAN_Practice/blob/main/Images/predict_image_epoch_0890.png)  
![Image text](https://github.com/RebeccaSY/GAN_Practice/blob/main/Images/predict_image_epoch_0870.png)  
