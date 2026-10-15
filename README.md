Lab: Guided Practice Project


Estimated Effort: 60 mins

Project Scenario
You have been employed as a data analyst by a Healthcare consultancy firm which has been conducting a survey on the state of global happiness annually. The World Happiness Report offers valuable insights into factors influencing happiness across countries. The firm wants you to produce a report to find out whether there are demographic, regional, and/or economic characteristics that lead to a better life.

The project tasks are data preparation, analysis, visualization, and dashboarding. Based on the data set, you must write prompts to generate the Python codes for performing specific tasks. You can access a JupyterLite-based testing environment to test the generated codes using the Generative AI classroom prompts.

The tasks assigned to you are as follows:

Check the correctness of the data types in the dataset.

There might be a few missing values in the dataset. Data cleaning will be a part of the assignment.

You have to perform exploratory data analysis to draw insights on the data:

Identify the GDP per capita and Healthy Life Expectancy of the top 10 countries and represent it as a bar chart
Find the correlation between the Economy (GDP per Capita), Family, Health (Life Expectancy), Freedom, Trust (Government Corruption), Generosity, and Happiness Score
Create a scatter plot to identify the effect of GDP per Capita on Happiness Score in various Regions
Create a pie chart to present Happiness Score by region
Create a map to display GDP per capita of countries and include Healthy Life Expectancy to be shown as a tooltip
Create a dashboard with at least four of the above visualizations

Generate the narrative to present the dashboard

You decide to use Generative AI to create python codes that can help you analyze the data, determine the best features and create the visualization as per requirement.

Disclaimer: This is a fictitious scenario created for the purpose of this project. The dataset being used is publicly available.

About the data set
The World Happiness Report is a landmark survey of the state of global happiness. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness. This is a public dataset available on the Kaggle website as World Happiness Report under the CC0: Public Domain license. For this guided practice project we will work on the year 2016 data, which has been slightly modified for the purpose of this guided practice project.
You can download it from here: 2016

Attributes of this dataset have been explained below.
Variable	Description
Country	Name of the country
Region	Region the country belongs to
Happiness Rank	Rank of the country based on the Happiness Score
Happiness Score	A metric measured in 2016 by asking the sampled people the question: "How would you rate your happiness?"
Lower Confidence Interval	Lower Confidence Interval of the Happiness Score
Upper Confidence Interval	Upper Confidence Interval of the Happiness Score
Economy (GDP per Capita)	The extent to which GDP contributes to the calculation of the Happiness Score
Family	The extent to which Family contributes to the calculation of the Happiness Score
Health (Life Expectancy)	The extent to which Life expectancy contributes to the calculation of the Happiness Score
Freedom	The extent to which Freedom contributes to the calculation of the Happiness Score
Trust (Government Corruption)	The extent to which Trust contributes to the calculation of the Happiness Score
Generosity	The extent to which Generosity contributes to the calculation of the Happiness Score
Dystopia Residual	Dystopia is an imaginary country that has the world's least-happy people. The residuals, or unexplained components, differ for each country, reflecting the extent to which the six variables either over- or under-explain average 2014-2016 life evaluations. These residuals have an average value of approximately zero over the whole set of countries
Code execution environment
To test the prompt-generated code, open the Jupyter Notebook that you have been provided with in the succeeding lab in the course.

The data set for this lab is available in the following URL.

plaintext

URL = "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-AI0272EN-SkillsNetwork/labs/dataset/2016.csv"
Complete the setup in the Jupyter Notebook and then proceed further.

Important Note: All prompts that are made available have been hidden and the users are encouraged to first try to write their own prompts to create the solutions. Also, the prompts given as solutions have also been maintained as ones which will create generic code structures which you can modify according to the question at hand.
