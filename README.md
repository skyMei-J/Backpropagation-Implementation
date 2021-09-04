# Backpropagation-Implementation (No Packages except for Numpy and other python standard library)

Implementation of a two hidden-layer neural network
- Two inputs(x,y)
- One output(label). If x>y, label = 0. If x<y, label = 1

In this example, I write a backpropagation program to separate y = x data, which has 100 points.

## Network Design (handcrafted)
![image](https://github.com/skyMei-J/Image/blob/main/backpropagation/截圖%202021-09-04%20下午5.53.53.png)
## Prediction and Groudtruth
![image](https://github.com/skyMei-J/Image/blob/main/backpropagation/截圖%202021-09-04%20下午5.54.21.png)
## Accuracy and loss
![image](https://github.com/skyMei-J/Image/blob/main/backpropagation/截圖%202021-09-04%20下午5.54.30.png)


## Derivation of Softmax's Corss entropy is softmax(x) – goundtruth
![image](https://github.com/skyMei-J/Image/blob/main/backpropagation/截圖%202021-09-04%20下午6.01.13.png)
## How to prevent Overflow of Softmax
Change log function log(a/b) to log a - log b to prevent log(0)




