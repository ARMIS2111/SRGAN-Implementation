# Super-Resolution-of-Images
The need for superresolution of images arises from the fact that in many applications, such as medical imaging, surveillance, and remote sensing, it is 
often necessary to obtain high-resolution images with more details and clarity than the original images. However, acquiring high-resolution images can be 
difficult, expensive, or impractical due to various reasons such as hardware limitations, storage constraints, or limitations in data transmission.

Superresolution techniques can be used to generate high-resolution images from low-resolution images by estimating the missing high-frequency information. 
This can improve the quality and usefulness of the images in various applications.

This project aims to enhance the quality of one single image at a time.

The networks are trained using images in the flickr30k dataset for its training.


Brief introduction of GANS:-
GAN (Generative adverserial Networks) are an approach to generative modeling using deep learning methods, such as convolutional neural networks. Generative modeling is an unsupervised learning task in machine learning that involves automatically discovering and learning the regularities or patterns in input data in such a way that the model can be used to generate or output new examples that plausibly could have been drawn from the original dataset.

In this modelling approach, two Networks : the Generator and the Discriminator work against each other to achieve high accuracy of the generator. The generator tries to generate fake images that cannot be differentiated from the real images by the discriminator. 

Architecture of Generator Network:-
![image](https://user-images.githubusercontent.com/101886753/231661610-a1c8c1a2-3cb4-4d5e-b3fb-1003a1d1c2d1.png)


Architecture of Discriminator Network:-
![image](https://user-images.githubusercontent.com/101886753/231661669-00018cdf-4389-497c-a870-e110870bee95.png)


HOW TO RECREATE:-
  Folder Structure:-
      MAIN 
      |
      |
      |
      -----> Low Resolution Images Folder
      |
      |
      |
      -----> High Resolution Images Folder
      
  Steps:-
  i) Download the Code File.
  ii) Change the no of Epochs according to your requirements.
  iii) Let the model train itself. // This will take time depending upon your GPU and no of epochs used
  iv) Get the result.
