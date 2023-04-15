# CSE523 Machine Learning 2023 The_Learning_Machines
## Anomaly Detection
### Introduction  

The process of detecting anomalies is crucial in network
defense as it provides security administrators with advanced
warnings of potentially harmful actions such as attacks, mal-
ware, and intrusions. In computer networks, anomalies have
dynamic nature, and thus they cannot be identified easily with
any rule-based approach. Machine learning techniques are fit
for detecting such threats. We have selected an IDS dataset,
namely [CICIDS2017](https://www.kaggle.com/datasets/cicdataset/cicids2017), which covers all the eleven necessary
criteria with common updated attacks such as DoS, DDoS,
Brute Force, XSS, SQL Injection, Infiltration, Port scan, and
Botnet. However, this project only focuses on four types of
attacks: DoS Hulk, DDoS, PortScan, and DoS GoldenEye. We
implement various machine learning classifiers on our dataset
and analyze their performance to classify the attacks.  

### Results

The results we obtained are as follows:  

[Random Forest Accuracy plot](/Results/RFA.png)  
[k-Nearest Neigbours Accuracy plot](/Results/KNN.png)  
[Quadratic Discriminant Analysis Accuracy plot](/Results/QDA.png)  
[Gaussian Naive Bayes Accuracy plot](/Results/GNB.png)  
[Maximum Accuracy for every algortihm](/Results/Best_of_every.png)
### References

- [1] “Toward generating a new intrusion detection dataset and intrusion TRAFC ...” [Online]. Available: https://rb.gy/9lirab. [Accessed: 11-Mar-2023]. 
- [2] “A review on imbalanced data handling using undersampling and oversampling technique,” International Journal of Recent Trends in Engineering and Research, vol. 3, no. 4, pp. 444–449, 2017.
- [3]  V. M. Deolindo, B. L. Dalmazo, M. V. B. da Silva, L. R. B. de Oliveira, A. de B. Silva, L. Z. Granville, L. P. Gaspary, and J. C. Nobre, “Using quadratic discriminant analysis by intrusion detection systems for port scan and slowloris attack classification.”. [Accessed: 15-Apr-2023].
- [4] Yoshifumimiya, “Feature selection using ANOVA,” Kaggle, 18-Oct-2022. [Online]. Available: https://www.kaggle.com/code/yoshifumimiya/feature-selection-using-anova. [Accessed: 15-Apr-2023]. 

