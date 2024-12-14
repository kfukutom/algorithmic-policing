# Predictive Policing and Crime Forecasting: A Data-Driven Approach  
*Urban Informatics, Professor Xiaofan Liang*

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)

## Overview  
This project analyzes arrest data in Chicago (2019–2022) to explore the potential of machine learning models in predicting future arrest hotspots. The study critically examines the systemic biases in policing and proposes data-driven solutions to identify areas with heightened risks of future arrests. Our approach integrates historical crime data with neighborhood features such as socioeconomic factors, walkability, and transit accessibility.

---

## Contributors  
- **Ken Fukutomi**  
  *University of Michigan, Bachelor's of Science  
- **Benjamin Spilo**  
  *University of Michigan, Bachelor's in Science & Informatics*

---

## Abstract  
Arrests, unlike crime reports, often reflect systemic biases due to their dependence on police discretion. This project focuses on arrests as a measure of "criminality" while acknowledging the disproportionate policing of minority and low-income communities. Using machine learning, we aim to forecast future arrest hotspots in Chicago.  

Our predictive model incorporates socioeconomic and infrastructural variables, such as walkability, transit accessibility, and income levels, to provide a nuanced understanding of neighborhood conditions influencing arrest trends.

[Project Proposal](https://xfliang.notion.site/Final-Proposal-e08b2c8a118d4fd19747bded1c87b7df)  

---

## Methodology  

### Data Collection and Preprocessing  
The dataset includes:  
- Historical crime and arrest data by neighborhood  
- Walkability scores and transit accessibility  
- Socioeconomic indicators (income, education, employment rates)  

### Modeling  
We employed the k-Nearest Neighbors (k-NN) algorithm to predict crime and arrest rates.  

#### Key Steps:  
1. **Feature Engineering**  
   Selected relevant variables such as time (season, day/night), socioeconomic factors, and neighborhood accessibility.  

2. **Model Training**  
   - Similarity between neighborhoods determined via Euclidean distance.  
   - Predicted crime rates based on aggregated data from similar neighborhoods.  

3. **Prediction**  
   Utilized time-categorized data to capture seasonal and temporal crime trends for enhanced accuracy.  

> **More Info:**  
> [Scikit-learn k-NN Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)

---

## Visualizations  

![k-NN Analysis](/additional/kNearNeigh.gif)  
Visualizing the k-NN algorithm's application to neighborhood crime prediction.

---

## Feasibility and Next Steps  
This project demonstrates the feasibility of using machine learning for predictive policing while highlighting systemic challenges. Future iterations will integrate real-time data and additional dynamic factors, such as changing transit networks or economic trends, to refine predictions.

---

## Repository Usage  

### Clone the Repository  
```bash
git clone https://github.com/kfukutom/urban-informatics.git
