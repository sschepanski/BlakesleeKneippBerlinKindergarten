# Kneipp Concept: Impact on Kindergarten Children's Health

## Introduction

This project explores the impact of the Kneipp concept on the health of kindergarten children, specifically focusing on infection-related absenteeism over a 12-month period. The Kneipp concept, rooted in European tradition, emphasizes a holistic approach to health and wellness through five key elements: cold water applications, exercise, nutrition, herbs, and life balance. While widely practiced in some kindergartens, the specific health benefits for children have remained largely unexplored until now.

## Objective

The primary objective of this project is to assess whether implementing a child-friendly Kneipp concept can reduce infection-related absenteeism and improve resilience among kindergarten children. The project involves comprehensive data analysis to explore and model the relationship between the Kneipp intervention and health outcomes over the study period.

## Project Structure

- **`data/`**: Contains the dataset used in the analysis.
- **`scr/`**: R scripts for data exploration, preprocessing, modeling, and assumption testing.
- **`graphs/`**: Contains the plots and visual outputs generated during the analysis.

## Scripts

1. **KITA_children.ipynb:** This script focuses on analyzing the kindergarten-reported sick days of children. The main objective is to predict the number of sick days based on the groups (e.g., Kneipp intervention group vs. control group). Various models are applied to examine the impact of the intervention on children's health, specifically looking at infection-related absenteeism.
2. **INT.ipynb:** This script provides a descriptive analysis of the Kneipp interventions conducted across four kindergartens over the course of one year. The analysis explores the frequency and types of interventions applied in each kindergarten, examining temporal trends and variations in program implementation. Visualizations such as heatmaps help illustrate these patterns.
3. **SOSCI.ipynb:** This script analyzes parent-reported data, including information about socioeconomic background, family life, and the basic characteristics of the family and child(ren). Additionally, it covers the Common Cold Questionnaire (CCQ) responses to assess the children's health outcomes. The goal is to explore the relationship between family background and children's health, and to provide insights into factors that may influence their well-being.

## Acknowledgements

This project is based on real-world data from kindergartens practicing the Kneipp concept. The data has been anonymized to protect participant privacy.

## Getting Started

1. **Clone this repository:**

   ```bash
   git clone https://github.com/sschepanski/kneipp-project.git
   ```
2. **Set up your R environment:**
   Ensure that R is installed and configured. All required packages are integrated directly in the respective R scripts. When running a script, any missing packages will be prompted for installation.
3. **Run the provided R scripts:**
   Execute the R scripts found in the scr/ directory for data preprocessing, modeling, and assumption testing. Set your working directory to the root of the project to ensure smooth execution of the scripts.

## Contributions

This project analysis was conducted by Dr. Steven Schepanski and represents a comprehensive study into the effects of the Kneipp concept on kindergarten children's health outcomes. It is part of the manuscript by Blakeslee et al.

## License

This project is licensed under the MIT License.