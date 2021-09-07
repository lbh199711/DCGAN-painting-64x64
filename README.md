# DCGAN-painting-64x64

Tensorflow implementation of Deep Convolutional Generative Adversarial Network (DCGAN) using custom data found in Kaggle. The training data consists of 5000 impressionist landscape paintings in 1024x1024 RGB format. <br>
The goal of this project is to generate 'fake' paintings. The generated paintings should look somewhat like the real ones inputed, yet be diverse and not look EXACTLY like the inputed ones. <br>
In this project, the images are resized to 64x64 RGB format to make the learning process easier. There may be a future project targeting 128x128 sized images. 

### Original images:
![DCGAN__main](https://user-images.githubusercontent.com/31713252/129493865-beda77b6-53fd-4120-a829-2f8e9f75c8bd.jpg)

### After processing input images:
![DCGAN__input](https://user-images.githubusercontent.com/31713252/132143941-8871fbe8-1e1c-4ff2-a885-18febfd428de.png)


### Output images from the generator ~2000 epochs:
![DCGAN_end_product](https://user-images.githubusercontent.com/31713252/129493893-40d42d59-a6f3-44c1-93ce-8427448d6c7c.png)

### Notes:
> *DCGAN v3_64.ipynb* currently produce the best performing model. <br>
> *v3_gen_2* is the tensorflow model produced by *DCGAN v3_64.ipynb* at around 2000 epochs.

