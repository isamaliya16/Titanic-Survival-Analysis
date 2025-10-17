# 🛳️ Titanic Survival Analysis

## 📘 Project Description
This project performs **Exploratory Data Analysis (EDA)** on the famous Titanic dataset.  
The goal is to understand the factors that influenced passenger survival, such as:

- Gender  
- Passenger class  
- Age  
- Embarkation point  
- Fare

We use clear visualizations to represent survival patterns simply and effectively.

---

## 📊 Dataset
**Dataset:** Titanic Dataset — Kaggle (Titanic: Machine Learning from Disaster)

The dataset contains passenger details such as:
- `Name`  
- `Age`  
- `Sex` (Gender)  
- `Pclass` (Ticket class)  
- `Fare`  
- `Survived` (0 = No, 1 = Yes)

---

## 🧰 Tools & Libraries
This project uses the following Python libraries:
- **pandas** — Data cleaning and analysis  
- **matplotlib** — Plotting and visualizations  
- **seaborn** — Advanced and attractive charts

---

## ⚙️ Steps Performed
1. **Import libraries** — Loaded pandas, matplotlib, and seaborn.  
2. **Load dataset** — Imported the Titanic CSV file into a DataFrame.  
3. **Data exploration**  
   - Checked for missing values  
   - Viewed summary statistics and data structure  
4. **Data cleaning**  
   - Handled missing values in `Age` and `Embarked`  
   - Converted categorical data (e.g., `Sex`) to numerical form when needed  
5. **Data visualization** — Created plots such as:  
   - Overall survival count  
   - Survival by gender  
   - Survival by passenger class  
   - Survival by age groups  
   - Correlation heatmap

---

## 📈 Example Visuals
- Bar chart showing survival by gender  
- Pie chart for class distribution  
- Histogram of passenger ages  
- Heatmap showing correlations among features

---

## 🧾 Key Findings
- **Females** had a much higher survival rate than males.  
- **First-class** passengers survived more often than lower classes.  
- **Younger** passengers generally had better chances of survival.

---

## 💡 Conclusion
Gender, passenger class, and age played major roles in determining survival on the Titanic.  
This project demonstrates how straightforward EDA and visualization can uncover meaningful insights from real-world datasets.

---

## 🚀 How to Run
1. Download the Titanic dataset from Kaggle: *"Titanic: Machine Learning from Disaster"*.  
2. Place the CSV file in the project directory.  
3. Open the Jupyter Notebook file `Titanic Survival Analysis.ipynb`.  
4. Run each cell step-by-step to reproduce the analysis and visualizations.

Optional: create a virtual environment and install dependencies:
```bash
python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows
pip install pandas matplotlib seaborn
