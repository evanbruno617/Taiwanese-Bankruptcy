# Taiwanese-Bankruptcy
# Purpose
The purpose of this project is to use data and characteristics of taiwanese companies in order to predict which companies will go bankrupt. 

# Analysis
The data was gathered from Kaggle's website. After importing model it was put into a random forest regression model. Where it had a 61% accuracy but only a 29% recall.
For bankruptcies being able to accurately predict them is great however the goal is to predict the majority of them. By apply undersampler to the data and inputting into a gradient machine learning model
it was able to give us the results below. 
![image](https://github.com/evanbruno617/Taiwanese-Bankruptcy/blob/main/Resources/Screenshot%202024-10-16%20at%204.30.57%E2%80%AFPM.png)
Where the best outcome was only a 19% precision but a 84% accuracy.

# Conclusion
When predicting bankruptcies the goal is to make sure most of the companies that will go bankrupt are predicted and the precision does not matter as much because for investors they would rather
have some companies be excluded from the rest than having a higher chance of picking a one that will go bankrupt. 
