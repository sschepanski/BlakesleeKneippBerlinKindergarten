# Kneipp Concept: Impact on Kindergarten Children's Health

## Introduction

This project explores the impact of the Kneipp concept on the health of kindergarten children, specifically focusing on infection-related absenteeism over a 12-month period. The Kneipp concept, rooted in European tradition, emphasizes a holistic approach to health and wellness through five key elements: cold water applications, exercise, nutrition, herbs, and life balance. While widely practiced in some kindergartens, the specific health benefits for children have remained largely unexplored until now.

## Objective

The primary objective of this project is to assess whether implementing a child-friendly Kneipp concept can reduce infection-related absenteeism and improve resilience among kindergarten children. The project involves comprehensive data analysis to explore and model the relationship between the Kneipp intervention and health outcomes over the study period.

## Project Structure

- **`data/`**: Contains the dataset used in the analysis.
- **`scr/`**: R scripts for data exploration, preprocessing, modeling, and assumption testing.
- **`graphs/`**: Contains the plots and visual outputs generated during the analysis.

## Analysis Workflow

1. **In-Depth Exploratory Data Analysis (EDA):** Thoroughly examine the dataset, including an exploration of variable distributions and key patterns.
2. **Attrition Analysis:** Assess the dropout rates during the study period to determine any potential biases from participant attrition.
3. **Compliance Analysis:** Evaluate the adherence to the Kneipp intervention across kindergartens to assess the overall compliance and its impact on the results.
4. **Data Imputation:** Address missing data through multiple imputation techniques to ensure robustness in the final analysis.
5. **Modeling:** Utilize a negative binomial regression model to predict infection-related absenteeism, accounting for overdispersion in the count data.
6. **Assumptions Testing:** Conduct thorough diagnostics of the negative binomial regression model, including checking for overdispersion, zero inflation, and the appropriateness of residual patterns.

## Data Dictionary

| Feature            | Description                                                    |
|--------------------|----------------------------------------------------------------|
| `Child_ID`         | Unique identifier for each child                               |
| `Assessment`       | Assessment time point (baseline, follow-up)                    |
| `kindergarten_ID`  | Identifier for the kindergarten                                |
| `sickday_count_1`  | Baseline number of infection-related sick days                 |
| `sickday_count_2`  | Number of infection-related sick days during the intervention  |
| `Group`            | Group assignment (Intervention or Control)                     |
| `Cluster_1`        | Cluster identifier for random effects                          |

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