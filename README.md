# 911 Calls Capstone Project

## Overview
This project analyzes 911 call data to extract insights about emergency calls, including trends, locations, and common reasons for calls. The dataset used for this project is sourced from Kaggle and contains various attributes related to 911 calls.

## Dataset Details
The dataset consists of the following fields:
- **lat**: Latitude of the call location
- **lng**: Longitude of the call location
- **desc**: Description of the emergency call
- **zip**: Zipcode where the call was placed
- **title**: Title indicating the reason for the call
- **timeStamp**: Timestamp of the call (YYYY-MM-DD HH:MM:SS format)
- **twp**: Township where the call occurred
- **addr**: Address of the emergency
- **e**: Dummy variable (always 1)

## Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas** (for data manipulation)
- **NumPy** (for numerical operations)
- **Matplotlib & Seaborn** (for data visualization)

## Project Workflow
1. **Data Loading**: Importing the dataset and examining its structure.
2. **Data Cleaning**: Handling missing values and data formatting.
3. **Exploratory Data Analysis (EDA)**:
   - Understanding call distribution across different townships.
   - Identifying the most common call reasons.
   - Visualizing the frequency of calls by time (hour, day, month).
   - Mapping the locations of emergency calls.
4. **Insights & Conclusions**: Summarizing key findings.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Haroon-89/911-calls-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd 911-calls-analysis
   ```
3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Open the Jupyter Notebook and run the analysis:
   ```bash
   jupyter notebook
   ```

## Results & Insights
- The most common emergency types and their frequency.
- Trends in emergency calls based on time and location.
- Visual representation of emergency hotspots.

## Contributing
Feel free to contribute by improving visualizations, adding more analysis, or optimizing the code!

## License
This project is for educational purposes. The dataset belongs to its respective owner (Kaggle dataset).

