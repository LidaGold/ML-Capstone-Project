# ML-Capstone-Project

Capstone project was completed over 3 weeks and based on data provided for ML – 2016 ML competition. Please see link https://github.com/2016-ml-contest

The purpose of the project was to take data for which I am a SME as I worked as a geophysicist for over 9 years, and apply knowledge I gained in this course.

This project's goal was not to find the best solution but rather show to the course evaluators that:

• I know how to read, clean and analyse row data

• I know how to use variety of visualizations to present data and select features to be used in models

• I have learned different models in this case I used prediction to predict digits for missing curve and I used classification models to predict final facies.

• I wanted to show that I know how to select and Hyper tune models

• Finally I wanted to show that I know how to evaluate model's validity and results.

For references I used following publicly available articles:

•	Marcelo Guarido 2019,  Machine Learning Strategies to Perform Facies Classification, Abstract from 2019 Geoconvention

•	Hall, B., 2016, Facies classification using machine learning: The Leading Edge, 35, No. 10, 906–909. 

•	Dubois, M. K., G. C. Bohling, and S. Chakrabarti, 2007, Comparison of four approaches to a rock facies classification problem: Computers & Geosciences, 33, no. 5, 599–617, http://dx.doi.org/10.1016/j. cageo.2006.08.011

In short, we were given 12 wells from Kansas. Nine wells have 5 logs each and core/facies description. The ten well were used to train data and two to apply model to predict facies.

I have looked at the original data and decided to eliminate one of the wells due to missing data. Also, two out of remaining nine wells were missing one of the logs. Marcelo Guarido (2019) pointed out that it is possible to predict missing log from existing ones. I followed his logic, but I used different ML model to predict missing log. 
Based on my modeling the best model to predict the missing log and facies is Random Forest. It shows very high 98% R2, which means that the model is overfitting. More work needs to be done to address this issue. 

 
To plot logs and facies in this format I copied code from the files contained in the contest’s GitHub. 

Jupyter Notebook has step by step description of the project.

