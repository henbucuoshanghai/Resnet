# Resnet

Based on the lenet5 Network,I add a resnet layer between the first conv-layer and the second conv-layer,and still train it on mnist data.  
But the acc is not very good.

  
one with data expand,batch size 100,40000steps      acc on test data is 94.68%  
second with data expand,batch size 500,8000steps      acc on test data is 94.68%  
third,four,five with no data expand,batch size 500,  but 4000,10000,20000 steps,acc on test data is 97.79%,98.17%,98.34%
