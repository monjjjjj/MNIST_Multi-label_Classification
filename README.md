# MNIST_Multi-label_Classification
## 架構比較
### for multi-class classification 
Model的最後一層要使用softmax function來做類別的預測，loss function要使用categorical_crossentropy。
### for multi-label classification
Model的最後一層要使用sigmoid function來做標籤的預測，loss function要使用binary_crossentropy。



