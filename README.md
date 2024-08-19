# Impact Analysis of Export-Facilitating Indicators on GDP per Capita

## Project Overview

This project investigates how specific export-facilitating indicators affect GDP per capita across various countries. The analysis focuses on four key factors:
- Information and Communication Technology (ICT)
- Physical Infrastructure
- Business Environment
- Border Transport Efficiency

By employing regression analysis, the study aims to identify and quantify the impact of these factors on GDP per capita, providing insights for economic policy and decision-making.

## Objectives

- To determine the impact of ICT, Physical Infrastructure, Business Environment, and Border Transport Efficiency on GDP per capita.
- To develop a regression model to assess the significance of these factors.

## Methodology

1. **Data Collection**:
   - Data was sourced from the World Bank, covering the period from 2004 to 2007.

2. **Data Analysis**:
   - Performed descriptive statistical analysis and graphical analysis (scatter plots, box plots).
   - Conducted correlation analysis and tested for multicollinearity.
   - Used White's Test to check for heteroskedasticity.
   - Applied forward stepwise regression to identify the most significant variables.

3. **Regression Analysis**:
   - Built and evaluated multiple regression models.
   - Final model was optimized to include significant variables only.

## Results

- The final regression equation is:
GDP = -2.240 + 5.011 * (business) + 2.700 * (border_transp) + 0.801 * (ph_infrastructure)
- Adjusted R² of 0.617 indicates a strong model fit, with Business Environment and Border Transport Efficiency being significant contributors to GDP per capita.

## Key Findings

- Business Environment and Border Transport Efficiency have significant positive impacts on GDP per capita.
- ICT was omitted from the final model due to high correlation with other variables, which did not significantly affect the model's performance.
- Physical Infrastructure, while important, was not as impactful in the regression model compared to other variables.
