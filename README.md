## RShiny NLP demonstration
### Project Overview
This project is an interactive R Shiny dashboard for exploring student exam score data. The app lets users filter a student performance dataset, build visualizations, and ask AI-assisted questions about the active plot.
### Mechanism
The app loads a student exam score dataset and connects it to QueryChat. QueryChat lets users filter the data using normal language. The filtered data is then used to update the plots and summaries.
### How does it work
The app has three main parts:
1.	A filter section where users choose or describe the data they want to see.
2.	A plot section where users create 2D plots, 3D plots, and histograms.
3.	A chat section where users ask questions about the current plot.
The app updates automatically when the user changes filters or plot settings.
### Dataset
The app uses a student exam scores dataset from Kaggle. The dataset has 30,641 rows. It includes math, reading, and writing scores, along with student information such as gender, ethnic group, parent education, lunch type, and test preparation.
