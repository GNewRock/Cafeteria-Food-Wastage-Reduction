# Cafeteria Food Wastage Reduction

## Project Details
This repository contains a sanitised sample of the work done during my internship at Mu Sigma. It includes a mock dashboard and the scripts used for analysis and prediction.

### Technologies and Tools Used
* Data Analytics and Machine Learning modules in Python: pandas, numpy, sklearn, tensorflow
* HTML5, CSS
* Microsoft PowerBI
* SurveyMonkey

### Problem
My team was asked to help reduce the excessive wastage of food at the Mu Sigma cafeteria. Employees were provided free lunch at the cafeteria daily, prepared and served by external vendors. Wastage stemmed both from the overestimation of quantities while ordering (food left unserved) and the food served to employees and wasted by them.

### Process
We followed the design thinking approach while solving this problem.  
* Defining the problem: We identified stakeholders in the problem domain, and had discussions to **define** the problem statement well. This included understanding how the food committe members placed the weekly food orders, and how they measured the food wasted at the end of each day. We also obtained the data for the same, in the form of MS Excel files.
* Research: We first interacted with employees picked out at random, who we met in the cafeteria, and asked them about their experience. We understood that their food preferences influenced how often they ate at the cafeteria. We then sent out a questionnaire over email to collect quantitative data about food preferences.
* Preliminary Data Analysis: The data we collected through the questionnaire, when evaluated against the food orders and wastage data, brought to light some trends. We conveyed our insights by storyboarding the results.
* Design: To identify all the factors that influenced  wastage of food, we did more research via interviews with staff, and created a decision tree to represent the factors. We wanted to create a **data-driven predictive model** that could analyse these factors and give us the optimal food quantities to be ordered every day.
* Modelling: We tried and evaluated a few different models: linear regression, multiple regression and a simple neural network. We also set up a pipeline through which the data collected daily, along with the predictions from the various models, could be viewed on a live aggregated dashboard. This dashboard displayed the wastage trends against the influencing factors we identified. This dashboard would help the staff monitor trends and make data-driven decisions.
The following are some sections of the mock dashboard.
<img width="655" alt="graphs" src="https://user-images.githubusercontent.com/31769636/149615141-a3572091-148b-4323-9c20-51ab04baf6e9.png">
<img width="1016" alt="Screenshot 2022-01-15 at 1 55 23 PM" src="https://user-images.githubusercontent.com/31769636/149615174-ff560cfe-d99a-4427-a091-df268d5ea68b.png">
<img width="456" alt="Screenshot 2022-01-15 at 1 55 38 PM" src="https://user-images.githubusercontent.com/31769636/149615576-d54df1ac-86c2-4543-9272-8751eebefc44.png">
* Other Ideas: During the research process, we identified a method of reducing food wastage by employees: we hung posters with quotes and statistics in the cafeteria to make an emotional appeal to employees and encourage them to take only the amount of food they required.

### Learning
An essential part of the design thinking process is feedback collection and prototype evaluation. We were unable to do this in the duration of the internship. However, this was a two-fold learning experience: I learned about problem-solving processes and the basics of decision science, which gave me a strong foundation for data analytics and machine learning.

### Sanitisation
All names and values in the dataset have been modified. The dashboard is a mock of the one that was created during the internship.
