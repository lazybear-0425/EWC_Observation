# EWC_Observation (MNIST)
## Single Layer
### w/o Modification
#### 2 Epoch 
 - 2025-03-23_13_41_26 (Task 0 Acc:  0.3643, Task 1 Acc:  0.8920)
 - 2025-03-23_13_48_01 (Task 0 Acc:  0.3631, Task 1 Acc:  0.8928)
#### 10 Epoch
 - 2025-03-23_14_16_42 (Task 0 Acc:  0.2307, Task 1 Acc:  0.9207)
 - 2025-03-23_14_31_20 (Task 0 Acc:  0.2255, Task 1 Acc:  0.9220)
### Lambda = 1
#### 2 Epoch
 - 2025-03-23_11_25_55 (Task 0 Acc:  0.6147, Task 1 Acc:  0.8193)
 - 2025-03-23_11_37_28 (Task 0 Acc:  0.5412, Task 1 Acc:  0.8509)
 - 2025-03-23_13_33_43 (Task 0 Acc:  0.5025, Task 1 Acc:  0.8422)
#### 10 Epoch
##### Adam
 - 2025-03-23_14_56_03 (Task 0 Acc:  0.4983, Task 1 Acc:  0.8616)
 - 2025-03-23_15_22_35 (Task 0 Acc:  0.3606, Task 1 Acc:  0.8837)
 - 2025-03-23_20_40_21 (Task 0 Acc:  0.3909, Task 1 Acc:  0.8909)
##### SGD
 - 2025-03-24_21_40_02 (Task 0 Acc:  0.7716, Task 1 Acc:  0.5255)
#### 10 Epoch + 2 Epoch
 - 2025-03-25_07_49_12 (Task 0 Acc:  0.5845, Task 1 Acc:  0.8322)

### Lambda = 10
#### 2 Epoch
 - 2025-03-23_11_04_54 (Task 0 Acc:  0.7141, Task 1 Acc:  0.7315, ACC: 0.7228)
 - 2025-03-23_11_12_04 (Task 0 Acc:  0.7929, Task 1 Acc:  0.6698, ACC: 0.7314)
 - 2025-03-23_11_18_31 (Task 0 Acc:  0.7658, Task 1 Acc:  0.7051, ACC: 0.7355)
#### 10 Epoch
##### Adam
 - 2025-03-23_19_30_50 (Task 0 Acc:  0.5382, Task 1 Acc:  0.8305, ACC: 0.6844)
 - 2025-03-23_19_53_21 (Task 0 Acc:  0.7152, Task 1 Acc:  0.7521, ACC: 0.7337)
 - 2025-03-23_20_15_26 (Task 0 Acc:  0.6682, Task 1 Acc:  0.7092, ACC: 0.6887)
##### SGD
 - 2025-03-24_21_09_06 (Task 0 Acc:  0.8026, Task 1 Acc:  0.3034)
##### SGD(model.parameters(), lr=0.01, momentum=0.9)
 - 2025-03-24_20_49_06 (Task 0 Acc:  0.6899, Task 1 Acc:  0.7447, ACC: 0.7173)
#### 10 Epoch + 2 Epoch
 - 2025-03-25_07_55_37 (Task 0 Acc:  0.7495, Task 1 Acc:  0.6880)
### Lambda = 25
#### 2 Epoch
 - 2025-03-23_10_42_35 (Task 0 Acc:  0.8219, Task 1 Acc:  0.6061)
 - 2025-03-23_10_51_39 (Task 0 Acc:  0.7719, Task 1 Acc:  0.6395)
 - 2025-03-23_10_58_25 (Task 0 Acc:  0.7474, Task 1 Acc:  0.6398)
#### 10 Epoch
##### Adam
 - 2025-03-23_21_41_19 (Task 0 Acc:  0.6812, Task 1 Acc:  0.7150)
 - 2025-03-23_22_10_54 (Task 0 Acc:  0.7526, Task 1 Acc:  0.7092)
 - 2025-03-23_22_36_41 (Task 0 Acc:  0.7364, Task 1 Acc:  0.7349)
##### SGD
 - 2025-03-23_23_03_30 (Task 0 Acc:  0.8103, Task 1 Acc:  0.2184)
 - 2025-03-23_23_26_45 (Task 0 Acc:  0.8143, Task 1 Acc:  0.2490)
 - 2025-03-24_19_44_31 (Task 0 Acc:  0.8124, Task 1 Acc:  0.2376)
##### SGD(model.parameters(), lr=0.01, momentum=0.9)
 - 2025-03-24_20_03_31 (Task 0 Acc:  0.7768, Task 1 Acc:  0.6751)
## Two Layer
### Lambda = 10
#### 10 Epoch
##### Adam
 - 2025-03-25_13_36_30 (Task 0 Acc:  0.6929, Task 1 Acc:  0.7075)
