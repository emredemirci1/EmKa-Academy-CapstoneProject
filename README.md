# **Film Rating Misinformation Analysis**

## **Project Description**  
This project aims to analyze user rating data from multiple movie review sites to identify potential misinformation or manipulation. The main focus is on whether users on certain platforms, particularly Fandango, are providing misleading ratings. The project applies data science techniques to compare rating patterns and identify inconsistencies.

## **Table of Contents**:
1. [Project Overview](#project-overview)
2. [Datasets](#datasets)
3. [Methodology](#methodology)
4. [Results and Insights](#results-and-insights)
5. [Technologies Used](#technologies-used)
6. [How to Run the Project](#how-to-run-the-project)
7. [Conclusion](#conclusion)

## **Project Overview**  
The goal of this project is to investigate whether there is evidence of misleading or manipulated ratings on movie rating platforms, specifically focusing on Fandango. The dataset contains user rating information from various sources, and comparative analysis is done to identify discrepancies.

## **Datasets**  
- **Fandango Dataset**: Contains user ratings, votes, and other movie-related data from Fandango.
- **All Sites Dataset**: Contains movie rating information from various other platforms for comparison.

## **Methodology**  
1. **Data Cleaning and Preprocessing**: Addressed null values and standardized datasets for comparison.
2. **Exploratory Data Analysis (EDA)**: Identified rating patterns, trends, and anomalies.
3. **Comparative Analysis**: Compared Fandango's ratings with other platforms to detect discrepancies.
4. **Hypothesis Testing**: Evaluated whether discrepancies in Fandango's ratings could indicate manipulative behavior.

## **Results and Insights**  
- **Fandango Findings**: Null or zero values were detected, indicating possible gaps or manipulations in the rating data.
- **Other Platforms**: Data from other platforms showed more consistent ratings and higher participation in voting compared to Fandango.
- **Conclusion**: Fandango's rating data shows significant differences compared to other platforms, suggesting potential misinformation or manipulation in its user ratings.

## **Technologies Used**  
- Python (Pandas, NumPy, Matplotlib)
- Data Visualization (Seaborn)
- Statistical Analysis (Hypothesis Testing)

## **How to Run the Project**  
1. Clone the repository.
2. Install the required libraries using the provided `requirements.txt`.
3. Open and run the Jupyter Notebook to explore the analysis.

## **Conclusion**  
This project successfully identifies potential discrepancies in Fandango's movie ratings. Further research could involve more sophisticated models to confirm whether these discrepancies are intentional or caused by other factors.
