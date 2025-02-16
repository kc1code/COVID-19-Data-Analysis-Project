# COVID-19-Data-Analysis-Project

📌 Project Overview

This project analyzes COVID-19 cases, testing, and vaccination data using Python and data analysis libraries like Pandas and NumPy. The goal is to extract insights from real-world COVID-19 data and visualize trends across different states in India.

📂 Dataset Information

The analysis is based on three datasets:

COVID-19 Cases Data (covid_19_india.csv)

Contains daily reported cases across Indian states.

Total Rows: X

Columns:

Sno, Date, Time, State/UnionTerritory, ConfirmedIndianNational, ConfirmedForeignNational, Cured, Deaths, Confirmed

COVID-19 Testing Data (StatewiseTestingDetails.csv)

Includes testing details for each state over time.

Total Rows: Y

Columns:

Date, State, TotalSamples, Negative, Positive

COVID-19 Vaccination Data (covid_vaccine_statewise.csv)

Contains state-wise vaccination records.

Total Rows: Z

Columns:

Updated On, State, Total Doses Administered, Sessions, Sites, First Dose Administered, Second Dose Administered, Male (Doses Administered), Female (Doses Administered), Transgender (Doses Administered), Covaxin (Doses Administered), CoviShield (Doses Administered), Sputnik V (Doses Administered), AEFI, 18-44 Years (Doses Administered), 45-60 Years (Doses Administered), 60+ Years (Doses Administered), Male(Individuals Vaccinated), Female(Individuals Vaccinated), Transgender(Individuals Vaccinated), Total Individuals Vaccinated

🛠 Technologies Used

Programming Language: Python

Libraries Used: Pandas, NumPy, Matplotlib, Seaborn

Jupyter Notebook for data processing and visualization

📊 Analysis Performed

Data Cleaning: Handled missing values, standardized column names, and converted date formats.

Merging Datasets: Combined COVID-19 cases, testing, and vaccination data for integrated analysis.

Exploratory Data Analysis (EDA):

Trends in COVID-19 cases across different states.

Testing and positivity rates.

Vaccination progress over time.

Data Visualization:

Line plots for case growth.

Bar charts for state-wise vaccination rates.

Pie charts for vaccine distribution.

🔍 Insights Gained

The highest number of COVID-19 cases was observed in ______.

The testing rate varied significantly among states, with ______ conducting the highest tests.

Vaccination trends showed that ______ had the highest coverage of total doses administered.

📌 How to Run This Project

Clone this repository:

git clone https://github.com/yourusername/covid-data-analysis.git

Install required dependencies:

pip install pandas numpy matplotlib seaborn

Run the Jupyter Notebook:

jupyter notebook covid_analysis.ipynb

📎 Project Structure

📂 COVID-19 Data Analysis
│-- 📜 covid_analysis.ipynb  # Jupyter Notebook with analysis
│-- 📜 README.md              # Project Documentation
│-- 📂 datasets               # Contains CSV files
│   │-- covid_19_india.csv
│   │-- StatewiseTestingDetails.csv
│   │-- covid_vaccine_statewise.csv

📢 Contributing

Feel free to fork the repository and contribute by submitting a pull request.

📄 License

This project is open-source and available under the MIT License.
