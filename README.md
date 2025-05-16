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
 - 2025-03-25_13_36_30 (Task 0 Acc:  0.6671, Task 1 Acc:  0.6744, ACC: 0.6708, BWT: -0.2571)
### Lambda = 25
#### 10 Epoch
##### Adam
 - 2025-03-25_12_53_07 (Task 0 Acc:  0.7643, Task 1 Acc:  0.5635, ACC: 0.6639, BWT: -0.1599)
## CNN + GAP
### Lambda = 1
#### 10 Epoch
##### Adam
 - 2025-03-25_19_11_49 (Task 0 Acc:  0.3418, Task 1 Acc:  0.8038, ACC: 0.5728, BWT: -0.5689)
### Lambda = 10
#### 10 Epoch
##### Adam
 - 2025-03-25_18_36_15 (Task 0 Acc:  0.5428, Task 1 Acc:  0.6046, ACC: 0.5737, BWT: -0.3679)
## two CNN
### Lambda = 10
#### 10 Epoch
##### Adam
 - 2025-03-25_21_34_11 (Task 0 Acc:  0.6001, Task 1 Acc:  0.7374, ACC: 0.6688, BWY: -0.3496)
### Lambda = 15
#### 10 Epoch
##### Adam
 - 2025-03-25_22_02_04 (Task 0 Acc:  0.5385, Task 1 Acc:  0.7074. ACC: 0.6230, BWT: -0.4112)
### Lambda = 20
#### 10 Epoch
##### Adam
 - 2025-03-25_22_28_07 (Task 0 Acc:  0.5730, Task 1 Acc:  0.6567, ACC: 0.6149, BWT: -0.3767)
### Lambda = 25
#### 10 Epoch
##### Adam
 - 2025-03-25_21_51_15 (Task 0 Acc:  0.6448, Task 1 Acc:  0.6010, ACC: 0.6229, BWT: -0.3049)

# EWC (MNIST 取樣)
## Single Layer
### Lambda = 1
#### 10 Epoch
##### Adam
###### 20 %
 - 2025-03-25_10_19_05 (Task 0 Acc:  0.2844, Task 1 Acc:  0.9170, ACC: 0.6007, BWT: -0.6394)
###### 80 %
 - 2025-03-25_10_55_38 (Task 0 Acc:  0.3915, Task 1 Acc:  0.8956, ACC: 0.6436, BWT: -0.5323)
### Lambda = 10
#### 10 Epoch
##### Adam
###### 5 %
 - 2025-03-26_00_34_22 (Task 0 Acc:  0.3029, Task 1 Acc:  0.9157, ACC: 0.6093, BWT: -0.6209)
 - 2025-03-26_01_28_08 (Task 0 Acc:  0.3029, Task 1 Acc:  0.9157, ACC: 0.6093, BWT: -0.6209)
     - 有固定座標軸為了報告
###### 20 %
 - 2025-03-25_11_27_13 (Task 0 Acc:  0.4055, Task 1 Acc:  0.8897, ACC: 0.6476, BWT: -0.5183)
###### 40 %
 - 2025-03-26_00_15_40 (Task 0 Acc:  0.5011, Task 1 Acc:  0.8532, ACC: 0.6772, BWT: -0.4227)
###### 50 %
 - 2025-03-25_23_48_20 (Task 0 Acc:  0.5331, Task 1 Acc:  0.8345, ACC: 0.6838, BWT: -0.3907)
###### 60 %
 - 2025-03-25_23_30_22 (Task 0 Acc:  0.5650, Task 1 Acc:  0.8228, ACC: 0.6939, BWT: -0.3588)
###### 70 %
 - 2025-03-25_23_13_13 (Task 0 Acc:  0.6026, Task 1 Acc:  0.8099, ACC: 0.7063, BWT: -0.3212)
###### 80 %
 - 2025-03-25_11_12_58 (Task 0 Acc:  0.6395, Task 1 Acc:  0.7960, ACC: 0.7178, BWT: -0.2843)
###### 100 %
 - 2025-03-26_02_24_40 
     - 有固定座標軸為了報告
### Lambda = 25
#### 10 Epoch
##### Adam
###### 20 %
 - 2025-03-25_12_03_36 (Task 0 Acc:  0.4712, Task 1 Acc:  0.8575, ACC: 0.6644, BWT: -0.4526)
###### 80 %
 - 2025-03-25_12_36_27 (Task 0 Acc:  0.7479, Task 1 Acc:  0.7253, ACC: 0.7366, BWT: -0.1759)

# EWC (fisher數量)
## Single Layer
### Lambda = 1
#### Adam
##### threshold = 0.5
 - 2025-03-25_23_04_47 (Task 0 Acc:  0.4136, Task 1 Acc:  0.8867, ACC: 0.6502, BWT: -0.5102)
### Lambda = 10
#### Adam
##### threshold = 0.2(去掉20%不要的)
 - 2025-03-26_00_11_34 (Task 0 Acc:  0.6809, Task 1 Acc:  0.7791. ACC: 0.7300, BWT: -0.2429)
##### threshold = 0.3
 - 2025-03-26_02_15_24 (Task 0 Acc:  0.6816, Task 1 Acc:  0.7785, ACC: 0.7301, BWT: -0.2422)
##### threshold = 0.4
 - 2025-03-26_01_54_15 (Task 0 Acc:  0.6787, Task 1 Acc:  0.7804, ACC: 0.7296, BWT: -0.2451)
##### threshold = 0.5
 - 2025-03-25_23_27_22 (Task 0 Acc:  0.6738, Task 1 Acc:  0.7805, ACC: 0.7272, BWT: -0.2500)
##### threshold = 0.6
 - 2025-03-26_00_39_58 (Task 0 Acc:  0.6333, Task 1 Acc:  0.7836, ACC: 0.7085, BWT: -0.2905)
##### threshold = 0.7
 - 2025-03-26_01_28_13 (Task 0 Acc:  0.4884, Task 1 Acc:  0.8104, ACC: 0.6494, BWT: -0.4354)
##### threshold = 0.8
 - 2025-03-26_00_23_08 (Task 0 Acc:  0.3528, Task 1 Acc:  0.8509, ACC: 0.6019, BWT: -0.5710)


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