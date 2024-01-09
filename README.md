# 2024 - Image-to-Image Texture Synthesis with Diffusion Model

## General idea
This is a conditional model that learns to generate and complete new textures from smaller or cropped ones.

![title](./images/groundtruth_condition.jpg)
![title](./images/groundtruth.jpg)

## Training results
The model was trained on different textures belonging both to different and same classes. The classes chosen are tatami, bricks and bark.
One experiment of the project was the implementation of EMA model.

### Real textures
![title](./images/test_real_1.jpg)
![title](./images/test_real_2.jpg)
![title](./images/test_real_3.jpg)


### Conditioning textures
![title](./images/test_conditioner_1.jpg)
![title](./images/test_conditioner_2.jpg)
![title](./images/test_conditioner_3.jpg)


### Model 
![title](./images/test_1.jpg)
![title](./images/test_2.jpg)
![title](./images/test_3.jpg)


### EMA model 
![title](./images/test_ema_1.jpg)
![title](./images/test_ema_2.jpg)
![title](./images/test_ema_3.jpg)
