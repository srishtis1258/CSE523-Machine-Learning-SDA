# CSE523-Machine-Learning-SDA
Sleep and Physical Performance Analysis: A case study of Collegiate Women’s Basketball Players
Over the decade, there has been a considerable amount of research done in analyzing the impact of sleep and exercise on the performance and recovery of an athlete. The long term objective of this research is to make use of the Machine Learning paradigm to create a predictive model that would help a coach determine whether a player is fit to play in the forthcoming match on the basis of the underlying patterns and correlations between sleep, training load, cognitive state information of the athlete and their performance. In this term, the objective in this project duration is to perform necessary data imputations as a part of preprocessing of data.

A real time dataset collected for an experiment to be conducted over 17 women’s basketball team players from Sacred Heart University. For imputations, Whoop Strap Data is considered:
There are 1810 records (14 weeks of data)
Attributes: 26 (RHR, HRV, Sleep Score, Hours of Sleep, Wake Periods, Sleep Consistency, Respiration Rate, etc.)

Data Imputation Techniques Experimented
1. Imputation using Global Mean
2. Imputation using Local Mean
a. k-Means Clustering based Imputations on entire dataset
b. RHR based k-Means Clustering
c. light-sleep (hours) based k-Means Clustering
3. Imputation using Linear Regression
a. Deterministic Linear Regression based Imputations
b. Stochastic Linear Regression based Imputations
c. Iterative Imputer based Imputations

Results suggest: Iterative Imputer works best for data imputations

