# PISCO_ML_Project
I will be attempting to use Supervised Machine Learning Models to predict whether or not the models can accurately predict my target feature: Purple Urchins.

# Data Source: Partnership for Interdisciplinary Studies of Coastal Oceans (PISCO)  
During my time at University, I dedicated a considerable amount of time to learning scuba diving. Throughout the years I steadily climbed to acquire my scientific diving certification; meaning, I was fully trained in conducting science (data gathering) while on scuba. 

Taking that passion to this second project, I decided to conduct my Machine learning project on the population growth of Strongylocentrotus purpuratus (Purple urchins). Luckily, my roommate, Casey Juliussen was affiliated with a non-profit known as PISCO who conducts multiple dives a day (across the Central Coast of California) collecting all sorts of data. With my fascination for trends and my knowledge of invertebrates, I used some of the data he collected in 2019. 

# 'Diving' Deaper into the Data

![f](https://user-images.githubusercontent.com/84295634/199641156-31d3cecf-cd58-45e5-8e9a-983d2f4a3313.png)

The fourth column on the right will highlight any strong or not strong correlations that urchins have with any other species listed on this graph. The goal is to identify any correlation with all the types of kelp (urchins’ main source of food). 

# Lets compare some Densities

![urchin_graph](https://user-images.githubusercontent.com/84295634/199642822-5a7ba881-00df-4842-92e5-6e65e220c190.png)

Overall densities of the purple urchin found in these areas.


![brown alg](https://user-images.githubusercontent.com/84295634/199642914-86faae27-534b-4efe-b8cf-854c0ac7adee.png)

Brown Algaes' density compared to purple urchin


![star](https://user-images.githubusercontent.com/84295634/199642989-4c8fa61a-6e25-4a22-97ba-5073ee6e51e8.png)

One of the urchins preditors


# The good stuff: Which model is best suited for the dive?

Running and tunning many models allowed me to narrow down my selection of models to the most accurate one: XGBoost. 

Accuracy | Precision on Urchin
---------|---------------------
%85      |  %90

# Conclusion

Predictive Models require a lot more variables. Swell, Chemical levels, temperature, with many more would be able to assist in the prediction of density. My outcomes from XGBoost will be able to use those variables to help organizations like PISCO to understand what trends are happening with this species of urchins. 
