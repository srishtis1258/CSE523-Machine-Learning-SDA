# CSE523-Machine-Learning-SDA
**Introduction**
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

**Results**
Raw Bias Results
![image](https://user-images.githubusercontent.com/82309888/114303151-47a5b900-9aea-11eb-9f75-487558b8fe52.png)
Percentage Bias Results
![image](https://user-images.githubusercontent.com/82309888/114303163-57250200-9aea-11eb-8e01-764160ad56d4.png)

Iterative Imputer performs better than the other algorithms

**References**
1.	Vyazovskiy, V.V., 2015. Sleep, recovery, and metaregulation: explaining the benefits of sleep. Nature and science of sleep, 7, p.171.
2.	Fullagar, H.H., Skorski, S., Duffield, R., Hammes, D., Coutts, A.J. and Meyer, T., 2015. Sleep and
3.	athletic performance: the effects of sleep loss on exercise performance, and physiological  and  cognitive  responses  to exercise. Sports medicine, 45(2), pp.161-186.
4.	Nédélec, M., Halson, S., Abaidia, A.E., Ahmaidi, S. and Dupont, G., 2015. Stress, sleep and recovery in elite soccer: a critical review of  the literature. Sports Medicine, 45(10), pp.1387- 1400.
5.	Martin, B.J., 1981. Effect of sleep deprivation on tolerance of prolonged exercise. European journal of applied physiology and occupational physiology, 47(4), pp.345-354.
6.	Mah, C.D., Mah, K.E., Kezirian, E.J. and Dement, W.C., 2011. The effects of sleep extension on the athletic performance of collegiate basketball players. Sleep, 34(7), pp.943-950.
7.	Al-Kandari, S., Alsalem, A., Al-Mutairi, S., Al-Lumai, D., Dawoud, A and Moussa, M., 2017. Association between sleep hygiene awareness and practice with sleep quality among Kuwait University students. Sleep health, 3(5), pp.342-347.
8.	Demirtas, H., Freels, S.A. and Yucel, R.M., 2008. Plausibility of multivariate normality assumption when multiply imputing non-Gaussian continuous outcomes: a simulation assessment. Journal of Statistical Computation and Simulation, 78(1), pp.69-84.
		
