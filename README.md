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
    - Validation will be by
- **Following on from the above, I predict that physical exercise is protective against CKD.**
    - Validation will be by
- **I also predict that patients with Metabolic Syndrome whose biomarkers are within normal range due to medication as less likely to have CKD.**
    - Validation will be by
- **Lastly, I predict that medical checkup frequency, medical adherence and health literacy are protective against CKD.**
    - Validation will be by

## Project Plan
1. Data aquisition and ETL; Pandas, Feature Engine
2. Data exploration: simple analysis and visualisation; Matplotlib
3. Data analysis and visulaisation to answer hypotheses; Seaborn, Plotly

* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

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
    - 
 In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.