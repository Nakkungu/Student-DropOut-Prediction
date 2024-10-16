# Predicting Students' Dropout and Academic Success

## Overview

This project aims to predict student dropout rates and academic success based on various demographic, academic, and socio-economic factors that were recorded at the time of enrollment. The dataset used in this project contains a rich set of features such as student’s marital status, previous qualifications, and parental education levels. By analyzing these variables, the goal is to build a predictive model that can identify students at risk of dropping out and forecast their academic performance.

## Dataset Description

The dataset includes features that represent key factors known at the time of the student’s enrollment. Below is a description of the columns:

### **Dataset Columns**

- **Marital Status**: The marital status of the student (e.g., single, married, divorced).
- **Application Mode**: The mode or type of application the student used to apply for the course.
- **Application Order**: The order in which the student applied for the course (e.g., first, second, or third choice).
- **Course**: The specific course or degree program the student is enrolled in (e.g., Computer Science, Engineering).
- **Daytime/Evening Attendance**: Indicates whether the student attends during the day or evening.
- **Previous Qualification**: The student's academic qualification before enrollment (e.g., high school diploma, vocational training).
- **Previous Qualification (Grade)**: The grade associated with the student’s previous qualification.
- **Nationality**: The nationality of the student.
- **Mother's Qualification**: The highest academic qualification attained by the student's mother.
- **Father's Qualification**: The highest academic qualification attained by the student's father.

These features are critical for building predictive models that can help identify potential academic risks and opportunities.

## Project Objectives

The primary objectives of this project are:
1. **Data Cleaning and Preparation**: Handle missing data, outliers, and prepare the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Understand the relationships between different features and their potential impact on student success or dropout.
3. **Model Building**: Build machine learning models to predict:
   - Students at risk of dropping out.
   - Academic success based on the given features.
4. **Evaluation**: Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.
5. **Visualization**: Visualize key trends and patterns in the data for better insights.

## Tools and Libraries

This project will be implemented using **R** and the following libraries:

- `tidyverse` – For data manipulation and visualization.
- `ggplot2` – For creating visualizations.
- `caret` – For model building and evaluation.
- `randomForest` – For building random forest models.
- `glmnet` – For applying logistic regression and other linear models.

## Project Structure

- `/data/`: Contains the dataset used for the analysis.
- `/scripts/`: R scripts for data cleaning, EDA, and modeling.
- `/reports/`: Final reports and visualizations from the analysis.
- `/models/`: Saved machine learning models.
- `README.md`: This file provides a project overview.

## How to Run the Project

To run this project, follow the steps below:

1. Clone this repository:  
   ```
   git clone https://github.com/yourusername/StudentDropoutPrediction.git
   ```
2. Install the required R libraries:
   ```r
   install.packages(c("tidyverse", "ggplot2", "caret", "randomForest", "glmnet"))
   ```
3. Run the data cleaning script:
   ```r
   source("scripts/data_cleaning.R")
   ```
4. Run the model building script:
   ```r
   source("scripts/model_building.R")
   ```
5. View the results and visualizations in the `/reports/` folder.

## Project Timeline

1. **Data Cleaning and Preparation**: 2 days
2. **Exploratory Data Analysis**: 3 days
3. **Model Building**: 3-4 days
4. **Evaluation and Reporting**: 2 days

## Conclusion

By leveraging the features in the dataset, this project aims to build a reliable model that can predict both student dropout risk and academic success. The findings from this analysis can help educational institutions take proactive steps to support at-risk students and improve overall student outcomes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

Special thanks to the creators of the dataset for providing valuable data for analysis.

---

This README provides potential clients or collaborators with a clear understanding of your project and how to run it, giving them confidence in your technical abilities.
