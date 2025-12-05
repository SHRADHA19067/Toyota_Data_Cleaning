Toyota Car Data Cleaning & Analysis

This project focuses on cleaning, preprocessing, and analyzing Toyota car sales data to prepare it for further exploration and machine learning tasks. The dataset contains information such as price, mileage, year, fuel type, transmission, and other important vehicle features.


---

🔹 Project Objectives

Remove missing, duplicate, and inconsistent records

Handle incorrect data types

Clean categorical and numerical columns

Detect and treat outliers

Prepare the dataset for visualization and ML modeling

Generate insights from cleaned data



---

🔹 Key Steps Performed

✔ 1. Loading the dataset

Imported CSV/Excel file

Inspected rows, columns, and data types


✔ 2. Data Cleaning

Removed duplicate rows

Treated missing values

Cleaned inconsistent categories (fuel type, transmission, etc.)

Converted price and mileage to numeric format

Handled outliers using IQR method


✔ 3. Feature Engineering

Extracted useful features (e.g., car age)

Converted categorical data to proper labels


✔ 4. Exploratory Data Analysis

Visualizations were created to answer:

Which fuel type has highest price?

Does transmission affect price?

Which features influence resale value?

Price distribution across models



---

🔹 Tech Stack Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook / Google Colab

Excel (for initial exploration)



---

🔹 Files in This Repository

File	Description

toyota.py	Python script for cleaning and analyzing Toyota dataset
toyota_data.csv / .xlsx	Raw dataset
README.md	Project documentation



---

🔹 Sample Insights

Diesel cars show higher resale value

Automatic transmission vehicles are costlier than manual

Car age and mileage are the most important features affecting price



---

🔹 How to Run the Project

1. Clone the repository


2. Install required libraries

pip install pandas numpy matplotlib seaborn


3. Run the script

python toyota.py




---

🔹 Conclusion

This project demonstrates real-world data cleaning skills and prepares a high-quality dataset suitable for price prediction models, dashboards, and exploratory analysis.
