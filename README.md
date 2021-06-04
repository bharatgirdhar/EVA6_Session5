# EVA6_Session5
## Problem Statement - Hit 99.4 Accuracy more than once in 15 EPOCS or Less with less than 10k parameters using MNIST dataset.

## Basic Skeleton with Batch Normalization, Regularization and Global Average Pooling

<a href="https://github.com/bharatgirdhar/EVA6_Session5/blob/main/EVA6_Session_5_Assigment_99_4.ipynb" target="_blank">Code - 1</a>

### Results
1. Parameter : <10k
2. Best Train Accuracy:99.05
3. Best Test Accuracy: 99.40

### Analysis
1. Lighter Model Working
2. NOT able to push further without implementing other techniques
3. our LR is fixed

## Playing with LR
<a href="https://github.com/bharatgirdhar/EVA6_Session5/blob/main/EVA6_Session_5_Assigment_99_43.ipynb" target="_blank">Code - 2</a>

### Results
1. Parameter : <10k
2. Best Train Accuracy:99.09
3. Best Test Accuracy: 99.43 (2 times in last 4 EPOCS)

### Analysis
1. Changing LR helping it to keep 99.4> formore than 1 EPOC.
2. Finding a good LR schedule is hard. We have tried to make it effective by reducing LR by 20th after the 10th epoch.

## Playing with Image Augmentation
<a href="https://github.com/bharatgirdhar/EVA6_Session5/blob/main/EVA6_Session_5_Assigment_99_41.ipynb" target="_blank">Code - 3</a>

### Results
1. Parameter : <10k
2. Best Train Accuracy:98.88
3. Best Test Accuracy: 99.41

### Analysis
1. Adding Image Augmentation is making the training harder.
2. Algo was able to hit 99.41 once in 15 EPOCS but considering the fact that it is underfitting,more EPOCS will improve the results.


