# Weather Data Analysis

This project is a beginner-friendly Exploratory Data Analysis (EDA) of historical weather data using Python. The goal was to clean and understand the dataset, perform statistical analysis, and answer specific weather-related queries without any data visualization.

---

## 📁 Project Structure

- `Weather analysis.ipynb` – Jupyter Notebook containing all analysis steps
- `weather.csv` – Dataset used for the project

---

## 🔍 Project Highlights

- Loaded and explored the weather dataset using pandas
- Cleaned the data (checked for null values, unique counts)
- Performed descriptive analysis (mean, max, min, std)
- Filtered and answered weather-related queries:
  - Count of clear weather conditions
  - Frequency of snowy or foggy conditions
  - Conditions where wind speed exceeded average
  - Days with exact visibility or temperature thresholds
- Renamed columns for better readability

> **Note:** This project does not include visualizations. It focuses on querying and reasoning with the data using `pandas`.

---

## 🧰 Tech Stack

- Python 3
- Jupyter Notebook
- pandas
- numpy

---

## 📝 Sample Questions Answered

- How many times was the weather exactly "Clear"?
- What was the mean visibility?
- What are all the times when it snowed?
- What is the average wind speed when the weather is cloudy?
- How many times did the pressure exceed 1020.0 hPa?
- What are all instances when:
  - Weather is "Clear" and Relative Humidity > 50
  - Wind speed > 24 and Visibility = 25
  - Weather condition is Snow or visibility < 4

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Amina-Afreen-M/Data-Analysis.git
   cd Data-Analysis
   ```

2. Install required libraries:
   ```bash
   pip install pandas numpy
   ```

3. Open the notebook:
   ```bash
   jupyter notebook
   ```

4. Run `Weather analysis.ipynb` and follow along.

---

## 📌 Future Work

- Add data visualizations using matplotlib/seaborn
- Extend queries to find correlations
- Integrate live weather data via APIs
- Create a dashboard for interactive analysis

---

## 👩‍💻 Author

**Amina Afreen M**  
📧 [aminafreenm20@gmail.com](mailto:aminafreenm20@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/amina-afreen-m/)  
💻 [GitHub](https://github.com/Amina-Afreen-M)

---


