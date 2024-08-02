# LLNL_DataScience
2024 Lawrence Livermore National Laboratory Data Science Challenge

## Challenge Details:
- #### Task 1 : Heartbeat Classification
  Get familiar working with ECG data by using the ECG Heartbeat Categorization Dataset to perform binary classification for healthy heartbeat vs. irregular heartbeat
- #### Task 2 : Irregular Heartbeat Classification
  Diagnosing an irregular heartbeat by using the ECG Heartbeat Categorization Dataset to perform multiclass classification to diagnose the irregular heartbeats.
- #### Task 3 : Activation Map Reconstruction from ECG
  Sequence-to-vector prediction using the Dataset of Simulated Intracardiac Transmembrane Voltage Recordings and ECG Signals to perform activation map reconstruction (i.e. transform a sequence of length 12x500 to 75x1 using a neural network)
- #### Task 4 : Transmembrane Potential Reconstruction from ECG
  Sequence-to-sequence prediction using the Dataset of Simulated Intracardiac Transmembrane Voltage Recordings and ECG Signals to perform transmembrane potential reconstruction (i.e. transform a sequence of length 12x500 to 75x500 using a neural network)
- Learn more: [Original LLNL Data Science Introduction Repo](https://github.com/landajuela/cardiac_challenge/tree/main?tab=readme-ov-file)

## Datasets:
- [Task 1 & 2](https://www.kaggle.com/datasets/shayanfazeli/heartbeat/data)
- [Task 3 & 4](https://library.ucsd.edu/dc/object/bb29449106)

## About the files:
- [Personal notebook](Albert's_LLNL_DataScience_Challenge_Notebook.ipynb)
  - Walks through the learning process of the tasks (1-3)
  - Discusses machine learning methods/techniques
  - Runs through the training/testing models
  - Displays diagrams of datasets
- [Personal test notebook](LLNL_DataScience_Tests.ipynb)
  - Secondary notebook for processing data
  - Trains/Processes task 1-3 data while running personal notebook
  - More diagrams for data
- [Task 3 and 4 test notebook](SqueezeNet_for_Task_3.ipynb)
  - Mainly task 3 data manipulation
  - Development of a model for task 3 classification
  - Walks through the individual layers of the model
- [Task 3 and 4 final model](squeezenet_ecg_to_vm_200.pth)
  - Finalized 1D Squeezenet model for heart ECG activation/lead prediction
