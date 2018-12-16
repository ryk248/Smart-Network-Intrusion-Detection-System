# Smart-Network-Intrusion-Detection-System

With the boom of the Internet and its powerful ability to store and share data across networks, the number and diversity of cyber network attacks have also increased. Servers of many companies have been victims of such network attacks (one of the most popular examples being the data breach at Yahoo in 2014: around 3 billion accounts were compromised in this attack). With the advent of technology, these network attacks have become sophisticated and hence difficult to detect, creating an immediate need of an intelligent Network Intrusion Detection system to detect and classify anomalous behavior.

In this project, we used various machine learning classification techniques to first predict if the packet captured over the network is a genuine regular packet or an attack and then we leverage the data gathered to detect if it is one of the various types of network attacks like Denial of Service, Backdoors, Worms, Exploits etc.

1) Models used for Binary classification - Random Forest and XGBoost
2) Models used for Multiclass classification - Random Forest

Accuracy scores:

1) Binary Classification: 
a) Random Forest - Precision = 91.53% and Recall = 89.9%
b) XGBoost - Precision = 90.6% and Recall = 95.67%

2) Multiclass Classification:
a) Random Forest - Precision = 79.07% and Recall = 71.3%

All the steps followed in the project along with the model configuration are mentioned in the report presented with this repository. 
