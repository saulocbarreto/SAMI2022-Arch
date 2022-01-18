# SAMI2022-Arch
The architecture for section III.A of the paper Training and Analysis of Hyperparameters in Neural Networks for Computer Vision Applications: A Didactic Approach

| Layer (type) | Output Shape | Number of Parameters |
| :---:         |     :---:      |          :---: |
| conv2d (Conv2D) | 30 x 30 x 32 | 896 |
| max_pooling (MaxPooling2D) | 15 x 15 x 32 | 0 |
| conv2d_1 (Conv2D) | 13 x 13 x 64 | 18496 |
| max_pooling2d_1 | 6 x 6 x 64 | 0 |
| conv2d_2 (Conv2D) | 4 x 4 x 64 | 896 |
| flatten (Flatten) | 1024 | 0 |
| dense (Dense) | 64 | 65600 |
| dense_1 (Dense) | 10 | 650 |
