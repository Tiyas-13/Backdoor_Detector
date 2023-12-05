## Backdoor Detector in Neural Network using Pruning

Response to Lab 4 Assignment for ML for Cybersecurity, NYU Tandon School of Engineering, Fall 2023
### Main Solution

- ```backdoor_detector.ipynb``` contains the code to create the GoodNet network and evaluate defense against the Youtube Face dataset
- ```report.pdf``` contains a report for the study

### Steps To Run

1. The dataset can be downloaded from this link: https://drive.google.com/drive/folders/1Rs68uH8Xqa4j6UxG53wzD0uyI8347dSq

In the ipynb file here, I have stored the data in a google drive. 
For local use, the data can be stored in the data folder. 
The original BadNet models are present in the models folder. In my code I have used a link from Google Drive.
Please change the path for all necessary files indicated by the commented lines in the ipynb file. 

2. Google Colab comes pre-installed with the necessary dependencies, however to run elsewhere, please install the following modules using pip:
```
pip install keras
pip install h5py
pip install numpy
pip install tensorflow
pip install matplotlib
```

3. Evaluation

To simply evaluate the created repaired_nets, the .h5 files can be found in the models folder. They can be used with:
```
model = load_model('repaired_net_threshold_{value}.h5')
```


   
