# Generate Faces using attributes using Conditional DCGAN

This model uses a DCGAN architecture combined with attributes input to generate faces trained on the Celeb_A dataset.

### Generator Architecture
 
<img src="https://user-images.githubusercontent.com/56511544/119218454-a2b2ce80-bae0-11eb-8780-7c37a0220995.png" alt="generator" width="400"/>  
<font size="2"> Image source: reproduced from Radford et al. (2015) </font>

### Discriminator Architecture

<img src="https://user-images.githubusercontent.com/56511544/119218481-ca099b80-bae0-11eb-9b2d-c07a2b693ba0.png" alt="discriminator" width="400"/>  
<font size="2"> Image source: Tracey Etheridge </font>

### Generated Images

Here the addition of noise to generate variety in facial feature is held constant and the attribute input changed. A clear distinction in attributes can be seen. Note: This is a minmal example to show differences. With more attributes, better quality faces are produced.

![image](https://user-images.githubusercontent.com/56511544/119218643-b7dc2d00-bae1-11eb-9d30-783b008dc892.png)

The below matrix of images shows examples where the attributes have been held constant and the noise parameter changed for each image. While images are still very similar, they are clearly different.

Attributes: Male, Eyeglasses, Young, Brown Hair, Smiling, Oval Face

<img src="https://user-images.githubusercontent.com/56511544/119218690-f671e780-bae1-11eb-8859-ef119b183f2f.png" alt="faces_noise" width="400"/> 


