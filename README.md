# Covid-19 Vaccine Tracker

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Customization](#customization)
- [Acknowledgments](#acknowledgments)

## Overview

In a highly competitive job market, especially within the data analytics and data science fields, showcasing practical projects can significantly enhance your portfolio and help you stand out among other candidates. This repository contains a comprehensive Tableau dashboard project focused on tracking and analyzing COVID-19 vaccination data globally. The dashboard includes key performance indicators (KPIs), vaccination rates by country, a global vaccination map, and an analysis of the relationship between GDP per capita and vaccination rates.

By following this project, you will gain hands-on experience in:

- Connecting and preprocessing data in Tableau
- Creating interactive and insightful visualizations
- Designing a user-friendly dashboard with multiple filters and parameters
- Demonstrating your Tableau skills effectively in your portfolio

### Description

  - `covid_vaccination_data.csv`: Cleaned and preprocessed data for Tableau.
  - `Global_Vaccine_Tracker.twbx`: The Tableau packaged workbook with all visualizations and configurations.

## Features

1. **KPIs Section**
   - **Partially Vaccinated**: Displays the number of individuals with at least one dose.
   - **Fully Vaccinated**: Shows the number of individuals with two doses.
   - **Unvaccinated Percentage**: Indicates the percentage of the population not vaccinated.
   
2. **Vaccination Performance by Country**
   - Bar charts showcasing partial and full vaccination rates for each country.
   - Dual-axis charts for effective comparison.
   
3. **Global Vaccination Map**
   - Interactive map displaying vaccination rates per 100 people globally.
   - Color-coded regions for easy visualization of vaccination coverage.
   
4. **GDP vs. Vaccination Analysis**
   - Scatter plot with a logarithmic trend line showing the correlation between GDP per capita and vaccination rates.
   
5. **Interactive Filters**
   - **Continent Filter**: Allows users to filter data by continent.
   - **Country Filter**: Enables selection of specific countries.

## Getting Started

### Telling the Data Story

The **Tableau COVID-19 Vaccine Tracker** project is more than just a dashboard—it's a narrative that unfolds the global journey of COVID-19 vaccinations. Through this project, I aimed to answer critical questions about vaccine distribution, uptake, and the socio-economic factors influencing these trends.

#### **Identifying the Challenge**

At the onset of the pandemic, understanding the pace and distribution of vaccinations became paramount. The challenge was not only to visualize the raw numbers but to derive meaningful insights that could inform public health strategies and policy decisions.

#### **Data Collection and Preparation**

I sourced comprehensive vaccination data from [Our World in Data](https://ourworldindata.org/covid-vaccinations), ensuring the dataset was both extensive and up-to-date. The raw data was meticulously cleaned and preprocessed using Python, addressing missing values, standardizing formats, and ensuring consistency across different data points. This foundational work was crucial in building a reliable and accurate dashboard.

#### **Crafting the Visual Narrative**

Leveraging Tableau's powerful visualization capabilities, I designed a dashboard that tells a compelling story:

- **KPIs**: By highlighting key metrics like partially and fully vaccinated individuals, the dashboard provides an immediate snapshot of vaccination progress.
  
- **Comparative Analysis**: Bar charts and dual-axis visualizations allow for an in-depth comparison of vaccination rates across countries, unveiling patterns and outliers.
  
- **Geospatial Insights**: The global vaccination map transforms data into a geographical context, making it easier to identify regions lagging or leading in vaccination efforts.
  
- **Socio-Economic Correlations**: The GDP vs. Vaccination analysis delves into how economic prosperity influences vaccination rates, adding a layer of socio-economic context to the health data.

#### **Interactive Exploration**

To empower users to explore the data dynamically, I integrated interactive filters for continents, countries, and date ranges. This interactivity not only enhances user engagement but also allows for tailored analyses based on specific interests or inquiries.

#### **Showcasing Skills**

Throughout this project, I demonstrated a blend of technical and analytical skills:

- **Data Wrangling**: Efficiently handling and preprocessing large datasets to ensure data integrity.
  
- **Advanced Visualization**: Utilizing Tableau's advanced features like dual axes, trend lines, and geospatial mapping to create insightful and aesthetically pleasing visualizations.
  
- **Data Storytelling**: Translating complex data into a coherent and engaging narrative that highlights key insights and facilitates informed decision-making.
  
- **User-Centric Design**: Designing an intuitive and interactive dashboard that caters to both technical and non-technical audiences, ensuring accessibility and usability.

This project stands as a testament to my ability to not only analyze data but also to present it in a way that tells a meaningful story, driving understanding and action.

## Usage

1. **Open the Tableau Dashboard**
   
   - Navigate to the `dashboard/` directory.
   - Open `Global_Vaccine_Tracker.twbx` using Tableau Desktop.

2. **Explore the Dashboard**
   
   - Use the interactive filters at the top to select continents, countries, and date ranges.
   - Hover over charts to see detailed tooltips.
   - Analyze the correlation between GDP per capita and vaccination rates.

3. **Customize the Dashboard**
   
   - Modify visualizations, colors, and layouts as per your preferences.
   - Add new data sources or extend existing analyses.

## Screenshots

### Dashboard Overview

![image](https://github.com/user-attachments/assets/f66383c2-ba11-4ba5-9c25-1df75b91c288)

### Vaccination Map

![image](https://github.com/user-attachments/assets/17ea23e7-ed50-4aa1-8a8f-ae5a1fbb2e03)

### GDP vs. Vaccination Analysis

![image](https://github.com/user-attachments/assets/969e80a1-a39e-4f54-aae5-0a3819ef0daf)

## Customization

Feel free to customize the dashboard to better suit your needs or to add new features. Some customization ideas include:

- **Adding More KPIs**: Incorporate additional metrics such as daily vaccination rates or vaccine distribution by type.
- **Enhancing Visualizations**: Use different chart types or add animations for better data storytelling.
- **Integrating Additional Data Sources**: Combine vaccination data with other datasets like mobility data or healthcare capacity.
- **Improving Interactivity**: Add more filters or parameters to allow deeper data exploration.

## Acknowledgments

Our World in Data: For providing comprehensive and up-to-date COVID-19 vaccination data.
Tableau: For the powerful data visualization tools that made this project possible.
GitHub: For hosting this repository and facilitating collaboration.
Feel free to reach out if you have any questions or need further assistance with the project. Happy data analyzing!
