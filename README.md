# Cell Classification with Convolutional Neural Networks (CNN)

## Dataset
The dataset contains 60,000 microscopic images of cells. It is split into training and testing sets for model training and evaluation, respectively.

![cell1](c_img/c_1.png)
![cell2](c_img/c_2.png)
![cell3](c_img/c_3.png)

## CNN Architecture
The CNN architecture used for cell classification consists of the following layers:
- Two convolutional layers with ReLU activation.
- Pooling layers for downsampling.
- Fully connected layers for classification.

![arch](https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.researchgate.net%2Fpublication%2F329414219%2Ffigure%2Ffig4%2FAS%3A700320464269316%401543980818372%2FOur-proposed-CNN-architecture-with-two-convolution-and-two-fully-connected-layers.ppm&tbnid=OP6rvRvK8X949M&vet=12ahUKEwjGrsrDpvSEAxXOi2MGHVGaAGgQMygAegQIARBS..i&imgrefurl=https%3A%2F%2Fwww.researchgate.net%2Ffigure%2FOur-proposed-CNN-architecture-with-two-convolution-and-two-fully-connected-layers_fig4_329414219&docid=-oB-LtWdMZNhoM&w=850&h=547&q=CNN%20architecture%20with%202%20convolution&ved=2ahUKEwjGrsrDpvSEAxXOi2MGHVGaAGgQMygAegQIARBS)

## Evaluation
The model's performance is evaluated based on the F1 score, which is a harmonic mean of precision and recall. The F1 score provides a balanced measure of the model's accuracy, particularly useful for imbalanced datasets.


