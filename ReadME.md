
### USE CASE: Can the cost of health insurance be estimated automatically?


#### Background: 
Insurance company especially health insurance company need to analyze how a customer is disease prone. We will try to find the risk based on the customers data.


If the Health_Risk can be estimated accurately then insurance cost can be calculated using this formula.

<center> <br>Health Insurance Cost = Base Cost + α * Health Risk</br></center>


#### Investigation on how accurately it can be estimated the health risk of a person.

#### Data Source:  [National Center for Health Statistics](www.cdc.gov/nchs/fastats/deaths.htm)

### Data Preprocessing
Total records : 1.04 M
Has disease and non disease records. 
Disease related records : 0.56 M 
No. of feature: 34

### Feature information: 

#### Median and Quartile of each features

<img src="https://github.com/igupta967937/Predicted_Health_Insurance/blob/master/results/featureStatsWithoutFeature17.png"></img>

#### Outlier Detection
Used Box-Whisker plot to detect outlier. 
<img src="https://github.com/igupta967937/Predicted_Health_Insurance/blob/master/results/featureStatsWithoutFeature17.png"></img>


#### Class Imbalance
Has high class imbalance <img src="https://github.com/igupta967937/Predicted_Health_Insurance/blob/master/results/classImbalance_scaled.png"></img>



### Classification
In this Project I Applied K-Nearest Neighbour, Random Forest, Neural Network and Support Vector Machine algorithms to classify the different health risk.
