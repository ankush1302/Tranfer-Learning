# Tranfer-Learning

### predicting whether a question asked on Quora is sincere or not.
 * Used pretrained model from tensoflow hub (which return embedded vector form) and then added more layers to for final model.

### Embedded : 

![2021-08-11 01_06_49-TensorFlow Hub](https://user-images.githubusercontent.com/52347680/128924159-d22282d6-3abe-49f3-938a-ee642cea0c20.png)

### Used to different pretrained model and comapred the accuracy on train and test data:
Pretrained Model helps to minimize the preprocessing data steps like: data cleaning , tokenisation , removing stop words etc.

1. nnlm-en-dim128 : Maps from text to 128-dimensional embedding vectors.
2. universal-sentence-encoder : he output is a 512 dimensional vector. 


