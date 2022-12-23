# Survival-prediction-of-COVID-19-patients-using-multi-modal-dataset
This repository contains code and dataset for the paper titled "Survival prediction of COVID-19 patients using multi-modal dataset", accepted at IEEE INDICON 2022.


The proposed Bi-Stream Gated Attention-based CNN (BSGA-CNN) model is used to classify the Clinical data collected from COVID-19-positive patients admitted at MGM college and hospital as shown in figure \ref{GA-CNN}. As the name suggests, it contains two streams of convolutional layers: the lower-hand-side convolutional layer (LHSC) and the upper-hand-side Convolutional layer (UHSC). Both of them use an attention module followed by a Gated sigmoid activation.
![Figure 1](https://github.com/sagardeepdeb/Survival-prediction-of-COVID-19-patients-using-multi-modal-dataset/blob/main/model_diagram.png)


Finally the AUROC curve is given in figure below

![Figure 2](https://github.com/sagardeepdeb/Survival-prediction-of-COVID-19-patients-using-multi-modal-dataset/blob/main/AUC%20Curve.png)
