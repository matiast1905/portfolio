# Data Science Portfolio

In this repository I condensated some of my Machine Learning and Data Science projects

## [Student Dropout Analysis](https://github.com/matiast1905/student_dropout_analysis)

In this project I will analise a dataset created from a higher education institution from Portugal related to students enrolled in different undergraduate degrees. The goal of this project is to predict the probability of dropout of the students based on indicators available at an early point of their carrers. With this information, the institutions could focus their resources in the students with the highest dropout probability, and hopefully prevent that situation.

The dataset target column is divided into 3 categories: 'Graduate', 'Enrolled' and 'Dropout'. This is because the student situation is measured at the end of the expected date of graduation. The students with a value equal to 'Enrolled' are those who are still studying at the end of this period, since they couldn't graduate on time. For this project I will focus on predicting only 'Dropout', that's why I will change the target variable only to one named 'Dropout' and boolean values of 0 (not dropout) and 1 (dropout).

The result of this project is a Gradio app hosted in [Hugging Face Spaces](https://huggingface.co/spaces) and you can find it in [this link](https://huggingface.co/spaces/matiast1905/student_dropout_analysis)

## [Steel Strength Calculator](https://github.com/matiast1905/steel_strength_calculator)

In this project I try to predict the 
[**Tensile Strength**](https://en.wikipedia.org/wiki/Ultimate_tensile_strength) and the [**Yield Strength**](https://en.wikipedia.org/wiki/Yield_(engineering)) of steel alloys using the *steel composition* and *steel temperature* as predictors.

I create a **streamlit app** that allow the user to enter the composition of the steel, and gives the curves of the **tensile strength (in MPa)** and **yield strength (in MPa)** vs the *temperature (in °C)*

![streamlit_app_pic](images/streamlit_app.PNG)

The app is deployed in the streamlit server and could be accessed in [this link](https://steelstrengthcalculator-kwzjyiwygdzuqugzg87wod.streamlit.app/)

## [Characters Similarities App](https://github.com/matiast1905/characters-similarities-app)

This shiny app let the user chose a character and find the most and least similar characters in the dataset using pairwise correlation.  
The dataset comes from the [Open-Source Psychometrics Project](https://openpsychometrics.org/tests/characters/), downloaded from the  [TidyTuesday Project](https://github.com/rfordatascience/tidytuesday/tree/master/data/2022/2022-08-16), and consists of `889` characters from `100` different movies and tv shows.

You can find the app in [this link](https://matias-taron.shinyapps.io/characters_similarities/).

![characters_similarities](https://github.com/matiast1905/shiny-apps/blob/main/characters_similarities/screenshot.png)

## [Global Mortality Analysis](https://matiastaron.netlify.app/posts/global-mortality-analysis/analysis)

This is a blog post where I analise the factors that produce a difference in  death causes around the world. In this project I show different techniques that can be applied in a data analysis workflow
