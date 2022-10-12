# MNIST_Multi-label_Classification
## Result
我做出來的結果：  
<img width="252" alt="截圖 2022-10-12 下午8 08 40" src="https://user-images.githubusercontent.com/62006029/195338845-d2246468-52d2-4ecd-acf4-ea66ed9c758e.png">  
與作者做出來的結果相差甚遠，作者做出來結果準確率可達99%！  
但將作者的code拿來重新跑一次，根本無法做出一樣的結果！  
作者做出來的結果：  
<img width="273" alt="截圖 2022-10-12 下午8 12 24" src="https://user-images.githubusercontent.com/62006029/195339506-aaf87e25-0b54-4992-a197-ae2739887af6.png">  
增加模型的複雜度、增加訓練次數，都無法改善準確度！

## 架構比較
### for multi-class classification 
Model的最後一層要使用softmax function來做類別的預測，loss function要使用categorical_crossentropy。
### for multi-label classification
Model的最後一層要使用sigmoid function來做標籤的預測，loss function要使用binary_crossentropy。



