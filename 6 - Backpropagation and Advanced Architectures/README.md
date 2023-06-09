
Model :
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1           [-1, 10, 26, 26]              90
       BatchNorm2d-2           [-1, 10, 26, 26]              20
              ReLU-3           [-1, 10, 26, 26]               0
            Conv2d-4           [-1, 10, 24, 24]             900
       BatchNorm2d-5           [-1, 10, 24, 24]              20
              ReLU-6           [-1, 10, 24, 24]               0
            Conv2d-7           [-1, 15, 22, 22]           1,350
       BatchNorm2d-8           [-1, 15, 22, 22]              30
              ReLU-9           [-1, 15, 22, 22]               0
        MaxPool2d-10           [-1, 15, 11, 11]               0
           Conv2d-11           [-1, 10, 11, 11]             150
      BatchNorm2d-12           [-1, 10, 11, 11]              20
             ReLU-13           [-1, 10, 11, 11]               0
           Conv2d-14             [-1, 10, 9, 9]             900
      BatchNorm2d-15             [-1, 10, 9, 9]              20
             ReLU-16             [-1, 10, 9, 9]               0
           Conv2d-17             [-1, 10, 7, 7]             900
      BatchNorm2d-18             [-1, 10, 7, 7]              20
             ReLU-19             [-1, 10, 7, 7]               0
           Conv2d-20             [-1, 10, 5, 5]             900
      BatchNorm2d-21             [-1, 10, 5, 5]              20
             ReLU-22             [-1, 10, 5, 5]               0
           Conv2d-23             [-1, 10, 1, 1]           2,500
================================================================
Total params: 7,840
Trainable params: 7,840
Non-trainable params: 0


Accuracy:

EPOCH: 9
Loss=0.01970233954489231 Batch_id=468 Accuracy=99.41: 100%|██████████| 469/469 [00:02<00:00, 221.88it/s]  
Test set: Average loss: 0.0166, Accuracy: 59718/60000 (99.53%)

EPOCH: 10
Loss=0.04306318983435631 Batch_id=468 Accuracy=99.49: 100%|██████████| 469/469 [00:02<00:00, 218.18it/s]  
Test set: Average loss: 0.0163, Accuracy: 59711/60000 (99.52%)

EPOCH: 11
Loss=0.09505224972963333 Batch_id=468 Accuracy=99.50: 100%|██████████| 469/469 [00:02<00:00, 216.41it/s]  
Test set: Average loss: 0.0141, Accuracy: 59745/60000 (99.58%)

EPOCH: 12
Loss=0.05094130337238312 Batch_id=468 Accuracy=99.51: 100%|██████████| 469/469 [00:02<00:00, 213.14it/s]  
Test set: Average loss: 0.0119, Accuracy: 59806/60000 (99.68%)

EPOCH: 13
Loss=0.009522756561636925 Batch_id=468 Accuracy=99.58: 100%|██████████| 469/469 [00:02<00:00, 212.90it/s] 
Test set: Average loss: 0.0111, Accuracy: 59821/60000 (99.70%)

EPOCH: 14
Loss=0.005547039210796356 Batch_id=468 Accuracy=99.60: 100%|██████████| 469/469 [00:02<00:00, 214.67it/s]  
Test set: Average loss: 0.0099, Accuracy: 59828/60000 (99.71%)
