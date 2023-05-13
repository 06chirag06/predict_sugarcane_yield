# To Predict Sugarcane Yield
The tremendous increases in population and random climatic changes have laid down a great challenge to the agricultural sector in terms of the unavailability of food, productivity, and sustainability. Although farmers are skilled in the cultivation of crops, there is a huge gap between scientific and technological knowledge, and their availability in rural areas. The goal is to develop a model which will predict the sugarcane produce in a particular area.
Having good sugarcane yield depends on external factors such as the fertility of the soil, the water availability, surrounding climatic conditions, the pesticides used, pH of the soil and internal factors like the quality of seeds used.<br/><br/>
The main objective of this model is to predict the sugarcane yield as a function of temperature and rainfall. The model will compare the regression algorithms namely multivariate linear regression, support vector machine, random forest and XGBoost algorithm. All the Indian states are selected for the yield prediction.
Th percentage error is found for the respective algorithms and the one with the least error value will be used to predict the production as a function of Temperature and Rainfall in a particular range.
# How to Run
In order to run the project following steps need to be followed:

	1. Install Jupyter notebook or VS Code in your computer.
	2. Run file named 'Preprocessing.ipynb', which will generate the final dataset.
	3. Run the algorithms in the order 'Random Forest.ipynb', 'XGBoost.ipynb', 'SVR.ipynb' and 'Mutivariate Linear Regression.ipynb'.
	4. Run 'Plot Error Percentage.ipynb' file to produce error percentage graph.
	5. Run 'Predict.ipynb' finally to predict the results.
	6. The file 'Without Preprocessing.ipynb' can be run anytime.

Also, below is the list of python libraries that should be available.<br/>
<b>numpy, pandas, matplotlib.pyplot, sklearn, pandas.plotting