### Lambda = 25
#### 10 Epoch
##### Adam
 - 2025-03-25_12_53_07 (Task 0 Acc:  0.7390, Task 1 Acc:  0.6546)
## CNN + GAP
### Lambda = 1
#### 10 Epoch
##### Adam
 - 2025-03-25_19_11_49 (Task 0 Acc:  0.3517, Task 1 Acc:  0.7607)
### Lambda = 10
#### 10 Epoch
##### Adam
 - 2025-03-25_18_36_15 (Task 0 Acc:  0.6576, Task 1 Acc:  0.4631)
## two CNN
### Lambda = 10
#### 10 Epoch
##### Adam
 - 2025-03-25_21_34_11 (Task 0 Acc:  0.3997, Task 1 Acc:  0.5879)
### Lambda = 15
#### 10 Epoch
##### Adam
 - 2025-03-25_22_02_04 (Task 0 Acc:  0.3706, Task 1 Acc:  0.6572)
### Lambda = 20
#### 10 Epoch
##### Adam
 - 2025-03-25_22_28_07 (Task 0 Acc:  0.6531, Task 1 Acc:  0.6208)
### Lambda = 25
#### 10 Epoch
##### Adam
 - 2025-03-25_21_51_15 (Task 0 Acc:  0.5591, Task 1 Acc:  0.4587)

# EWC (MNIST 取樣)
## Single Layer
### Lambda = 1
#### 10 Epoch
##### Adam
###### 20 %
 - 2025-03-25_10_19_05 (Task 0 Acc:  0.2673, Task 1 Acc:  0.9210)
 - 2025-03-25_10_34_32 (Task 0 Acc:  0.2938, Task 1 Acc:  0.9185)
###### 80 %
 - 2025-03-25_10_55_38 (Task 0 Acc:  0.3821, Task 1 Acc:  0.9007)
### Lambda = 10
#### 10 Epoch
##### Adam
###### 5 %
 - 2025-03-26_00_34_22 (Task 0 Acc:  0.2831, Task 1 Acc:  0.9168, ACC: 0.6000, BWT: 0.6408)
###### 20 %
 - 2025-03-25_11_27_13 (Task 0 Acc:  0.3840, Task 1 Acc:  0.8977, ACC: 0.6409)
###### 40 %
 - 2025-03-26_00_15_40 (Task 0 Acc:  0.5406, Task 1 Acc:  0.8353, ACC: 0.6880)
###### 50 %
 - 2025-03-25_23_48_20 (Task 0 Acc:  0.4760, Task 1 Acc:  0.8445, ACC: 0.6603)
###### 60 %
 - 2025-03-25_23_30_22 (Task 0 Acc:  0.6046, Task 1 Acc:  0.8382, ACC: 0.7214)
###### 70 %
 - 2025-03-25_23_13_13 (Task 0 Acc:  0.6720, Task 1 Acc:  0.7817, ACC: 0.7269)
###### 80 %
 - 2025-03-25_11_12_58 (Task 0 Acc:  0.5776, Task 1 Acc:  0.8104, ACC: 0.6939)
### Lambda = 25
#### 10 Epoch
##### Adam
###### 20 %
 - 2025-03-25_12_03_36 (Task 0 Acc:  0.4868, Task 1 Acc:  0.8634)
###### 80 %
 - 2025-03-25_12_36_27 (Task 0 Acc:  0.7515, Task 1 Acc:  0.6684)

# EWC (fisher數量)
## Single Layer
### Lambda = 1
#### Adam
##### threshold = 0.5
 - 2025-03-25_23_04_47(Task 0 Acc:  0.3760, Task 1 Acc:  0.8992)
### Lambda = 10
#### Adam
##### threshold = 0.2
 - 2025-03-26_00_11_34 (Task 0 Acc:  0.6582, Task 1 Acc:  0.7997)
##### threshold = 0.5
 - 2025-03-25_23_27_22 (Task 0 Acc:  0.6769, Task 1 Acc:  0.7488)
##### threshold = 0.6
 - 2025-03-26_00_39_58 (Task 0 Acc:  0.5405, Task 1 Acc:  0.7876)
##### threshold = 0.8
 - 2025-03-26_00_23_08 (Task 0 Acc:  0.3802, Task 1 Acc:  0.8255)


# EWC (Fashion MNIST)
## Single Layer
### Lambda = 25
#### 10 Epoch
##### Adam
 - 2025-03-24_20_22_19 (Task 0 Acc:  0.5438, Task 1 Acc:  0.7353)

# EWC (CIFAR 10)
## Single Layer
### Lambda = 10
#### 10 Epoch
##### Adam
 - 2025-03-25_08_11_39 (Task 0 Acc:  0.3594, Task 1 Acc:  0.2498)
#### 20 Epoch
 - 2025-03-25_08_29_52 (Task 0 Acc:  0.3675, Task 1 Acc:  0.2528)

# To Do List 
- [ ] 改成取樣