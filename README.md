# PU-GNN
A Positive Unlabeled Learning method for Polypharmacy Side-effects Detection based on Graph Neural Networks
PU- GNN
This repository provides a framework of three stages that combine several drug features to predict DDS-associated events, using attributed heterogeneous networks and multiple deep neural networks. 

 PU-GNN involves three main steps: 


![abstract](https://github.com/abedin-keshavarz234/PU_GNN/assets/76855169/c9fae299-6ab0-4b99-aaa5-7dc8194d493f)



1-Dimensionality reduction to extract optimal features: By reducing the feature dimensions, we aim to capture the most effective features for model evaluation. 

![g11](https://github.com/abedin-keshavarz234/PU_GNN/assets/76855169/a140b402-84d8-4503-a35f-92565236b895)


2-Addressing data uncertainty through positive unlabeled (PU) learning: We employ PU learning to identify positive and negative data from unlabeled data, reducing uncertainty and enhancing model accuracy. 

![G2](https://github.com/abedin-keshavarz234/PU_GNN/assets/76855169/c38859f7-6f35-408e-a7c0-c3ae346f4a49)

3. Predicting simultaneous side effects of drug pairs using a Graph Neural Network model: Our method predicts polypharmacy between two drugs efficiently using a neural graph network-based model.

![g3](https://github.com/abedin-keshavarz234/PU_GNN/assets/76855169/68bc2c12-d2b2-4142-afea-7e74008ad504)


![q_all (1)](https://github.com/abedin-keshavarz234/PU_GNN/assets/76855169/5672f390-7b96-4e5e-b7f7-b00d5ca78ec0)


 We implement this model, which enables this model to be trained with GPUs. For additional details, read the published article for this work through this link.

Environments

Python 3.6.12 

Tensorflow 2.1

numpy 1.19

pandas 1.1.3

Usage
 You can access the data from the GitHub link. When using this code, you need to clone this repo and load all the files in the folder into your running environment first. Then, Copy the PU_GNN_ run_DS2.py file and run it in your environment. All the files you want are in the (project folder).
In the google colab environment, you can run the program by saving the project folder in the google drive environment.
Then copy and run the PU_GNN_ run_DS2 file in the google colab environment

