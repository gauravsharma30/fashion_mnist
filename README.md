# fashion_mnist
## Fashion MNIST Classification with ANN

## Project Overview
This project explores the classification of Fashion MNIST using a neural network with 4 hidden layers and performs an ablation study to analyze the impact of varying layers and neurons.



### Baseline Model (4 Hidden Layers)
- **Test Accuracy**: 0.8881
- **Sample Predictions**: TensorBoard logs/screenshots

### Ablation Study
| Model Variant                 | Test Accuracy     |
|-------------------------------|-------------------|
| 4 Hidden Layers               | 0.8841            |
| 3 Hidden Layers               | 0.8870            |
| 5 Hidden Layers               | 0.8855            |
| Fewer Neurons per Layer       | 0.8672            |
| More Neurons per Layer        | 0.8853            |
| 3 Hidden Layers & more neurons| 0.8876            |


## Results 

### Model with 4 layers
![image](https://github.com/user-attachments/assets/7d744ddf-1129-4ccd-bdc4-6b85e9a5c131)

### Model with 3 layers
![image](https://github.com/user-attachments/assets/6c036ed4-d1f5-4a9d-8241-15a6f3638011)

### Model with 5 layers
![image](https://github.com/user-attachments/assets/e3704c5f-16d2-421a-8a81-bace5929bfaa)

### Model with fewer neurons layers
![image](https://github.com/user-attachments/assets/d51e4128-7e06-445a-80d4-fe2eb65c8f48)

### Model with more neurons layers
![image](https://github.com/user-attachments/assets/c3dbb03a-3c4a-4226-bef8-e60fd530571b)

### Model with 3 layers and more neurons
![image](https://github.com/user-attachments/assets/9150ad12-6ff4-421f-b073-1c5d883fd3da)

