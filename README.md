# COVID-19-Data-Analysis-Project

 ## 📌 Project Overview

This project analyzes COVID-19 cases, testing, and vaccination data using Python and data analysis libraries like Pandas and NumPy. The goal is to extract insights from real-world COVID-19 data and visualize trends across different states in India.

 ## 📂 Dataset Information

The analysis is based on three datasets:

 ### COVID-19 Cases Data (covid_19_india.csv)

Contains daily reported cases across Indian states.

Total Rows: 18111

Columns: 9 

Sno, Date, Time, State/UnionTerritory, ConfirmedIndianNational, ConfirmedForeignNational, Cured, Deaths, Confirmed

 ### COVID-19 Testing Data (StatewiseTestingDetails.csv)

Includes testing details for each state over time.

Total Rows: 16337

Columns: 5

Date, State, TotalSamples, Negative, Positive

 ### COVID-19 Vaccination Data (covid_vaccine_statewise.csv)

Contains state-wise vaccination records.

Total Rows: 7846

Columns: 24

Updated On, State, Total Doses Administered, Sessions, Sites, First Dose Administered, Second Dose Administered, Male (Doses Administered), Female (Doses Administered), Transgender (Doses Administered), Covaxin (Doses Administered), CoviShield (Doses Administered), Sputnik V (Doses Administered), AEFI, 18-44 Years (Doses Administered), 45-60 Years (Doses Administered), 60+ Years (Doses Administered), Male(Individuals Vaccinated), Female(Individuals Vaccinated), Transgender(Individuals Vaccinated), Total Individuals Vaccinated

## 🛠 Technologies Used

Programming Language: Python

Libraries Used: Pandas, NumPy, Matplotlib, Seaborn

Jupyter Notebook for data processing and visualization

 ## 📊 Analysis Performed

Data Cleaning: Handled missing values, standardized column names, and converted date formats.

Merging Datasets: Combined COVID-19 cases, testing, and vaccination data for integrated analysis.

Exploratory Data Analysis (EDA):

Trends in COVID-19 cases across different states.

Testing and positivity rates.

Vaccination progress over time.

## Data Visualization:

Line plots for case growth.

Bar charts for state-wise vaccination rates.

Pie charts for vaccine distribution.

## 📌 How to Run This Project

1. Clone this repository:

git clone https://github.com/yourusername/covid-data-analysis.git

2. Install required dependencies:

pip install pandas numpy matplotlib seaborn

3. Run the Jupyter Notebook:

jupyter notebook covid_analysis.ipynb

## 📎 Project Structure

📂 COVID-19 Data Analysis
│-- 📜 covid_analysis.ipynb  # Jupyter Notebook with analysis
│-- 📜 README.md              # Project Documentation
│-- 📂 datasets               # Contains CSV files
│   │-- covid_19_india.csv
│   │-- StatewiseTestingDetails.csv
│   │-- covid_vaccine_statewise.csv

## 📄 License

This project is open-source and available under the MIT License.
