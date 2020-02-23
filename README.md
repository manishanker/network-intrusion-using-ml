# network-intrusion-using-ml

Dataset url : https://www.unb.ca/cic/datasets/ids-2017.html

I took some parts of the dataset and tried to see how ML techniques like Decision Tree, Random Forest, ANN, SVM work in detecting
Network attacks vs a normal traffic

DOS, DDOS, PORTSCAN attacks are considered for this experiment. Was able to achieve 99.99 % accuracy. The shape of the dataframe 
was in the order of 1.2 Million X 79 

All the columns were continuous except the target column which was categorical. 

Later, I used PCA to reduce the dimension to 1.2 Million X 22 columns with a minor drop in Accuracy 0.01%.
