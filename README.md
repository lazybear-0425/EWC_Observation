# EWC_Observation (MNIST)
## Single Layer
### w/o Modification
#### 2 Epoch 
 - 2025-03-23_13_41_26 (Task 0 Acc:  0.3657, Task 1 Acc:  0.8906, ACC: 0.6282, BWT: -0.5400)
#### 10 Epoch
 - 2025-03-23_14_16_42 (Task 0 Acc:  0.2269, Task 1 Acc:  0.9214, ACC: 0.5741, BWT: -0.6969)
### Lambda = 1
#### 2 Epoch
 - 2025-03-23_11_25_55 (Task 0 Acc:  0.6191, Task 1 Acc:  0.8144, ACC: 0.7168, BWT: -0.2866)
#### 10 Epoch
##### Adam
 - 2025-03-23_14_56_03 (Task 0 Acc:  0.4133, Task 1 Acc:  0.8869, ACC: 0.6686, BWT: -0.5105)
##### SGD
 - 2025-03-24_21_40_02 (Task 0 Acc:  0.7713, Task 1 Acc:  0.5323, ACC: 0.6518, BWT: -0.0474)
#### 10 Epoch + 2 Epoch
 - 2025-03-25_07_49_12 (Task 0 Acc:  0.5771, Task 1 Acc:  0.8176, ACC: 0.6974, BWT: -0.3467)

### Lambda = 10
#### 2 Epoch
 - 2025-03-23_11_04_54 (Task 0 Acc:  0.7825, Task 1 Acc:  0.6569, ACC: 0.7197, BWT: -0.1232)
#### 10 Epoch
##### Adam
 - 2025-03-23_19_30_50 (Task 0 Acc:  0.6806, Task 1 Acc:  0.7784, ACC: 0.7295, BWT: -0.2432)
##### SGD
 - 2025-03-24_21_09_06 (Task 0 Acc:  0.8053, Task 1 Acc:  0.3056, ACC: 0.5555, BWT: -0.0134)
##### SGD(model.parameters(), lr=0.01, momentum=0.9)
 - 2025-03-24_20_49_06 (Task 0 Acc:  0.6201, Task 1 Acc:  0.8044, ACC: 0.7123, BWT: -0.2969)
#### 10 Epoch + 2 Epoch
 - 2025-03-25_07_55_37 (Task 0 Acc:  0.7615, Task 1 Acc:  0.6944, ACC: 0.7280, BWT: -0.1623)
### Lambda = 25
#### 2 Epoch
 - 2025-03-23_10_51_39 (Task 0 Acc:  0.8234, Task 1 Acc:  0.5737, ACC: 0.6986, BWT: -0.0823)
#### 10 Epoch
##### Adam
 - 2025-03-23_21_41_19 (Task 0 Acc:  0.7795, Task 1 Acc:  0.7034, ACC: 0.7415, BWT: -0.1443)
##### SGD
 - 2025-03-23_23_03_30 (Task 0 Acc:  0.8125, Task 1 Acc:  0.2420, ACC: 0.5273, BWT: -0.0062)
##### SGD(model.parameters(), lr=0.01, momentum=0.9)
 - 2025-03-24_20_03_31 (Task 0 Acc:  0.7472, Task 1 Acc:  0.7215, ACC: 0.7344, BWT: -0.1698)
## Two Layer
### Lambda = 10
#### 10 Epoch
##### Adam
 - 2025-03-25_13_36_30 
### Lambda = 25
#### 10 Epoch
##### Adam
 - 2025-03-25_12_53_07 
## CNN + GAP
### Lambda = 1
#### 10 Epoch
##### Adam
 - 2025-03-25_19_11_49 
### Lambda = 10
#### 10 Epoch
##### Adam
 - 2025-03-25_18_36_15 
## two CNN
### Lambda = 10
#### 10 Epoch
##### Adam
 - 2025-03-25_21_34_11 
### Lambda = 15
#### 10 Epoch
##### Adam
 - 2025-03-25_22_02_04 
### Lambda = 20
#### 10 Epoch
##### Adam
 - 2025-03-25_22_28_07 
### Lambda = 25
#### 10 Epoch
##### Adam
 - 2025-03-25_21_51_15 

# EWC (MNIST 取樣)
## Single Layer
### Lambda = 1
#### 10 Epoch
##### Adam
###### 20 %
 - 2025-03-25_10_19_05 (Task 0 Acc:  0.2844, Task 1 Acc:  0.9170, ACC: 0.6007, BWT: -0.6394)
###### 80 %
 - 2025-03-25_10_55_38 
### Lambda = 10
#### 10 Epoch
##### Adam
###### 5 %
 - 2025-03-26_00_34_22  
 - 2025-03-26_01_28_08 
     - 有固定座標軸為了報告
###### 20 %
 - 2025-03-25_11_27_13  
###### 40 %
 - 2025-03-26_00_15_40  
###### 50 %
 - 2025-03-25_23_48_20  
###### 60 %
 - 2025-03-25_23_30_22  
###### 70 %
 - 2025-03-25_23_13_13  
###### 80 %
 - 2025-03-25_11_12_58  
###### 100 %
 - 2025-03-26_02_24_40 
     - 有固定座標軸為了報告
### Lambda = 25
#### 10 Epoch
##### Adam
###### 20 %
 - 2025-03-25_12_03_36 
###### 80 %
 - 2025-03-25_12_36_27 

# EWC (fisher數量)
## Single Layer
### Lambda = 1
#### Adam
##### threshold = 0.5
 - 2025-03-25_23_04_47
### Lambda = 10
#### Adam
##### threshold = 0.2(去掉20%不要的)
 - 2025-03-26_00_11_34  
##### threshold = 0.3
 - 2025-03-26_02_15_24  
##### threshold = 0.4
 - 2025-03-26_01_54_15  
##### threshold = 0.5
 - 2025-03-25_23_27_22  
##### threshold = 0.6
 - 2025-03-26_00_39_58  
##### threshold = 0.7
 - 2025-03-26_01_28_13  
##### threshold = 0.8
 - 2025-03-26_00_23_08  


# EWC (Fashion MNIST)
## Single Layer
### Lambda = 25
#### 10 Epoch
##### Adam
 - 2025-03-24_20_22_19 (Task 0 Acc:  0.4950, Task 1 Acc:  0.7237, ACC: 0.6094, BWT: -0.3449)

# EWC (CIFAR 10)
## Single Layer
### Lambda = 10
#### 10 Epoch
##### Adam
 - 2025-03-25_08_11_39 (Task 0 Acc:  0.3906, Task 1 Acc:  0.2476, ACC: 0.3191, BWT: -0.0030)
#### 20 Epoch
 - 2025-03-25_08_29_52 (Task 0 Acc:  0.3854, Task 1 Acc:  0.2508, ACC: 0.3181, BWT: 0.0049)

# To Do List 
- [ ] 改成取樣