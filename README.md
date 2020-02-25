# TSAI-S5
List of files to be shared in the 5th session of the TSAI

EVA4S5F1:

Target:

Included BatchNorm in this model and included the 3*3 kernel as the last kernel.

Results:
Parameters: 6.9k
Best Train Accuracy: 99.58%
Best Test Accuracy: 98.84%
Epochs - 15
Final Receptive Field Calculated - 23

Analysis:
The Model is over-fitting. 
Even if the model is pushed further, it won't be able to get to 99.4
With 20 epochs, the model is able to get 99.76% and 99.07% train and test accuracy, which is still over-fitting

EVA4S5F2:

Target:

Included BatchNorm and included Drouput in specific layers where the test accuracy was going down. Included the 3*3 kernel as the last kernel.

Results:
Parameters: 6.9k
Best Train Accuracy: 99.07%
Best Test Accuracy: 98.01%
Epochs - 15
Final Receptive Field Calculated - 23

Analysis:
The Model is good. 
if the model is pushed further, it will be able to reach the target of 99.4% accuracy
With 20 epochs, the model is able to get 99.17% and 99.13% train and test accuracy
One thing noted is that the model looks underfitting till the second last epoch

EVA4S5F4:

Target:

Included BatchNorm and included Drouput after each layer excluding the last layer. Included the 3*3 kernel as the last kernel.

Results:
Parameters: 7.6k
Best Train Accuracy: 99.06%
Best Test Accuracy: 98.0%
Epochs - 15
Final Receptive Field Calculated - 23

Analysis:
The Model is good. 
if the model is pushed further, it will be able to reach the target of 99.4% accuracy

EVA4S5F3:

Target:

Included BatchNorm and reduced Drouput value from 0.1 to 0.01. Included the 3*3 kernel as the last kernel.

Results:
Parameters: 7.6k
Best Train Accuracy: 99.45%
Best Test Accuracy: 99.31%
Epochs - 15
Final Receptive Field Calculated - 23

Analysis:
The Model is good. 
if the model is pushed further, it will be able to reach the target of 99.4% accuracy


