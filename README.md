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
 - 2025-03-24_20_49_06 (Task 0 Acc:  0.6899, Task 1 Acc:  0.7447)

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

# EWC (Fashion MNIST)
## Single Layer
### Lambda = 25
#### 10 Epoch
##### Adam
 - 2025-03-24_20_22_19 (Task 0 Acc:  0.5438, Task 1 Acc:  0.7353)


# To Do List 
- [ ] 改成取樣