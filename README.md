# Data-Driven Car Purchase Optimization: An Analytical Approach Using Multi-Attribute Value Theory

## The complete analysis is documented in [Application of Multi-Attribute Value Theory for Car Purchase Decision Optimization]

## Description
This project applies **Data Analytics** and **Multi-Attribute Value Theory (MAVT)** to optimize car purchasing decisions. The report provides a structured, quantitative approach to evaluating multiple car attributes, ultimately recommending the most suitable vehicle for a family based on comprehensive data analysis.

## Overview

### 1. Introduction
- **Background**: A three-member family seeks a reliable, fuel-efficient car for city driving.
- **Objective**: Utilize MAVT to make an informed car purchase decision by analyzing multiple attributes and constraints.

### 2. Problem Formulation
- **Fundamental Objectives**: Identified through discussions, the objectives include cost-effectiveness, reliability, performance, space, and environmental impact.
- **Attributes**: Key attributes analyzed are:
  - **Price**: €16,000 - €14,000
  - **Fuel Consumption**: 10–3 liters/100km
  - **Repair Costs**: €3,000 - €200
  - **Age**: 10–0 years
  - **Mileage**: 120,000 - 20,000 km
  - **Reliability Ratings**: 0–99
  - **Performance (Horsepower)**: 90–150 HP
  - **Acceleration (0–100 km/h)**: 20–6 seconds
  - **Braking Distance**: 50–10 meters
  - **Cargo Space**: 700–2,000 liters
  - **Car Type**: Binary (Hatchback or Farmer)
  - **Environmental Impact (CO2 Emissions)**: 150–95 g/km

### 3. Data Collection and Analysis
- **Data Sources**: Car listings from [Kamux](https://www.kamux.fi/?gad_source=1&gclid=Cj0KCQjw8MG1BhCoARIsAHxSiQkqOc8raSjckvhK1b5fUnMI5pZ2C28SuqhzkIoJrRlXSsFXTaXPhI0aAptUEALw_wcB), reliability ratings, repais cost estimators from [Caredge.com](https://caredge.com/) and [J.D. Power](https://www.jdpower.com/).
- **Data Analytics**: 
  - **Cleaning and Preprocessing**: Ensured data accuracy and consistency.
  - **Normalization**: Scaled attributes using linear and non-linear value functions.
  - **Attribute Scaling**: Applied methods like the bisection method for non-linear attributes (e.g., repair costs, mileage).

### 4. Elicitation of Objectives’ Weights
- **SWING Method**: Utilized to prioritize attributes by assigning weights based on their impact on the decision-making process.
- **Weight Distribution**: Emphasized attributes with higher importance to the family’s needs.

### 5. Results
- **MAV Scores Calculation**: Computed for each car alternative.
- **Top Recommendations**: The analysis revealed “Skoda Octavia – 2017” as the optimal choice with a MAV score of 0.562.
- **Ranking**: Detailed ranking of all alternatives based on MAV scores for transparency.

### 6. Discussion and Conclusion
- **Theoretical Assumptions**: Evaluated assumptions like Mutual Preference Independence and Difference Independence.
- **Behavioral Biases**:
  - **Generating Objectives and Alternatives**: Addressed biases like desirability bias and omission bias.
  - **Attribute Scaling**: Mitigated scaling biases using natural attributes and external data sources.
  - **Weight Assignment**: Used the SWING method to prevent equalizing bias.
- **Limitations**:
  - **Data Reliability**: Manufacturer’s data vs. real-world conditions.
  - **Subjectivity in Ratings**: Variability and potential biases in reliability ratings.

### 7. Appendices
- **Figures and Tables**: Detailed illustrations of fundamental objectives, attribute ranges, decision alternatives, and MAV scores.
- **Documentation**: Comprehensive details on data sources, value functions, and calculation methods.

## Key Highlights
- **Analytical Rigor**: Robust data analytics techniques for accurate and reliable decision-making.
- **Quantitative Analysis**: Clear, numerical evaluation of attributes and alternatives.
- **Visualization**: Detailed visual representations of data and results.
- **Transparency**: Extensive documentation of methods and data sources.
- **Bias Mitigation**: Strategies to identify and reduce biases in the decision-making process.

This project demonstrates the power of integrating data analytics with decision-making theories like MAVT to provide clear, actionable insights in complex scenarios such as car purchasing.

