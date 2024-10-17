# Fashion-MNIST-

**Problem**: It is a multi-class classification problem, and here classes 0 to 9 refer to it as a T-shirt or top, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots, respectively. The optimal categorization model will then be identified by comparing the outputs of the two models. 


**Solution Methods**: We used a neural network approach and a hybrid approach with the combination of CNN and Vision Transformer to solve this classification problem.
1. ANN and CNN are used to make predictions using the help of the Tensorflow Keras library. This is the first approach to approaching this problem. To get an overview of these two models we are sharing the flowchart of the models and also the classification report.

ANN model Flowchart:
![model_ann](https://github.com/user-attachments/assets/1e1676e0-f787-42bb-ae23-eb58933f4782)

CNN model Flowchart:
![cnn_model_plot](https://github.com/user-attachments/assets/9b87e38d-59bb-4410-b9bf-e0761a7e4db0)

2. We also explored a hybrid model Compact Convolutional Transformer, in which we implemented a combination of CNN and Vision Transformer to get more precise classification. In this case we used Pytorch framework and the model flowchart is given below.
![model gv](https://github.com/user-attachments/assets/3b4033ba-9f6e-4560-bde4-0a51fc1000da)
