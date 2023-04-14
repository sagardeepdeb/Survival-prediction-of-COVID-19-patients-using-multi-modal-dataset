# Survival-prediction-of-COVID-19-patients-using-multi-modal-dataset

# This repository contains code and dataset for the paper titled "Survival prediction of COVID-19 patients using multi-modal dataset", accepted at 2022 IEEE 19th India Council International Conference (INDICON) and the paper can be obtained from [here](https://ieeexplore.ieee.org/abstract/document/10040102).


The proposed Bi-Stream Gated Attention-based CNN (BSGA-CNN) model is used to classify the Clinical data collected from COVID-19-positive patients admitted at MGM college and hospital as shown in figure \ref{GA-CNN}. As the name suggests, it contains two streams of convolutional layers: the lower-hand-side convolutional layer (LHSC) and the upper-hand-side Convolutional layer (UHSC). Both of them use an attention module followed by a Gated sigmoid activation.
![Figure 1](https://github.com/sagardeepdeb/Survival-prediction-of-COVID-19-patients-using-multi-modal-dataset/blob/main/model_diagram.png)

## Dataset creation

The multi-model dataset for survival prediction of COVID-19 infected patients was collected at Mahatma Gandhi Memorial Medical College, Indore. The dataset was prepared under the supervision of the experienced radiologists. The dataset contains clinical entries of patients along with their Chest X-Ray images. The dataset was created to predict the survival chances of the COVID-19-positive patients using two different data modalities. The data were randomized and anonymized so that the identity of the patients were not revealed.  
The dataset prepared contains a total of 419 patients. Out of them, 57\% are male, and the rest are female. The mean age of all the patients is 40 $\pm$ 20 years. Pregnant women and children under ten were not included in the study. The dataset was collected between February 2021 and October 2021. It contains 230 patients in the Survival class and 189 in the Deceased class. 

The heatmap shon below depicts the positive and negative association between different attributes. The correlation of attributes in the i-th row and j-th column is represented by each cell c(i, j) in the grid. The positive connection between feature pairs increases as the cell colour approaches green. As shown, Blood pressure and Nausea are having high correlation whereas Blindness and Tunnel Vision are having almost zero correlation between all other feature entries.
![Figure2](https://github.com/sagardeepdeb/Survival-prediction-of-COVID-19-patients-using-multi-modal-dataset/blob/main/corelation.png)

Finally the AUROC curve is given in figure below

![Figure 3](https://github.com/sagardeepdeb/Survival-prediction-of-COVID-19-patients-using-multi-modal-dataset/blob/main/AUC%20Curve.png)

## !! Prior permission from the authors is must for using the dataset. 

## Citation
Please cite our paper if you find the work useful: 
<pre>
  @INPROCEEDINGS{10040102,
  author={Deb, Sagar Deep and Jha, Rajib Kumar and Talera, Yash and Tripathy, Prem S and Agrawal, Simran and Jha, Kamlesh},
  booktitle={2022 IEEE 19th India Council International Conference (INDICON)}, 
  title={Survival prediction of COVID-19 patients using multi-modal dataset}, 
  year={2022},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/INDICON56171.2022.10040102}}
</pre>
