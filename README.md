# final-project: COVID-19 Deaths. Correlated factors

This repository contains our final project related to a database of the first year of COVID-19 pandemic in Mexico

# Team 2

Felipe de Jesus Gutierrez Davila
Alan Aurelio Cejudo Rodríguez
Cecilia Lizcano Martinez
Silvia Aurora Perez Corzas


# Introduction

Coronavirus is an infectious illness caused by  the SARS-CoV-2 virus. The majority of virus-infected individuals will recover from mild to moderate respiratory infection without the need for additional care. Nonetheless, a small percentage will get really sick and need medical care.

Our presentation link: https://docs.google.com/file/d/1aLouWn5rTnE2baoRaMe8UEqz1GR0UlMn/edit?filetype=mspresentation


# About our Dataset

The DGE (Dirección general de epidemiología) data collected between January 2020 and June 2021 in Mexico are used in this study.  

DGE link: https://www.gob.mx/salud/acciones-y-programas/informacion-epidemiologica

# Parameters

We take in consideration the next parameters in our study: demographics, treatment specifics, morbidities related to the infection. 

# Tools used

* SQLite: An embedded relational database management system without a server is called SQLite. It is an unrestricted, free library that runs entirely in memory and doesn't need to be installed.

* AWS: AWS, or Amazon Web Services, is a comprehensive and dynamic cloud computing platform that offers a range of packaged software as a service (SaaS), platform-as-a-service (PaaS), and infrastructure-as-a-service (IaaS)options. AWS services can provide a company with resources like content delivery, database storage, and processing capacity. During this segment, we also utilized Logistic Regression.

* Machine Learning: A subfield of computer science and AI called “machine learning” focuses on using data and algorithms to simulate human learning processes and progressively increase their accuracy.During this project, we utilized Logistic Regression in order to estimate the probability of an event occurring, based on a given dataset of independent variables. We also utilized Random Forest and Neural Networks.

* Tableau: This type of statistical model is often used for classification and predictive analytics. Logistic regression estimates the probability of an event occurring, based on a given dataset of independent variables. Since the outcome is a probability, the dependent variable is bounded between 0 and 1.

# Process

You can find the process and coding in the Programs and AWS folders. The first part were the scrapping of the data by pandasframe and SQLite, this also help us to make more easy to work with Tableau and cleaning data was very helpful to apply different algorithms to compare our data and predictions. Using AWS was an extra feature we add to compare and know better our dataset. 

The visualizations was made entirely by Tableau, the links of the workbooks are: 

https://public.tableau.com/app/profile/alan.cejudo/viz/Final_project_team_2/Historia1?publish=yes

https://public.tableau.com/views/COVIDdashboard_17001021979780/Dashboard4?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link


# Conclusions

The results obtained for each of the Tools used were the following:

Logistic regression: 94.70% accuracy
Neural Network: 95.81% accuracy 
Random Forest: 96% accuracy
AWS (Logistic regression): 94.71% accuracy

The resulting model is considered successful and will let us know the probability of dying of COVID for a patient considering the eligibility in the parameters considered to build the model.

# Research

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10325129/#:~:text=Risk%20factors%20that%20contribute%20to,and%20a%20history%20of%20smoking.

# Photos

Doctor taking coronavirus test sample
Front view of medical control for covid19 concept
People in protective equipment disinfecting a dangerous area
Person wearing protective equipment with copy space
Woman wearing a medical protective equipment
