# CFGAN
Implementation of CFGAN. The implementation based on Pytorch is done, and the max precision on ML100k is 0.49 in 1000 train epochs, when use the paramaters in the paper.

cfgan.py  :  the model of CFGAN

data.py   :  load data

main.py   :  train and show result


Run the demo : 

Python main.py

You can modify paramaters in main.py, for example, modify the alpha to 0.5(in fact, result turn better when you do that)


Next, we consider implementing another version based on Tensorflow.

Author:
    Xuxin Zhang, HUST, xuxinz@hust.edu.cn

Reference:
Chae D K , Kang J S , Kim S W , et al. CFGAN: A Generic Collaborative Filtering Framework based on Generative Adversarial Networks[C]// the 27th ACM International Conference. ACM, 2018.

Baseline:
https://github.com/1051003502/CFGAN

