# Abstract Art GAN - 256x256
![image info](./preview/8973432.png)
![image info](./preview/8973498.png)
![image info](./preview/8973600.png)

![image info](./preview/8973446.png)
![image info](./preview/8973522.png)
![image info](./preview/8975286.png)

![image info](./preview/8973458.png)
![image info](./preview/8973584.png)
![image info](./preview/8975428.png)

This is a generative adversarial neural network I trained to generate photos of abstract art at 256x256 resolution. Preview photos are 
available along with the log data from the training process. StyleGAN2-ada-pytorch was used to train on my own custom 
abstract art data set. I used a script that uses Flickr's API to crawl through the image database and download photos that 
match a specified keyword (in this case the keyword was 'art'). The image set that I collected will be linked below. 
Videos that I have created using the trained network are below. The 
.pkl file for this network is also included below in case anyone is interested in generating their own photos of 
abstract art.

Links:

* [Progression video of the training process on this data set](https://youtu.be/Veh3uNC8VI8)
* [Latent vector walk video #1](https://youtu.be/Gzfzxq-ZHTo)
* [Download link to my own custom art dataset used for training](https://github.com/dudebroSW/pretrained-gan-abstract-art-256/releases/download/v1.0/abstract-art-img-set-256.zip)
* [Download link to the abstract art .pkl file](https://github.com/dudebroSW/pretrained-gan-abstract-art-256/releases/download/v1.0/abstract-art-256-trained.pkl)
