# Undestanding Risk Factors in Chronic Kidney Disease

This project aims to analyse a comprehensive dataset of factors which could have a role in the development of chronic kidney disease (CKD), in this specific population. 

CKD has an extremely high socioeconomic impact, including: direct medical costs, affecting ~ 7.2 million people at a cost of ~ £6.4 billion per year in the UK (ckdexplained.co.uk), and 35.5 million people at a cost of $130 billion per year in the US (Medicare data 2022); indirect costs such as loss of working capacity and premature mortality; and severe Quality of Life costs.


## Dataset Content
- The [**Chronic Kidney Disease Dataset**](https://www.kaggle.com/datasets/rabieelkharoua/chronic-kidney-disease-dataset-analysis/discussion/512947) is publicly available from kaggle
- It contains 1659 rows (i.e. patients) and 54 columns (i.e. variables)
- Variables can be broadly divided into (this is not a exhaustive list):
    - Descriptors: age; sex; gender ethnicity; body-mass index (BMI)
    - Biomarkers: blood pressure; cholesterol; HbA1c
    - Modifiable environmental factors: smoking; alcohol consumption; diet; exercise
    - Non (or less) modifiable environemental factors: Heavy metal or chemical exposure; water quality
    - Prior medical history: acude kidney disease; urinary/ renal infection
    - Family history: CKD; hypertension
    - Symptoms of CKD: electrolyte imbalance; edaema; fatigue; nausea    


## Business Requirements
The business requirement is to develop a better understanding of the risk factors in CKD, which will allow government healthcare agencies, academic researchers and biotech companies to devise more effective monitoring, prevention and treatment strategies, which aim to reduce morbidity and mortality from CKD.


## Questions, Hypothesis and how to validate?
#### Questions
- What risk factors most strongly associate with CKD?
- What factors separate patients with diabetes and/ or hypertension who have CKD from those who don't i.e. what factors might be protective against CKD?

### Hypotheses
- Diabetes and hypertension are 2 of the biggest known risk factors for CKD. These conditions are thought to result from 'Metabolic Syndrome', which is characterised by abdominal obesity, hypertriglyceridemia, reduced High-Density Lipoprotein (HDL) cholesterol, and hyperglycemia.
- **I therefore predict that these markers of Metabolic Syndrome are also risk factors for CKD.**
    - Validation will be by using individual scatter plots grouped by CKD patient or control.
- **Following on from the above, I predict that physical exercise is protective against CKD.**
    - Validation will be by KDE plot grouped by CKD patient or control.
- **Lastly, I predict that medical checkup frequency, medical adherence and health literacy are protective against CKD.**
    - Validation will be by KDE plot grouped by CKD patient or control.

After basic analysis, it was found that patients with a family history of kidney diesase appear overrepresented in CKD cases, suggesting a genetic component.
- **I therefore predict that CKD patients with a family history of kidney disease will be younger than CKD patients without family history.**
    - Validation will be by box plots using Plotly.

## Project Plan
1. Data aquisition and ETL; Pandas, Feature Engine
2. Data exploration: simple analysis and visualisation; Matplotlib
3. Data analysis and visulaisation to answer hypotheses; Seaborn, Plotly

* A new csv file will be created at the end of ETL and read into the new notebook for more visualisations
* I used stacked bar plots for categorical data because it is easy to see proportions
* I used KDE plots to visualise the distribution of continuous numerical data as it is again, easy to compare groups
* I used scatter plots to look for correlations in the continuous numeric variables
* I used box plots to compare grouped numeric data

## The rationale to map the business requirements to the Data Visualisations
* My analysis allowed me to gain a deeper understanding of the factors associated with CKD in this population. Some of my hypotheses were proved wrong, which highlights the need and usefulness of the analysis, as this will inform downstream stakeholder how and where to place resources.

## Analysis techniques used
* I imported my data from a csv file; looked at basic information and statistics; I made a data type change to help my basic visualisation; carried out basic visualisations of all appropriate variables; transformed the DataFrame by adding summary columns; visualised and answered hypotheses using Seaborn and Plotly.
* I structured the data analysis techniques according to the ETL process shown. I did basic visualisation to understand what transformations I wanted to do. When ETL was complete, I moved on to answer my questions/ hypotheses.
* I think that the lack of correlations in the data was a little limiting
* I used ChatGPT in particular to help with plot, title and legend optimisations

## Ethical considerations
* In this case, there are no ethical considerations as the dataset was already ananymised

## Unfixed Bugs
* I wanted to repeat a KDE plot of 'HealthManagement', it was the same data as plotted previously, but almost the same code gave me a different plot. In the end I deleted the repeat plot and asked the reader to look previously.

## Development Roadmap
* I understood what we have learned and could remember what was possible, but it felt like I spent quite a bit of time looking back for code. 
* However, I am happy that a lot of basic code feels familiar.

## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Plotly


## Credits 
- I would like to acknowledge and thank Rabie El Kharoua for making this dataset available, and kaggle for hosting it.
- I would like to acknowledge the use of ChatGPT and Co-Pilot in generating and debugging my code. 
    - Co-pilot suggested to add .gitattributes file to deal with Line Feed warning by Git


### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)



## Acknowledgements (optional)
* I'd like to thank Vasi for his encouragement and understanding.