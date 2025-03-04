# Traffic Accident Severity Analysis

## Project Overview

Traffic accidents are a critical public safety issue, contributing to significant loss of life and economic consequences. Understanding the factors influencing accident severity is crucial for improving road safety and optimizing emergency response strategies. This project leverages a traffic accident dataset to analyze the relationship between environmental, traffic, and road conditions to predict accident severity and uncover patterns that can contribute to smarter transportation systems.

### Objective

The primary objective of this project is to use data mining techniques to analyze traffic accident data. The goal is to identify patterns using clustering and predict accident severity using classification techniques. This analysis aims to improve road safety, optimize emergency response strategies, and contribute to better transportation systems.

### Class Label

The class label for this dataset is **Accident_Severity**, which classifies the severity of accidents into three categories:
- **Low**
- **Moderate**
- **High**

## Dataset

The dataset used for this project is a **Traffic Accident Dataset**, containing 840 instances and 14 attributes. It provides valuable insights into the factors influencing traffic accident outcomes.

### Dataset Attributes

1. **Accident_ID**: Unique identifier for each accident.
2. **Accident_Severity**: Severity level of the accident (Low, Moderate, High).
3. **Start_Time**: Timestamp when the accident started.
4. **End_Time**: Timestamp when the accident ended.
5. **Location**: Geographic location of the accident (e.g., road, intersection, city).
6. **Temperature**: Temperature at the time of the accident (in Fahrenheit).
7. **Humidity**: Relative humidity percentage at the time of the accident.
8. **Precipitation**: Amount of precipitation (e.g., rain, snow) at the time of the accident (in inches).
9. **Wind_Speed**: Wind speed during the accident (in miles per hour).
10. **Visibility**: Visibility distance at the time of the accident (in miles).
11. **Sunlight**: Whether sunlight was present (0 = No, 1 = Yes).
12. **Cloud_Cover**: Percentage of sky covered by clouds during the accident.
13. **Road_Condition**: Condition of the road (e.g., wet, icy, dry).
14. **Traffic_Volume**: Amount of traffic on the road at the time of the accident.

## Project Phases

This project is divided into three main phases, each with specific tasks can be accessed from the NoteBook folder.

### Phase 1: Data Preprocessing
- Loading and cleaning the dataset.
- Handling missing data and preprocessing categorical and numerical features.

### Phase 2: Data Mining and Model Building
- Applying clustering techniques to identify patterns in the data.
- Using classification techniques to predict accident severity.
- Evaluating and comparing the performance of different algorithms.

### Phase 3: Reporting and Presentation
- Documenting findings and visualizations of the results.
- Updating the GitHub repository based on instructor feedback.
- Preparing a short presentation summarizing the work.

## Tools & Libraries Used

- **Python**: Programming language used for data mining and analysis.
- **Jupyter Notebooks**: Environment for creating and sharing the project work.
- **Pandas**: Data manipulation and analysis library.
- **NumPy**: Numerical computing library.
- **Scikit-learn**: Library for machine learning algorithms and evaluation.
- **Matplotlib & Seaborn**: Visualization libraries for data exploration.

## Getting Started

To run this project locally, follow the instructions below:

### Prerequisites

1. Python 3.x
2. Jupyter Notebooks
3. Required libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Running the Code

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/traffic-accident-severity-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd traffic-accident-severity-analysis
   ```

3. Open the Jupyter notebook:

   ```bash
   jupyter notebook
   ```

4. Run the notebooks in order and follow the steps outlined in each phase.

## Conclusion

This project aims to apply data mining techniques to real-world traffic accident data. By identifying patterns and predicting accident severity, we can contribute to enhancing road safety, optimizing emergency responses, and ultimately improving transportation systems.


## Acknowledgements

This project is based on code originally developed by Ralshatiri (found at https://github.com/Ralshatiri/Data-mining-project) and has been modified to suit the specific requirements of this project. 

