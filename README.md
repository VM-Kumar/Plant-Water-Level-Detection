# Plant Water Level Detection (Neural Network)
**Goal:** to determinie the level of water/level of wilting in soybean plants from images of its leaves(using neural networks).

![Untitled Diagram](https://user-images.githubusercontent.com/70597312/103419739-47785200-4bba-11eb-9e5f-13a3211b3c5d.png)

the content is organized as follows:
1. [Description_Report.pdf](https://github.com/VM-Kumar/Plant-Water-Level-Detection/blob/main/Description_Report.pdf) : detailed report on the neural network used and results obtained
2. [DataProcessing_Train_code.ipynb](https://github.com/VM-Kumar/Plant-Water-Level-Detection/blob/main/DataProcessing_Train_code.ipynb) : sample code to augment training data and to organize them to folders. Use paths to inuput and destination folders as given in code comment
3. [DataProcessing_Validation_code.ipynb](https://github.com/VM-Kumar/Plant-Water-Level-Detection/blob/main/DataProcessing_Validation_code.ipynb) : sample code to augment validation data and to organize them to folders. Use paths to inuput and destination folders as given in code comment
4. [train_test_split.ipynb](https://github.com/VM-Kumar/Plant-Water-Level-Detection/blob/main/train_test_split.ipynb):sample code to split training and test data randomly
5. [Densenet121.ipynb](https://github.com/VM-Kumar/Plant-Water-Level-Detection/blob/main/Densenet121.ipynb): main code to train the neural network model and obtain weights. Input must be training and validation data oraganized in 5 folders according to their class(0-4). output is the model weights file.
6. [Results.ipynb](https://github.com/VM-Kumar/Plant-Water-Level-Detection/blob/main/Results.ipynb): sample code to generate testing results. Input must be test images organized in folders according to 5 categories(0-4) and weights file obtained from Densenet121.ipynb.\
note:DataProcessing_Train_code.ipynb,DataProcessing_Validation_code.ipynb,train_test_split.ipynb are option if data is already augmented and organized into classes.




